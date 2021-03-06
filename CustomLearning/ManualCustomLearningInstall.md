---
author: pkrebs
ms.author: pkrebs
title: Руководство по установке путей обучения
ms.date: 02/18/2019
manager: bpardi
description: Руководство по установке путей обучения
ms.service: sharepoint-online
ms.topic: article
ms.openlocfilehash: 6f106b569602730f16fc2b6f8a09fa44667e32e1
ms.sourcegitcommit: 33acfc2149de89e8375b064b2223cae505d2a102
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52575974"
---
# <a name="manually-installing-and-configuring-custom-learning-for-office-365"></a>Ручная установка и настройка настраиваемого обучения для Office 365

Веб-часть Microsoft Custom Learning создается с SharePoint Framework [версии](/sharepoint/dev/spfx/sharepoint-framework-overview) 1.7.1.

Чтобы вручную установить и настроить веб-часть и коллекцию сайтов, необходимо выполнить следующие действия:

1. Проверка того, что вы выполнили все необходимые условия.
1. Установите файл customlearning.sppkg в каталоге Office 365 клиента.
1. Provision/Identify a modern communication site to act as your Custom Learning for Office 365 home site.
1. Выполните сценарий PowerShell, который настроит клиента соответствующими артефактами, от которых зависит настраиваемое обучение.
1. Перейдите на страницу сайта CustomLearningAdmin.aspx, чтобы загрузить веб-часть администратора для инициализации настраиваемой конфигурации контента.

## <a name="prerequisites"></a>Предварительные условия

Необходимо настроить и настроить каталог приложений для всех клиентов. См. [раздел Настройка Office 365 клиента и](/sharepoint/dev/spfx/set-up-your-developer-tenant#create-app-catalog-site) раздел Создание сайта каталога приложений. Если каталог приложений для клиента уже завершен, вам потребуется доступ к учетной записи, которая имеет права на отправку пакета в него для завершения этого процесса настройки. Как правило, эта учетная запись SharePoint администратора. Если учетная запись с этой ролью не работает, перейдите в центр администрирования SharePoint и найдите администраторов коллекции сайтов для коллекции сайтов каталога приложений и войдите в качестве одного из администраторов коллекции сайтов, или добавьте учетную запись SharePoint администратора, которая не удалось администраторам коллекции сайтов. Вам также потребуется доступ к учетной записи, которая является администратором SharePoint клиента.

## <a name="upload-the-web-part-to-the-tenant-app-catalog"></a>Upload веб-часть каталога приложений клиента

Чтобы настроить настраиваемый Office 365 для Office 365, вы загрузите файл customlearning.sppkg в каталог приложений для клиента и развернете его. Подробные инструкции по добавлению приложения в каталог приложений в SharePoint в Интернете см. в книге ["Использование](/sharepoint/use-app-catalog) каталога приложений".

## <a name="provisionidentify-modern-communication-site"></a>Provision/Identify Modern Communication Site

Либо определите существующий сайт SharePoint связи, либо задайте новый в клиенте SharePoint Online. Дополнительные сведения о создании сайта связи см. в веб-сайте [Create a communication site in SharePoint Online](https://support.office.com/article/create-a-communication-site-in-sharepoint-online-7fb44b20-a72f-4d2c-9173-fc8f59ba50eb) и следуйте шагам по созданию сайта связи.

## <a name="set-permissions-for-the-site"></a>Настройка разрешений для сайта

Необходимо добавить в группу "Посетители" всех, кто должен иметь возможность просматривать контент, и всех, кто должен иметь возможность администрирования пользовательских списков воспроизведения в группу Участников. Чтобы настроить сайт для настраиваемого обучения в первый раз, пользователь должен быть администратором коллекции сайтов или частью группы Владельцев.

Добавление настраиваемой Office 365 для приложения в коллекцию сайтов.

## <a name="execute-powershell-configuration-script"></a>Выполнение сценария конфигурации PowerShell

Сценарий PowerShell включен, который необходимо выполнить для создания трех свойств `CustomLearningConfiguration.ps1` клиента, которые использует решение. [](/sharepoint/dev/spfx/tenant-properties) Кроме того, сценарий [](/sharepoint/dev/spfx/web-parts/single-part-app-pages) создает две страницы приложения для отдельных частей в библиотеке страниц сайта для размещения веб-частей администратора и пользователя в известном расположении.

### <a name="disabling-telemetry-collection"></a>Отключение коллекции телеметрии

Часть этого решения включает анонимную систему отслеживания телеметрии, которая по умолчанию включена. Если выполняется ручная установка и вы хотите отключить отслеживание телеметрии, измените сценарий, чтобы $optInTelemetry переменная `CustomlearningConfiguration.ps1` $false.

Если вы не выполняете ручную установку и хотите отключить отслеживание телеметрии, был включен отдельный сценарий, который при запуске отключит отслеживание `TelemetryOptOut.ps1` телеметрии.

## <a name="initialize-web-part-custom-configuration"></a>Инициализация настраиваемой конфигурации веб-части

После успешного запуска сценария PowerShell перейдите в `<YOUR-SITE-COLLECTION-URL>/SitePages/CustomLearningAdmin.aspx` . Это инициализирует элемент списка CustomConfig, который настраивает настраиваемый процесс обучения для его первого использования.

Конфигурация завершена, и вы можете двигаться вперед с помощью настраиваемой системы обучения для Office 365. Дополнительные сведения см. в документации пользователя.

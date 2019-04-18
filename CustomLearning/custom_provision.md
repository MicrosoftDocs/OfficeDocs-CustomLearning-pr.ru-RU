---
author: pkrebs
ms.author: pkrebs
title: Подготовка настраиваемого сайта обучения
ms.date: 02/10/2019
description: Подготовка настраиваемого обучения для сайта Office 365 с помощью модуля подготовки SharePoint
ms.openlocfilehash: 868708f9f096c84d5ebc5f9bc4e21e558da84d2b
ms.sourcegitcommit: 5ea8d7fdc255ef7de06f41b3c794bc40551cf5bb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/14/2019
ms.locfileid: "30577865"
---
# <a name="provision-custom-learning"></a>Подготовка настраиваемого обучения 

С помощью службы подготовки SharePoint Online администратор клиента Office 365 может начать процесс подготовки с помощью нескольких простых щелчков мыши. Служба подготовки является рекомендуемым способом подготовки настраиваемого обучения. Она быстро, легко и занимает несколько минут, чтобы начать процесс. Тем не менее, прежде чем приступить к работе со службой подготовки, убедитесь, что выполнены необходимые условия для подготовки.

## <a name="prerequisites"></a>Необходимые компоненты
 
Для успешной настройки настраиваемого обучения со службой подготовки необходимо, чтобы пользователь, выполняющий подготовку, соответствовал следующим предварительным требованиям: 
 
- Пользователь, который подготавливает обучение, должен быть администратором клиента клиента, на котором будет подготовлено пользовательское обучение.  
- Каталог приложений клиента должен быть доступен в параметрах приложений центра администрирования SharePoint. Если в вашей организации нет каталога приложений клиента SharePoint, обратитесь к [документации SharePoint Online](https://docs.microsoft.com/en-us/sharepoint/use-app-catalog) , чтобы создать ее.  
- Настраиваемый обучающий пользователь должен быть владельцем семейства веб-сайтов в каталоге приложений клиента. Если пользователь, который подготавливает обучение, не является владельцем семейства веб-сайтов каталога приложений, [выполните приведенные ниже инструкции](addappadmin.md) и продолжайте. 

### <a name="to-provision-custom-learning"></a>Подготовка настраиваемого обучения

1. Перейдите к http://provisioning.sharepointpnp.com верхнему правому углу домашней страницы и **Войдите в** него.  Войдите с учетными данными целевого клиента, на котором планируется установить шаблон сайта.

![пнфоме. png](media/inst_signin.png)

2. Отмените **согласие от имени вашей организации** и нажмите кнопку **принять**.

![возврата](media/inst_perms.png)

3. ПроКрутите страницу вниз, перейдите на вкладку **решения** , а затем выберите **пользовательское обучение для Office 365**. 

![возврата](media/inst_select.png)

4. Выберите **Добавить в клиент**

![инст_селект. png](media/inst_add.png)

5. ЗаПолните поля на странице сведения о подготовке в соответствии с требованиями вашей установки. Как минимум введите адрес электронной почты, на который вы хотите получать уведомления о процессе подготовки, и конечный URL-адрес сайта, на который будет выполняться подготовка.  
> [!NOTE]
> Сделайте конечный URL-адрес сайта понятным для ваших сотрудников, например "/СИТЕС/митраининг" или "/teams/LearnOffice365".

![инст_оптионс. png](media/inst_options.png)

6. Выберите **подготовить** , когда вы будете готовы к установке настраиваемого обучения в клиентской среде.  Процесс подготовки займет до 15 минут. Вы получите уведомление по электронной почте (на адрес электронной почты с уведомлением, введенный на странице подготовки), когда сайт будет готов к доступу. 

> [!IMPORTANT]
> Администратор клиента, который подготавливает настраиваемый сайт обучения, должен перейти на сайт, а затем открыть **кустомлеарнингадмин. aspx** для инициализации настраиваемых свойств администратора обучения. В настоящее время Администратор клиента также должен назначить владельцами сайт. 

## <a name="validate-provisioning-success-and-initialize-the-customconfig-list"></a>Проверка успешности подготовки и инициализация списка Кустомконфиг

По завершении подготовки администратор клиента, который подготавливает сайт, получает электронное письмо от службы подготовки PnP. Сообщение содержит ссылку на сайт. На этом шаге администратор клиента должен перейти на сайт, используя ссылку, приведенную в сообщении электронной почты, и настроить сайт для первого использования:

- Перейдите по ссылке `<YOUR-SITE-COLLECTION-URL>sites/<YOUR-SITE-NAME>/SitePages/CustomLearningAdmin.aspx`. При открытии **кустомлеарнингадмин. aspx** инициализируется элемент списка **кустомконфиг** , в котором настраивается особое обучение для первого использования. Должна отобразиться страница, которая выглядит следующим образом:

![кг-админапппаже. png](media/cg-adminapppage.png)

## <a name="add-owners-to-site"></a>Добавление владельцев для сайта
Как администратор клиента, маловероятно, чтобы пользователь настраивает сайт, поэтому необходимо назначить сайт нескольким владельцам. Владельцы имеют административные права на сайте, чтобы они могли изменять страницы сайта и изменять фирменный стиль сайта. Они также могут скрывать и показывать контент, доставленный через пользовательскую веб-часть обучения. Кроме того, они могут создавать настраиваемые списки воспроизведения и назначать их настраиваемым подкатегориям.  

1. В меню **Параметры** SharePoint выберите разрешения для **сайта**.
2. Нажмите кнопку **Дополнительные параметры разрешений**.
3. Щелкните **пользовательское обучение для владельцев Office 365**.
4. Нажмите кнопку **создать** > ,**чтобы добавить пользователей в эту группу**, а затем добавьте пользователей, которых вы хотите сделать владельцами. 
5. Добавьте ссылку для [просмотра сайта](custom_exploresite.md) в сообщении общего доступа, а затем щелкните **общий доступ**.

### <a name="next-steps"></a>Следующие действия
- ИзУчите [контент по умолчанию](custom_exploresite.md) , указанный на сайте и веб-части.
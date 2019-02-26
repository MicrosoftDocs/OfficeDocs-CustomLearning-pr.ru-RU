---
author: karuanag
ms.author: karuanag
title: Предварительные требования для установки
ms.date: 02/11/2019
description: Решения и сведения о предварительных требованиях для выборочной установки и настройки обучения
ms.openlocfilehash: 1a57e8fbecfbce4608c8dcb618f4fdc007467789
ms.sourcegitcommit: e10085e60ca3f38029fde229fb093e6bc4a34203
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 02/25/2019
ms.locfileid: "29989720"
---
# <a name="getting-started"></a><span data-ttu-id="fb148-103">Начало работы</span><span class="sxs-lookup"><span data-stu-id="fb148-103">Getting Started</span></span>

<span data-ttu-id="fb148-p101">Пользовательское обучение для Office 365 позволит вам предоставлять учебные решения по запросу в Организации.  Здесь мы расскажем о необходимых требованиях и решениях, которые необходимо выполнить для успешного развертывания.</span><span class="sxs-lookup"><span data-stu-id="fb148-p101">Custom Learning for Office 365 will allow you to provide on-demand training solutions for your organization.  Here we will discuss the pre-requisites and decisions you will need to make for a successful deployment.</span></span>

<span data-ttu-id="fb148-p102">В следующих инструкциях описывается подготовка настраиваемого обучения для Office 365 (CLO365), в том числе Установка шаблона сайта для обмена данными CLO365 и настраиваемой веб-части обучения в клиентской среде. В https://provisioning.sharepointpnp.com этих инструкциях ОПИСЫВАЕТСЯ установка CLO365 через службу подготовки SharePoint Online, если вы хотите установить только настраиваемую веб-часть обучения для использования на существующем сайте для обмена данными SharePoint Online, обратитесь к разделу инструкции по [установке настраиваемой веб-части](installwebpart.md).</span><span class="sxs-lookup"><span data-stu-id="fb148-p102">The following instructions outline how to provision Custom Learning for Office 365 (CLO365), including the installation of the CLO365 communication site template and the Custom Learning web part, into your tenant environment. These instructions cover the installation of CLO365 via the SharePoint Online Provisioning Service at https://provisioning.sharepointpnp.com    If you are interested in installing just the Custom Learning web part for use on an existing SharePoint Online communication site, please refer to the instructions for [installing the custom webpart](installwebpart.md).</span></span> 

## <a name="prerequisites"></a><span data-ttu-id="fb148-108">Необходимые компоненты</span><span class="sxs-lookup"><span data-stu-id="fb148-108">Prerequisites</span></span>
 
<span data-ttu-id="fb148-109">Для успешной установки CLO365 через [службу подготовки SharePoint Online](https://provisioning.sharepointpnp.com) необходимо выполнить следующие предварительные требования:</span><span class="sxs-lookup"><span data-stu-id="fb148-109">To successfully install CLO365 via the [SharePoint Online Provisioning Service](https://provisioning.sharepointpnp.com) you must meet the following pre-requisites:</span></span> 
 
- <span data-ttu-id="fb148-110">Для установки необходимо, чтобы пользователь, который будет подготовлен к работе CLO365, был администратором клиента целевого клиента.</span><span class="sxs-lookup"><span data-stu-id="fb148-110">The individual that will be provisioning CLO365 must be the tenant administrator of the target tenant for install.</span></span>  
- <span data-ttu-id="fb148-p103">Клиент "Каталог приложений" должен быть доступен в параметре "Apps" центра администрирования SharePoint. Если у вас в настоящее время нет каталога приложений, обратитесь к [документации SharePoint Online](https://docs.microsoft.com/en-us/sharepoint/use-app-catalog) , чтобы подготовить эту функцию.</span><span class="sxs-lookup"><span data-stu-id="fb148-p103">A tenant 'App Catalog' must be available within the 'Apps' option of the SharePoint Admin Center. If you do not have an app catalog currently refer to the [SharePoint Online documentation](https://docs.microsoft.com/en-us/sharepoint/use-app-catalog) to provision this feature.</span></span>  
- <span data-ttu-id="fb148-p104">Для установки CLO365 необходимо быть владельцем семейства веб-сайтов для каталога приложений в целевом клиенте. Если CLO365 Installer не является владельцем семейства веб-сайтов каталога приложений, [выполните приведенные ниже инструкции](addappadmin.md) и продолжайте.</span><span class="sxs-lookup"><span data-stu-id="fb148-p104">The individual that will be provisioning CLO365 must be a site collection owner of the app catalog in the target tenant for install. If the CLO365 installer is not a site collection owner of the app catalog [complete these instructions](addappadmin.md) and continue.</span></span>  

### <a name="next-steps---service-decisionsservicedecisionsmd"></a><span data-ttu-id="fb148-115">Дальнейшие действия: [решение для обслуживания](servicedecisions.md)</span><span class="sxs-lookup"><span data-stu-id="fb148-115">Next Steps - [Service Decisions](servicedecisions.md)</span></span>

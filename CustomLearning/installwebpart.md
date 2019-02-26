---
author: karuanag
ms.author: karuanag
title: Установка настраиваемой веб-части решения для обучения
ms.date: 02/10/2019
description: Инструкции по установке для веб-части настраиваемого решения для обучения
ms.openlocfilehash: 53229e5b1b8175b06d888091963d1a9f2f0bd361
ms.sourcegitcommit: e10085e60ca3f38029fde229fb093e6bc4a34203
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 02/25/2019
ms.locfileid: "29989690"
---
# <a name="installing-the-custom-learning-solution-webpart"></a><span data-ttu-id="17cc7-103">Установка настраиваемой веб-части решения для обучения</span><span class="sxs-lookup"><span data-stu-id="17cc7-103">Installing the Custom Learning Solution Webpart</span></span>

## <a name="prerequisites-for-a-tenant-wide-installation"></a><span data-ttu-id="17cc7-104">Необходимые условия для установки на уровне клиента</span><span class="sxs-lookup"><span data-stu-id="17cc7-104">Prerequisites for a tenant-wide installation</span></span>

- <span data-ttu-id="17cc7-p101">Чтобы установить настраиваемую веб-часть обучения для всего клиента, необходимо иметь административные разрешения Office 365.  Если у вас нет этих разрешений, вы можете работать с администратором Office 365 или установить веб-часть для отдельного семейства веб-сайтов.</span><span class="sxs-lookup"><span data-stu-id="17cc7-p101">To install the Custom Learning webpart for your entire tenant you will need to have Office 365 Administrative permissions.  If you do not have these permissions you can either work with your Office 365 Administrator or install the webpart for an individual site collection.</span></span>
- <span data-ttu-id="17cc7-107">Для получения веб-части необходимо, чтобы администратор Office 365 выполнил настройку и настроила [Каталог приложений](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/set-up-your-developer-tenant) на уровне клиента или [Каталог приложений для семейства веб-сайтов](https://docs.microsoft.com/en-us/sharepoint/dev/general-development/site-collection-app-catalog).]</span><span class="sxs-lookup"><span data-stu-id="17cc7-107">You or your Office 365 Administrator must have setup and configured a tenant-wide [App Catalog](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/set-up-your-developer-tenant) or a [Site Collection App Catalog](https://docs.microsoft.com/en-us/sharepoint/dev/general-development/site-collection-app-catalog)to receive the webpart.]</span></span>
- <span data-ttu-id="17cc7-p102">Мы поддерживаем только SharePoint Online. Веб-часть не поддерживает установку в локальной версии SharePoint.</span><span class="sxs-lookup"><span data-stu-id="17cc7-p102">We support SharePoint Online only. The web part is not support for installation on any version of SharePoint on premises.</span></span>

## <a name="add-the-custom-learning-webpart-to-your-tenant"></a><span data-ttu-id="17cc7-110">Добавление настраиваемой веб-части обучения в клиент</span><span class="sxs-lookup"><span data-stu-id="17cc7-110">Add the Custom Learning webpart to your tenant</span></span> 

1. <span data-ttu-id="17cc7-p103">Скачайте настраиваемую веб-часть обучения и сохраните ее на локальном диске.  Этот файл называется "MS-Custom-Learning. sppkg".  Не изменяйте имя или суффикс файла.</span><span class="sxs-lookup"><span data-stu-id="17cc7-p103">Download the Custom Learning webpart and save it to your local drive.  This file is named "ms-custom-learning.sppkg".  Do not change the name or suffix of the file.</span></span> 
2. <span data-ttu-id="17cc7-114">Перейдите на [портал администрирования Office 365](https://admin.microsoft.com/AdminPortal/Home#/homepage) для своего клиента.</span><span class="sxs-lookup"><span data-stu-id="17cc7-114">Navigate to the [Office 365 Admin portal](https://admin.microsoft.com/AdminPortal/Home#/homepage) for your tenant</span></span>
3. <span data-ttu-id="17cc7-p104">В области навигации слева выберите пункт центры администрирования SharePoint. Откроется новая вкладка. в центре администрирования SharePoint выберите приложения, Каталог приложений, приложения для SharePoint.</span><span class="sxs-lookup"><span data-stu-id="17cc7-p104">From the left navigation select Admin Centers, SharePoint. This will open in a new tab. , In the SharePoint Admin Center select Apps, App Catalog, Apps for SharePoint</span></span> 
4. <span data-ttu-id="17cc7-117">Выберите отправить веб-часть и выберите загруженный файл MS-Custom-Learning. sppkg</span><span class="sxs-lookup"><span data-stu-id="17cc7-117">Select upload the webpart and choose the "ms-custom-learning.sppkg" file you downloaded</span></span>
5. <span data-ttu-id="17cc7-118">Для этой установки на уровне клиента установите флажок рядом с пунктом "сделать это решение доступным для всех почтовых организаций".</span><span class="sxs-lookup"><span data-stu-id="17cc7-118">For this tenant-wide installation check the box next to "Make this solution available to all sits in the organization."</span></span>  
 
> [!NOTE]
> <span data-ttu-id="17cc7-p105">После установки веб-части ее можно будет найти в коллекции веб-частей в SharePoint Online.  **В коллекции веб-часть называется "обучение Майкрософт"**</span><span class="sxs-lookup"><span data-stu-id="17cc7-p105">Once the webpart is installed you will find it in your webpart gallery in SharePoint Online.  **In the gallery the webpart is named "Microsoft Learning"**</span></span>

![Развертывание решения](media/trustapp_sm.png)


## <a name="add-the-microsoft-learning-webpart-to-a-sharepoint-online-page"></a><span data-ttu-id="17cc7-122">Добавление веб-части "обучение Майкрософт" на страницу SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="17cc7-122">Add the Microsoft Learning webpart to a SharePoint Online Page</span></span>

<span data-ttu-id="17cc7-p106">После установки в клиенте настраиваемого обучения можно добавить веб-часть на страницу SharePoint. Если вы выполняете обучение по Office 365 и Windows 10, вы можете использовать сайт.</span><span class="sxs-lookup"><span data-stu-id="17cc7-p106">After Custom Learning is installed in your tenant you can add the Web part to a SharePoint page. When you do Office 365 and Windows 10 training is available to your site.</span></span>

1. <span data-ttu-id="17cc7-125">Добавьте пользовательскую веб-часть Learning в макет столбца "полная ширина":</span><span class="sxs-lookup"><span data-stu-id="17cc7-125">Add the Custom Learning webpart in a full width column layout:</span></span>

![Макет страницы SharePoint](media/clo365fullcolumnwidth.png)

2. <span data-ttu-id="17cc7-p107">На странице SharePoint выберите Добавить раздел, а затем выберите столбец "полная ширина".  Появится следующее сообщение:</span><span class="sxs-lookup"><span data-stu-id="17cc7-p107">In the SharePoint page, select Add section and then select full width column.  You'll see the following prompt:</span></span>

![Аддвебпарт](media/clo365addfullwidthwebpart.png)

3. <span data-ttu-id="17cc7-p108">Выберите пункт обучение Майкрософт.  Теперь должны отобразиться следующие компоненты:</span><span class="sxs-lookup"><span data-stu-id="17cc7-p108">Select Microsoft Learning.  You should now see the following:</span></span> 

![Настраиваемая веб-часть обучения](media/clo365addwebpart.png)

 <span data-ttu-id="17cc7-133">Теперь вы можете щелкнуть плитку, чтобы просмотреть контент по умолчанию, включенный в решение.</span><span class="sxs-lookup"><span data-stu-id="17cc7-133">You can now click on the tiles to explore the default content included in the solution.</span></span>  

### <a name="next-steps"></a><span data-ttu-id="17cc7-134">Дальнейшие действия</span><span class="sxs-lookup"><span data-stu-id="17cc7-134">Next Steps</span></span>
- <span data-ttu-id="17cc7-135">ИзУчите [контент по умолчанию](webpartcontent.md) , включенный в веб-часть.</span><span class="sxs-lookup"><span data-stu-id="17cc7-135">Explore the [default content](webpartcontent.md) included in the webpart.</span></span>
- <span data-ttu-id="17cc7-136">[Настройка](customization.md) обучающих интерфейсов для Организации.</span><span class="sxs-lookup"><span data-stu-id="17cc7-136">[Customize](customization.md) the training experience for your organization.</span></span>
- <span data-ttu-id="17cc7-137">[Внедрение](driveadoption.md) вашего учебного решения.</span><span class="sxs-lookup"><span data-stu-id="17cc7-137">[Drive adoption](driveadoption.md) of your training solution.</span></span>


# <a name="installing-the-custom-learning-solution-webpart"></a><span data-ttu-id="6217d-101">Установка настраиваемого обучения решения веб-части</span><span class="sxs-lookup"><span data-stu-id="6217d-101">Installing the Custom Learning Solution Webpart</span></span>

## <a name="prerequisites-for-a-tenant-wide-installation"></a><span data-ttu-id="6217d-102">Необходимые условия для установки клиента всей</span><span class="sxs-lookup"><span data-stu-id="6217d-102">Prerequisites for a tenant-wide installation</span></span>

- <span data-ttu-id="6217d-p101">Установка обучения настраиваемые веб-части для всей клиента необходимо иметь права администратора Office 365.  Если эти разрешения можно вместе с администратором Office 365 или установить веб-части для отдельного семейства узлов.</span><span class="sxs-lookup"><span data-stu-id="6217d-p101">To install the Custom Learning webpart for your entire tenant you will need to have Office 365 Administrative permissions.  If you do not have these permissions you can either work with your Office 365 Administrator or install the webpart for an individual site collection.</span></span>
- <span data-ttu-id="6217d-105">Пользователь или администратор Office 365 должны иметь программы установки и настройки клиента всей [Каталога приложений](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/set-up-your-developer-tenant) или [Каталоге приложений семейства сайтов](https://docs.microsoft.com/en-us/sharepoint/dev/general-development/site-collection-app-catalog)для получения веб-части.]</span><span class="sxs-lookup"><span data-stu-id="6217d-105">You or your Office 365 Administrator must have setup and configured a tenant-wide [App Catalog](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/set-up-your-developer-tenant) or a [Site Collection App Catalog](https://docs.microsoft.com/en-us/sharepoint/dev/general-development/site-collection-app-catalog)to receive the webpart.]</span></span>
- <span data-ttu-id="6217d-p102">Мы только поддерживает SharePoint Online. Веб-часть не поддерживается для установки на любой версии SharePoint локально.</span><span class="sxs-lookup"><span data-stu-id="6217d-p102">We support SharePoint Online only. The web part is not support for installation on any version of SharePoint on premises.</span></span>

## <a name="add-the-custom-learning-webpart-to-your-tenant"></a><span data-ttu-id="6217d-108">Добавление обучения настраиваемые веб-части к клиенту</span><span class="sxs-lookup"><span data-stu-id="6217d-108">Add the Custom Learning webpart to your tenant</span></span> 

1. <span data-ttu-id="6217d-p103">Загрузите обучения настраиваемые веб-части и сохраните его на локальный диск.  Этот файл называется «ms-custom-learning.sppkg».  Не изменяйте имя или суффикс файла.</span><span class="sxs-lookup"><span data-stu-id="6217d-p103">Download the Custom Learning webpart and save it to your local drive.  This file is named "ms-custom-learning.sppkg".  Do not change the name or suffix of the file.</span></span> 
2. <span data-ttu-id="6217d-112">Перейдите на [портал администрирования Office 365](https://admin.microsoft.com/AdminPortal/Home#/homepage) для клиента</span><span class="sxs-lookup"><span data-stu-id="6217d-112">Navigate to the [Office 365 Admin portal](https://admin.microsoft.com/AdminPortal/Home#/homepage) for your tenant</span></span>
3. <span data-ttu-id="6217d-p104">В левой панели навигации выберите центры администрирования SharePoint. Откроется в новой вкладке, выберите приложения в центр администрирования SharePoint, каталог приложений, приложений для SharePoint</span><span class="sxs-lookup"><span data-stu-id="6217d-p104">From the left navigation select Admin Centers, SharePoint. This will open in a new tab. , In the SharePoint Admin Center select Apps, App Catalog, Apps for SharePoint</span></span> 
4. <span data-ttu-id="6217d-115">Выбор Отправка веб-части и выберите загруженный файл «ms-custom-learning.sppkg»</span><span class="sxs-lookup"><span data-stu-id="6217d-115">Select upload the webpart and choose the "ms-custom-learning.sppkg" file you downloaded</span></span>
5. <span data-ttu-id="6217d-116">Для установки клиента всей установите флажок рядом с пунктом «Сделать это решение, доступное для всех документа в организации».</span><span class="sxs-lookup"><span data-stu-id="6217d-116">For this tenant-wide installation check the box next to "Make this solution available to all sits in the organization."</span></span>  

![Развертывание решения](media/trustapp_sm.png)


## <a name="add-the-customer-learning-webpart-to-a-sharepoint-online-page"></a><span data-ttu-id="6217d-118">Добавление веб-части клиента обучения на страницу SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="6217d-118">Add the Customer Learning webpart to a SharePoint Online Page</span></span>

<span data-ttu-id="6217d-p105">После установки настраиваемых обучения клиента можно добавить веб-части на страницу SharePoint. В этом случае внезапно обучения Office 365 доступен.</span><span class="sxs-lookup"><span data-stu-id="6217d-p105">After Custom Learning is installed in your tenant you can add the Web part to a SharePoint page. When you do, suddenly Office 365 training is available to you.</span></span> 

1. <span data-ttu-id="6217d-121">Добавьте обучения настраиваемые веб-части в макете полной ширины столбца:</span><span class="sxs-lookup"><span data-stu-id="6217d-121">Add the Custom Learning webpart in a full width column layout:</span></span>

![Макет страницы SharePoint](media/clo365fullcolumnwidth.png)

2. <span data-ttu-id="6217d-p106">На странице SharePoint выберите Добавить раздел, а затем выберите полной ширины столбца.  Вы увидите следующее сообщение:</span><span class="sxs-lookup"><span data-stu-id="6217d-p106">In the SharePoint page, select Add section and then select full width column.  You'll see the following prompt:</span></span>

![AddWebpart](media/clo365addfullwidthwebpart.png)

3. <span data-ttu-id="6217d-p107">Выберите Microsoft Learning.  Должна появиться следующее:</span><span class="sxs-lookup"><span data-stu-id="6217d-p107">Select Microsoft Learning.  You should now see the following:</span></span> 

![Настраиваемые обучения веб-части](media/clo365addwebpart.png)

 <span data-ttu-id="6217d-129">Теперь можно щелкнуть заголовков для изучения содержимого по умолчанию, входящие в состав решения.</span><span class="sxs-lookup"><span data-stu-id="6217d-129">You can now click on the tiles to explore the default content included in the solution.</span></span>  

## <a name="next-steps"></a><span data-ttu-id="6217d-130">Дальнейшие действия</span><span class="sxs-lookup"><span data-stu-id="6217d-130">Next Steps</span></span>
- <span data-ttu-id="6217d-131">Обзор [содержимого по умолчанию](webpartcontent.md) , включенные в веб-части.</span><span class="sxs-lookup"><span data-stu-id="6217d-131">Explore the [default content](webpartcontent.md) included in the webpart.</span></span>
- <span data-ttu-id="6217d-132">[Настройка](customization.md) качества обучения для вашей организации.</span><span class="sxs-lookup"><span data-stu-id="6217d-132">[Customize](customization.md) the training experience for your organization.</span></span>
- <span data-ttu-id="6217d-133">[Внедрения](driveadoption.md) решения для обучения.</span><span class="sxs-lookup"><span data-stu-id="6217d-133">[Drive adoption](driveadoption.md) of your training solution.</span></span>


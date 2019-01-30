# <a name="customize-the-services-and-playlists"></a><span data-ttu-id="16d93-101">Настройка служб и списки</span><span class="sxs-lookup"><span data-stu-id="16d93-101">Customize the Services and Playlists</span></span>

<span data-ttu-id="16d93-p101">По умолчанию на взаимодействие с сайта и веб-части включать контент для всех служб Office 365.  Если только для всех или некоторых из этих служб, доступные в вашей компании можно скорректировать, какой контент доступными для пользователей.  В этой статье мы будет настраивать контент веб-части.</span><span class="sxs-lookup"><span data-stu-id="16d93-p101">By default both the site experience and the webpart include content for all Office 365 services.  If only all or some of these services are available in your company you can adjust what content is available to your users.  In this article we will customize the webpart content.</span></span>  

## <a name="customizing-the-webpart-content"></a><span data-ttu-id="16d93-105">Настройка веб-части содержимого</span><span class="sxs-lookup"><span data-stu-id="16d93-105">Customizing the webpart content</span></span>

<span data-ttu-id="16d93-106">Learning настраиваемые веб-части содержит две основные возможности:</span><span class="sxs-lookup"><span data-stu-id="16d93-106">The Custom Learning webpart provides two key features:</span></span>
- <span data-ttu-id="16d93-107">Показать/скрыть технологий</span><span class="sxs-lookup"><span data-stu-id="16d93-107">Hide/Show Technologies</span></span>
- <span data-ttu-id="16d93-108">Создать список воспроизведения</span><span class="sxs-lookup"><span data-stu-id="16d93-108">Create a Playlist</span></span>

### <a name="hide-or-show-technology-categories"></a><span data-ttu-id="16d93-109">Скрытие или отображение технологии категорий</span><span class="sxs-lookup"><span data-stu-id="16d93-109">Hide or Show Technology Categories</span></span>

<span data-ttu-id="16d93-110">Скрытие и отображение содержимого в веб-части:</span><span class="sxs-lookup"><span data-stu-id="16d93-110">To hide and show content in the Web part:</span></span> 
1.  <span data-ttu-id="16d93-111">Выберите в раскрывающемся меню на веб-части, а затем нажмите кнопку Показать/скрыть технологий</span><span class="sxs-lookup"><span data-stu-id="16d93-111">Click the dropdown menu on the webpart, then click Hide/Show Technologies</span></span>

![Пункт меню](media/clohideshow.png)

2. <span data-ttu-id="16d93-113">Выберите checkox, чтобы скрыть или отобразить технологии и выберите **Применить**.</span><span class="sxs-lookup"><span data-stu-id="16d93-113">Select a checkox to hide or show a technology and select **Apply**.</span></span>

![Параметры технологии](media/clohideshow1.png)

### <a name="create-a-playlist"></a><span data-ttu-id="16d93-115">Создать список воспроизведения</span><span class="sxs-lookup"><span data-stu-id="16d93-115">Create a Playlist</span></span>

<span data-ttu-id="16d93-p102">Список воспроизведения-это compliation «ресурсов». «Актив» — это страницы SharePoint или существующий элемент Microsoft учебные материалы. При создании списка воспроизведения выбрать средства, которые используются вместе для создания план обучения для пользователей.</span><span class="sxs-lookup"><span data-stu-id="16d93-p102">A playlist is a compliation of "assets". An "asset" is a SharePoint page or existing item of Microsoft training content. When you create a playlist you select assets that go together to create a learning path for your user.</span></span>  

<span data-ttu-id="16d93-p103">— Это преимущество Добавление страниц SharePoint, что можно создавать страницы SharePoint с YouTube видео или видео, размещенного в вашей организации. Также можно создавать страницы с формами или другое содержимое Office 365.</span><span class="sxs-lookup"><span data-stu-id="16d93-p103">The benefit of adding SharePoint pages is that you can create SharePoint pages with a YouTube videos or videos hosted in your organization. You can also create pages with Forms or other Office 365 content.</span></span>  

#### <a name="step-1-create-a-sharepoint-page-for-your-playlist"></a><span data-ttu-id="16d93-121">Шаг 1: Создание страницу SharePoint для списка воспроизведения</span><span class="sxs-lookup"><span data-stu-id="16d93-121">Step 1: Create a SharePoint page for your playlist</span></span>
<span data-ttu-id="16d93-p104">В этом примере мы сначала создайте страницу SharePoint, чтобы добавить в список воспроизведения. Мы создадим страницу с YouTube видео веб-части и текст веб-части.  Эти инструкции предполагают, что вы используете службу SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="16d93-p104">In this example, we’ll first create a SharePoint page to add to the playlist. We’ll create a page with a YouTube video web part and Text web part.  These instructions assume you are using the SharePoint Online service.</span></span> 

#### <a name="create-a-new-page"></a><span data-ttu-id="16d93-125">Создание новой страницы</span><span class="sxs-lookup"><span data-stu-id="16d93-125">Create a new page</span></span>
1.  <span data-ttu-id="16d93-126">Выберите параметры меню > контент сайта > страниц сайта > новой > страница сайта.</span><span class="sxs-lookup"><span data-stu-id="16d93-126">Select the Settings menu > Site Contents > Site Pages > New > Site Page.</span></span>
2.  <span data-ttu-id="16d93-127">В области заголовка типа используйте поле Команда групп</span><span class="sxs-lookup"><span data-stu-id="16d93-127">In the title area, type Use the Teams command box</span></span>
3.  <span data-ttu-id="16d93-128">Выберите Добавить новый раздел и выберите два столбца.</span><span class="sxs-lookup"><span data-stu-id="16d93-128">Select the Add a new section, and then select Two Columns.</span></span>

![Добавьте два столбца](media/clo365addtwocolumn.png)

4.  <span data-ttu-id="16d93-130">В левом окне выберите Добавить новый веб-части и выберите Embed.</span><span class="sxs-lookup"><span data-stu-id="16d93-130">In the left-hand box, select Add a new web part, and then select Embed.</span></span> 
5.  <span data-ttu-id="16d93-131">В веб-браузере перейдите на этот URL-адрес https://youtu.be/wYrRCRphrp0 и получить код внедрения для видео.</span><span class="sxs-lookup"><span data-stu-id="16d93-131">In a Web browser, go to this URL https://youtu.be/wYrRCRphrp0 and get the embed code for the video.</span></span> 
6.  <span data-ttu-id="16d93-132">В веб-части SharePoint выберите Добавить внедрить код и вставьте его в поле Embed.</span><span class="sxs-lookup"><span data-stu-id="16d93-132">In the SharePoint Web part, select Add Embed code and then paste it into the Embed box.</span></span> 
7.  <span data-ttu-id="16d93-133">В правом поле выберите Добавить новый веб-части и затем выберите текст.</span><span class="sxs-lookup"><span data-stu-id="16d93-133">In the right-hand box, select Add a new web part, and then select Text.</span></span> 
8.  <span data-ttu-id="16d93-p105">В веб-браузере перейдите на этот URL-адрес: https://support.office.com/en-us/article/13c4e429-7324-4886-b377-5dbed539193b и скопируйте Try его! Инструкции по со страницы и вставьте их в текст веб-части. Страница должна выглядеть следующим образом.</span><span class="sxs-lookup"><span data-stu-id="16d93-p105">In a Web browser, go to this URL: https://support.office.com/en-us/article/13c4e429-7324-4886-b377-5dbed539193b and copy the Try it! Instructions from the page and paste them into the Text Web part. Your page should look like the following.</span></span> 

![Внедрение страницы](media/clo365teamscommandbox.png)

9.  <span data-ttu-id="16d93-138">Нажмите кнопку Опубликовать и затем скопируйте URL-адрес страницы и вставьте его в "Блокнот"</span><span class="sxs-lookup"><span data-stu-id="16d93-138">Click Publish, and then copy the URL of the page and paste it in Notepad</span></span>

#### <a name="step-2-create-the-playlist"></a><span data-ttu-id="16d93-139">Шаг 2: Создание списка воспроизведения</span><span class="sxs-lookup"><span data-stu-id="16d93-139">Step 2: Create the Playlist</span></span>
1.  <span data-ttu-id="16d93-p106">Перейдите к установленному обучения настраиваемые веб-части. Весь сайт сайтами размещены на страницу обучение для Office 365.</span><span class="sxs-lookup"><span data-stu-id="16d93-p106">Navigate to where you have installed the Custom Learning webpart. In the full site experience it is hosted on the Office 365 training page.</span></span> 
2.  <span data-ttu-id="16d93-142">В раскрывающемся меню выберите создать новый список воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="16d93-142">From the dropdown menu select Create New Playlist.</span></span> 

![Создание настраиваемого списка воспроизведения](media/clo365createplaylist.png)

3.  <span data-ttu-id="16d93-144">Введите значения, как показано в следующем примере и выберите команду **Создать**.</span><span class="sxs-lookup"><span data-stu-id="16d93-144">Fill in the values as shown in the example below and select **Create**.</span></span> 

#### <a name="step-3-add-assets-to-the-playlist"></a><span data-ttu-id="16d93-145">Шаг 3: Добавление средств в список воспроизведения</span><span class="sxs-lookup"><span data-stu-id="16d93-145">Step 3: Add assets to the playlist</span></span>
<span data-ttu-id="16d93-146">На этом этапе вы добавите существующие ресурсы от корпорации Майкрософт и страницы SharePoint, которую вы создали в список воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="16d93-146">In this step, you’ll add existing assets from Microsoft and the SharePoint page you created to the playlist.</span></span> 

1.  <span data-ttu-id="16d93-147">Нажмите кнопку меню, а затем нажмите кнопку Добавить существующий активов.</span><span class="sxs-lookup"><span data-stu-id="16d93-147">Click the menu button, then click Add Existing Asset.</span></span>

![Добавьте средств](media/clo365addasset.png)

2.  <span data-ttu-id="16d93-149">Фильтрация на обучение группами Майкрософт > приложений Office 365</span><span class="sxs-lookup"><span data-stu-id="16d93-149">Filter on Office 365 Apps > Microsoft Teams Training</span></span>
3.  <span data-ttu-id="16d93-150">Добавление Добро пожаловать в Microsoft группы, получение ваша группа запущено и работает и запустите чаты и совершать звонки.</span><span class="sxs-lookup"><span data-stu-id="16d93-150">Add Welcome to Microsoft Teams, Get your team up and running, and Start chats and make calls.</span></span>
4.  <span data-ttu-id="16d93-151">Выберите > кнопки меню Создать активов.</span><span class="sxs-lookup"><span data-stu-id="16d93-151">Select the menu button > Create Asset.</span></span>
5.  <span data-ttu-id="16d93-152">Поле Команда групп используется тип в поле Название активов.</span><span class="sxs-lookup"><span data-stu-id="16d93-152">Type Use the Teams command box in the Asset title box.</span></span> 
6.  <span data-ttu-id="16d93-153">Вставьте SharePoint использование команды командной поле URL-адрес страницы копируются в поле содержимого активов.</span><span class="sxs-lookup"><span data-stu-id="16d93-153">Paste the SharePoint Use the Teams command box page URL you copied in the Asset content field.</span></span> 
7.  <span data-ttu-id="16d93-p107">Теперь перейдите обратно в > настраиваемые списки > домашнюю страницу вашего первого дней с группами > используйте поле Команда группами. Страница должна выглядеть следующим образом.</span><span class="sxs-lookup"><span data-stu-id="16d93-p107">Now navigate back to the Home Page > Custom Playlists > Your first days with Teams > Use the Teams command box. Your page should look like the following.</span></span> 

![созданный страницы](media/clo365createplaylist2.png)

<span data-ttu-id="16d93-157">Список воспроизведения с помощью этого контента теперь будут доступны в любом месте установлены / внедренные обучения настраиваемые веб-части.</span><span class="sxs-lookup"><span data-stu-id="16d93-157">Your playlist with this content will now be available anywhere you have installed / embedded the Custom Learning webpart.</span></span> 

#### <a name="things-to-think-about"></a><span data-ttu-id="16d93-158">Вещей для обдумывания</span><span class="sxs-lookup"><span data-stu-id="16d93-158">Things to Think About</span></span>

<span data-ttu-id="16d93-p108">Настраиваемые списки можно использовать для помощи конечных пользователей при vareity задач.  У вас есть время выключить форма запроса?  Форма для запроса оборудования оборудование?  Любые существующие ресурсы обучения можно запрограммировать в качества.</span><span class="sxs-lookup"><span data-stu-id="16d93-p108">Custom playlists can be used to assist your end users in a vareity of tasks.  Do you have a time off request form?  A form to request hardware equipment?  Any existing training assets can be programmed into the experience.</span></span>  

---
author: karuanag
ms.author: karuanag
manager: alexb
title: Настройка и совместное делиться списками воспроизведения
ms.date: 02/10/2019
description: Создание пользовательских списков воспроизведения из существующего контента или новых страниц SharePoint
ms.service: sharepoint-online
audience: itpro
ms.topic: article
ms.openlocfilehash: 31a0e5524181d26f4d62ae7206636c9e553b6f8f
ms.sourcegitcommit: 97e175e5ff5b6a9e0274d5ec9b39fdf7e18eb387
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/25/2021
ms.locfileid: "52000215"
---
# <a name="customize-and-share-playlists"></a><span data-ttu-id="2b7f3-103">Настройка и совместное делиться списками воспроизведения</span><span class="sxs-lookup"><span data-stu-id="2b7f3-103">Customize and share playlists</span></span>

## <a name="create-a-playlist"></a><span data-ttu-id="2b7f3-104">Создание списка воспроизведения</span><span class="sxs-lookup"><span data-stu-id="2b7f3-104">Create a Playlist</span></span>

<span data-ttu-id="2b7f3-105">Список воспроизведения — это соответствие "активам".</span><span class="sxs-lookup"><span data-stu-id="2b7f3-105">A playlist is a compliation of "assets".</span></span> <span data-ttu-id="2b7f3-106">"Актив" — это страница SharePoint или существующий элемент обучающего контента Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-106">An "asset" is a SharePoint page or existing item of Microsoft training content.</span></span> <span data-ttu-id="2b7f3-107">При создании списка воспроизведения вы выбираете ресурсы, которые вместе создают путь к обучению для пользователя.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-107">When you create a playlist you select assets that go together to create a learning path for your user.</span></span>  

<span data-ttu-id="2b7f3-108">Преимущество добавления страниц SharePoint состоит в том, что вы можете создавать страницы SharePoint с помощью видео или видео на YouTube, которые будут организованы в вашей организации.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-108">The benefit of adding SharePoint pages is that you can create SharePoint pages with a YouTube videos or videos hosted in your organization.</span></span> <span data-ttu-id="2b7f3-109">Вы также можете создавать страницы с формами или другим контентом Office 365.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-109">You can also create pages with Forms or other Office 365 content.</span></span>  

#### <a name="step-1-create-a-sharepoint-page-for-your-playlist"></a><span data-ttu-id="2b7f3-110">Шаг 1. Создание страницы SharePoint для списка воспроизведения</span><span class="sxs-lookup"><span data-stu-id="2b7f3-110">Step 1: Create a SharePoint page for your playlist</span></span>
<span data-ttu-id="2b7f3-111">В этом примере сначала создадим страницу SharePoint, которая будет добавлена в список воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-111">In this example, we’ll first create a SharePoint page to add to the playlist.</span></span> <span data-ttu-id="2b7f3-112">Мы создадим страницу с веб-частью видео YouTube и веб-частью Text.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-112">We’ll create a page with a YouTube video web part and Text web part.</span></span>  <span data-ttu-id="2b7f3-113">Эти инструкции предполагают, что вы используете службу SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-113">These instructions assume you are using the SharePoint Online service.</span></span> 

#### <a name="create-a-new-page"></a><span data-ttu-id="2b7f3-114">Создайте новую страницу</span><span class="sxs-lookup"><span data-stu-id="2b7f3-114">Create a new page</span></span>
1.  <span data-ttu-id="2b7f3-115">Выберите меню Параметры > содержимого сайта > страниц сайта > страницу > сайта.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-115">Select the Settings menu > Site Contents > Site Pages > New > Site Page.</span></span>
2.  <span data-ttu-id="2b7f3-116">В области заголовка введите Использование командного окна Teams</span><span class="sxs-lookup"><span data-stu-id="2b7f3-116">In the title area, type Use the Teams command box</span></span>
3.  <span data-ttu-id="2b7f3-117">Выберите добавить новый раздел, а затем выберите два столбца.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-117">Select the Add a new section, and then select Two Columns.</span></span>

![добавление двух столбцов](media/clo365addtwocolumn.png)

4.  <span data-ttu-id="2b7f3-119">В левом окне выберите Добавить новую веб-часть, а затем выберите Embed.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-119">In the left-hand box, select Add a new web part, and then select Embed.</span></span> 
5.  <span data-ttu-id="2b7f3-120">В веб-браузере перейдите к этому URL-адресу https://youtu.be/wYrRCRphrp0 и получите встраив код для видео.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-120">In a Web browser, go to this URL https://youtu.be/wYrRCRphrp0 and get the embed code for the video.</span></span> 
6.  <span data-ttu-id="2b7f3-121">В веб-части SharePoint выберите Добавить код встраить, а затем вложить его в поле Embed.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-121">In the SharePoint Web part, select Add Embed code and then paste it into the Embed box.</span></span> 
7.  <span data-ttu-id="2b7f3-122">В правом окне выберите Добавить новую веб-часть, а затем выберите Текст.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-122">In the right-hand box, select Add a new web part, and then select Text.</span></span> 
8.  <span data-ttu-id="2b7f3-123">В веб-браузере перейдите к этому URL-адресу и https://support.office.com/article/13c4e429-7324-4886-b377-5dbed539193b скопируйте try it!</span><span class="sxs-lookup"><span data-stu-id="2b7f3-123">In a Web browser, go to this URL: https://support.office.com/article/13c4e429-7324-4886-b377-5dbed539193b and copy the Try it!</span></span> <span data-ttu-id="2b7f3-124">Инструкции со страницы и вклейте их в текстовую веб-часть.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-124">Instructions from the page and paste them into the Text Web part.</span></span> <span data-ttu-id="2b7f3-125">Ваша страница должна выглядеть следующим образом.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-125">Your page should look like the following.</span></span> 
<span data-ttu-id="2b7f3-126">![Встраить страницу](media/clo365teamscommandbox.png)</span><span class="sxs-lookup"><span data-stu-id="2b7f3-126">![Embed page](media/clo365teamscommandbox.png)</span></span>
9.  <span data-ttu-id="2b7f3-127">Нажмите **кнопку Опубликовать,** а затем скопируйте URL-адрес страницы и вклеите ее в Блокнот</span><span class="sxs-lookup"><span data-stu-id="2b7f3-127">Click **Publish**, and then copy the URL of the page and paste it in Notepad</span></span>

#### <a name="step-2-create-the-playlist"></a><span data-ttu-id="2b7f3-128">Шаг 2. Создание списка воспроизведения</span><span class="sxs-lookup"><span data-stu-id="2b7f3-128">Step 2: Create the Playlist</span></span>

1. <span data-ttu-id="2b7f3-129">Перейдите на **страницу Администрирование пользовательского** обучения в вашем опыте работы с сайтом.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-129">Navigate to the **Custom Learning Administration** page in your site experience.</span></span>
<span data-ttu-id="2b7f3-130">![Экран, на котором вы выбираете настраиваемый администрирование обучения.](media/custom_admin.png)</span><span class="sxs-lookup"><span data-stu-id="2b7f3-130">![Screen where you select Custom Learning Administration.](media/custom_admin.png)</span></span>
1. <span data-ttu-id="2b7f3-131">**Убедитесь, что выбрана** категория</span><span class="sxs-lookup"><span data-stu-id="2b7f3-131">Make sure **Category** is selected</span></span> 
1. <span data-ttu-id="2b7f3-132">Щелкните категорию, в которой должен появиться новый плейлист</span><span class="sxs-lookup"><span data-stu-id="2b7f3-132">Click on the category where you'd like your new playlist to appear</span></span>
1. <span data-ttu-id="2b7f3-133">Рядом с именем категории щелкните окно плюс символ с параметром ![ Category и выделенным знаком Plus.](media/custom_addplay.png)</span><span class="sxs-lookup"><span data-stu-id="2b7f3-133">Next to the category name, click on the plus symbol ![Window with the Category option and the Plus sign highlighted.](media/custom_addplay.png)</span></span>

1. <span data-ttu-id="2b7f3-134">Заполните значения, как показано в примере ниже, и выберите **Создать**.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-134">Fill in the values as shown in the example below and select **Create**.</span></span> 
<span data-ttu-id="2b7f3-135">![Страница, на которой вы вводите сведения о списке воспроизведения.](media/custom_details.png)</span><span class="sxs-lookup"><span data-stu-id="2b7f3-135">![Page where you enter playlist details.](media/custom_details.png)</span></span>
- <span data-ttu-id="2b7f3-136">**Название** — отображение имени списка воспроизведения</span><span class="sxs-lookup"><span data-stu-id="2b7f3-136">**Title** - Display name of the playlist</span></span>
- <span data-ttu-id="2b7f3-137">**Описание** . Сведения о том, что будет известно</span><span class="sxs-lookup"><span data-stu-id="2b7f3-137">**Description** - Information about what will be learned</span></span>
- <span data-ttu-id="2b7f3-138">**Категория** — предварительно отбираемая в зависимости от первоначального выбора</span><span class="sxs-lookup"><span data-stu-id="2b7f3-138">**Category** - Preselected based on your initial selection</span></span>
- <span data-ttu-id="2b7f3-139">**Sub Category** - Preselected based on your intial selection</span><span class="sxs-lookup"><span data-stu-id="2b7f3-139">**Sub Category** - Preselected based on your intial selection</span></span>
- <span data-ttu-id="2b7f3-140">**Технология** — выберите применимое</span><span class="sxs-lookup"><span data-stu-id="2b7f3-140">**Technology** - Select as applicable</span></span>
- <span data-ttu-id="2b7f3-141">**Уровень** - Beginner, Intermidate или Advanced</span><span class="sxs-lookup"><span data-stu-id="2b7f3-141">**Level** - Beginner, Intermidate or Advanced</span></span>
- <span data-ttu-id="2b7f3-142">**Аудитория** . Это позволяет нацелить контент на основе предварительно определенного списка ролей, предоставляемых Корпорацией Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-142">**Audience** - This allows you to target content based on a pre-defined list of roles provided by Microsoft.</span></span>

6. <span data-ttu-id="2b7f3-143">Щелкните **сохранить деталь**</span><span class="sxs-lookup"><span data-stu-id="2b7f3-143">Click **Save Detail**</span></span>

> [!TIP]
> <span data-ttu-id="2b7f3-144">Вы можете настроить образ значка для списка воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-144">You can customize the icon image for your playlist.</span></span>  <span data-ttu-id="2b7f3-145">Щелкните значок изображения и вставьте URL-адрес ранее загруженного изображения.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-145">Click the image icon and insert an URL of a previously uploaded image.</span></span>  <span data-ttu-id="2b7f3-146">Убедитесь, что изображение находится в коллекции настраиваемого сайта обучения или в другом расположении, чтобы все пользователи получили доступ к файлу.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-146">Make sure the image is located within the Custom Learning site collection or in another location that all users will have access to the file.</span></span>  
<span data-ttu-id="2b7f3-147">![Выберите окно изображения.](media/custom_image.png)</span><span class="sxs-lookup"><span data-stu-id="2b7f3-147">![Choose an image window.](media/custom_image.png)</span></span>

#### <a name="step-3-add-assets-to-the-playlist"></a><span data-ttu-id="2b7f3-148">Шаг 3. Добавление активов в список воспроизведения</span><span class="sxs-lookup"><span data-stu-id="2b7f3-148">Step 3: Add assets to the playlist</span></span>
<span data-ttu-id="2b7f3-149">На этом этапе в список воспроизведения будут добавлены существующие активы из Microsoft и страница SharePoint, созданная вами.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-149">In this step, you’ll add existing assets from Microsoft and the SharePoint page you created to the playlist.</span></span> 

1. <span data-ttu-id="2b7f3-150">После сэкономленных сведений для списка воспроизведения можно использовать поиск существующих активов.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-150">Once you have saved the details for your Playlist you can use the Search for Existing Assets.</span></span>
1. <span data-ttu-id="2b7f3-151">**Введите в любом термине** поиска список предопределяемых активов, доступных из других списков воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-151">**Enter in any search term** to see a list of predefined assets that are available from other playlists.</span></span> <span data-ttu-id="2b7f3-152">**Щелкните имя актива,** чтобы включить его в новый плейлист.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-152">**Click on the name** of an asset to include it in your new playlist.</span></span><br/>
<span data-ttu-id="2b7f3-153">![Страница активов playlist](media/custom_slist.png)</span><span class="sxs-lookup"><span data-stu-id="2b7f3-153">![Playlist assets page](media/custom_slist.png)</span></span>

<span data-ttu-id="2b7f3-154">Вы также можете добавить страницу SharePoint, созданную ранее, или создать ее с нуля в этом опыте.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-154">You can also add the SharePoint page you created earlier or create one from scratch in the experience.</span></span>

1. <span data-ttu-id="2b7f3-155">Щелкните параметр **New Asset** в диалоговом окте "Активы playlist".</span><span class="sxs-lookup"><span data-stu-id="2b7f3-155">Click on the **New Asset** option in the Playlist Assets dialog.</span></span>
1. <span data-ttu-id="2b7f3-156">Дайте вашему активу **название**.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-156">Give your asset a **Title**.</span></span> <span data-ttu-id="2b7f3-157">После вступив, будут отображаться дополнительные параметры.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-157">Once entered, additional options will display.</span></span>
<span data-ttu-id="2b7f3-158">![Форма, в которой вы вводите название и дополнительные сведения.](media/custom_newpage.png)</span><span class="sxs-lookup"><span data-stu-id="2b7f3-158">![Form where you enter your title and additional details.](media/custom_newpage.png)</span></span>
1. <span data-ttu-id="2b7f3-159">Теперь вы можете создать новую страницу активов в SharePoint Online или ввести URL-адрес существующей страницы, чтобы добавить ее в пользовательский список воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-159">You can now create a new asset page in SharePoint Online or enter in the URL of an existing page to add it to your custom playlist.</span></span> 
1. <span data-ttu-id="2b7f3-160">**Поля категории,** **sub Category** и **Technology** будут предварительно заполнены в зависимости от предыдущих выборов для этого списка воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-160">**Category**, **Sub Category** and **Technology** fields will be pre-populated based on your previous selections for this playlist.</span></span>
1. <span data-ttu-id="2b7f3-161">Сделайте соответствующие выборки для уровня и аудитории для этого отдельного актива.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-161">Make the appropriate selections for Level and Audience for this individual asset.</span></span>  
1. <span data-ttu-id="2b7f3-162">Нажмите **кнопку Сохранить актив,** чтобы добавить его в настраиваемый список воспроизведения</span><span class="sxs-lookup"><span data-stu-id="2b7f3-162">Click **Save Asset** to add it to the custom playlist</span></span>
1. <span data-ttu-id="2b7f3-163">Повторите эти действия, поиск или добавление отдельных страниц до завершения списка воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-163">Repeat these steps, either searching or adding individual pages, until your playlist is complete.</span></span> 
1. <span data-ttu-id="2b7f3-164">Нажмите **кнопку Закрыть список воспроизведения,** чтобы сохранить</span><span class="sxs-lookup"><span data-stu-id="2b7f3-164">Click **Close Playlist** to save</span></span>

<span data-ttu-id="2b7f3-165">Ваш плейлист с этим содержимым теперь будет доступен в любом месте, где вы установили или встроите веб-часть настраиваемой учебной системы.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-165">Your playlist with this content will now be available anywhere you have installed / embedded the Custom Learning webpart.</span></span> 

> [!NOTE]
> <span data-ttu-id="2b7f3-166">Если вы допустили ошибку после закрытия списка воспроизведения, вы можете удалить его из категории, щелкнув X рядом с именем плейлиста.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-166">If you make a mistake once you have closed the playlist, you can delete it from the category by clicking the X next to the playlist name.</span></span>  

#### <a name="things-to-think-about"></a><span data-ttu-id="2b7f3-167">Что нужно думать</span><span class="sxs-lookup"><span data-stu-id="2b7f3-167">Things to Think About</span></span>

<span data-ttu-id="2b7f3-168">Настраиваемые списки воспроизведения можно использовать для оказания помощи конечным пользователям в различных задачах.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-168">Custom playlists can be used to assist your end users in a variety of tasks.</span></span>  <span data-ttu-id="2b7f3-169">У вас есть форма запроса на время?</span><span class="sxs-lookup"><span data-stu-id="2b7f3-169">Do you have a time off request form?</span></span>  <span data-ttu-id="2b7f3-170">Форма для запроса оборудования?</span><span class="sxs-lookup"><span data-stu-id="2b7f3-170">A form to request hardware equipment?</span></span>  <span data-ttu-id="2b7f3-171">Все существующие средства подготовки можно запрограммированы на опыт.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-171">Any existing training assets can be programmed into the experience.</span></span>  

## <a name="share-playlists"></a><span data-ttu-id="2b7f3-172">Share Playlists</span><span class="sxs-lookup"><span data-stu-id="2b7f3-172">Share Playlists</span></span>

1. <span data-ttu-id="2b7f3-173">Перейдите к любому списку воспроизведения в веб-части или на сайте.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-173">Navigate to any playlist within the webpart or site experience</span></span>
1. <span data-ttu-id="2b7f3-174">В верхнем левом углу вы увидите три значка</span><span class="sxs-lookup"><span data-stu-id="2b7f3-174">In the upper left hand corner you will see three icons</span></span>
1. <span data-ttu-id="2b7f3-175">Щелкните значок, представляющий ссылку</span><span class="sxs-lookup"><span data-stu-id="2b7f3-175">Click on the icon representing a link</span></span>
1. <span data-ttu-id="2b7f3-176">Скопируйте URL-адрес на экран плейлиста, на ![ котором щелкните Скопируйте рядом с URL-адресом.](media/share.png)</span><span class="sxs-lookup"><span data-stu-id="2b7f3-176">Copy the URL to the playlist ![Screen where you click Copy next to the URL.](media/share.png)</span></span>
<span data-ttu-id="2b7f3-177">Этот URL-адрес теперь можно вставить в навигацию по сайту или использовать в других сообщениях, чтобы вывести сотрудников непосредственно в этот плейлист.</span><span class="sxs-lookup"><span data-stu-id="2b7f3-177">This URL can now be inserted in your site navigation or utilized in other communications to take your employees directly to that playlist.</span></span> 

### <a name="next-steps---drive-adoption"></a><span data-ttu-id="2b7f3-178">Дальнейшие действия — [принятие диска](driveadoption.md)</span><span class="sxs-lookup"><span data-stu-id="2b7f3-178">Next Steps - [Drive Adoption](driveadoption.md)</span></span>

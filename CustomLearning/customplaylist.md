---
author: karuanag
ms.author: karuanag
title: Настройка и общий доступ к спискам воспроизведения
ms.date: 02/10/2019
description: Создание настраиваемых списков воспроизведения из существующего контента или с новых страниц SharePoint
ms.openlocfilehash: d330b6e401c9020eb68877bc8a132350811a2f31
ms.sourcegitcommit: e10085e60ca3f38029fde229fb093e6bc4a34203
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 02/25/2019
ms.locfileid: "29989730"
---
# <a name="customize-and-share-playlists"></a><span data-ttu-id="f3b09-103">Настройка и общий доступ к спискам воспроизведения</span><span class="sxs-lookup"><span data-stu-id="f3b09-103">Customize and Share Playlists</span></span>

## <a name="create-a-playlist"></a><span data-ttu-id="f3b09-104">Создание списка воспроизведения</span><span class="sxs-lookup"><span data-stu-id="f3b09-104">Create a Playlist</span></span>

<span data-ttu-id="f3b09-p101">Список воспроизведения — это "ресурсы". "Актив" — это страница SharePoint или существующий элемент обучающих материалов Майкрософт. При создании списка ресурсов выберите ресурсы, которые объединяются, чтобы создать учебный путь для пользователя.</span><span class="sxs-lookup"><span data-stu-id="f3b09-p101">A playlist is a compliation of "assets". An "asset" is a SharePoint page or existing item of Microsoft training content. When you create a playlist you select assets that go together to create a learning path for your user.</span></span>  

<span data-ttu-id="f3b09-p102">Преимущество добавления страниц SharePoint состоит в том, что вы можете создавать страницы SharePoint с помощью видеороликов YouTube или видеороликов, размещенных в вашей организации. Кроме того, можно создавать страницы с помощью форм или другого контента Office 365.</span><span class="sxs-lookup"><span data-stu-id="f3b09-p102">The benefit of adding SharePoint pages is that you can create SharePoint pages with a YouTube videos or videos hosted in your organization. You can also create pages with Forms or other Office 365 content.</span></span>  

#### <a name="step-1-create-a-sharepoint-page-for-your-playlist"></a><span data-ttu-id="f3b09-110">Шаг 1: Создание страницы SharePoint для списка воспроизведения</span><span class="sxs-lookup"><span data-stu-id="f3b09-110">Step 1: Create a SharePoint page for your playlist</span></span>
<span data-ttu-id="f3b09-p103">В этом примере мы сначала создадим страницу SharePoint для добавления в список воспроизведения. Мы создадим страницу с видеовеб-частью YouTube Video и текстовой веб-частью.  В этих инструкциях предполагается, что вы используете службу SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="f3b09-p103">In this example, we’ll first create a SharePoint page to add to the playlist. We’ll create a page with a YouTube video web part and Text web part.  These instructions assume you are using the SharePoint Online service.</span></span> 

#### <a name="create-a-new-page"></a><span data-ttu-id="f3b09-114">Создание новой страницы</span><span class="sxs-lookup"><span data-stu-id="f3b09-114">Create a new page</span></span>
1.  <span data-ttu-id="f3b09-115">Выберите меню Параметры _Гт_ контент сайта _Гт_ страницы сайта _Гт_ новая страница _Гт_ сайта.</span><span class="sxs-lookup"><span data-stu-id="f3b09-115">Select the Settings menu > Site Contents > Site Pages > New > Site Page.</span></span>
2.  <span data-ttu-id="f3b09-116">В области Заголовок введите команду использовать командное поле Teams</span><span class="sxs-lookup"><span data-stu-id="f3b09-116">In the title area, type Use the Teams command box</span></span>
3.  <span data-ttu-id="f3b09-117">Выберите раздел Добавить новый, а затем выберите два столбца.</span><span class="sxs-lookup"><span data-stu-id="f3b09-117">Select the Add a new section, and then select Two Columns.</span></span>

![Добавление двух столбцов](media/clo365addtwocolumn.png)

4.  <span data-ttu-id="f3b09-119">В левом поле выберите Добавить новую веб-часть, а затем нажмите кнопку внедрить.</span><span class="sxs-lookup"><span data-stu-id="f3b09-119">In the left-hand box, select Add a new web part, and then select Embed.</span></span> 
5.  <span data-ttu-id="f3b09-120">В веб-браузере перейдите по этому URL- https://youtu.be/wYrRCRphrp0 адресу и получите код внедрения для видеоролика.</span><span class="sxs-lookup"><span data-stu-id="f3b09-120">In a Web browser, go to this URL https://youtu.be/wYrRCRphrp0 and get the embed code for the video.</span></span> 
6.  <span data-ttu-id="f3b09-121">В веб-части SharePoint выберите добавить код внедрения и вставьте его в поле внедрить.</span><span class="sxs-lookup"><span data-stu-id="f3b09-121">In the SharePoint Web part, select Add Embed code and then paste it into the Embed box.</span></span> 
7.  <span data-ttu-id="f3b09-122">В правом поле выберите Добавить новую веб-часть, а затем выберите текст.</span><span class="sxs-lookup"><span data-stu-id="f3b09-122">In the right-hand box, select Add a new web part, and then select Text.</span></span> 
8.  <span data-ttu-id="f3b09-p104">В веб-браузере перейдите по указанному ниже https://support.office.com/en-us/article/13c4e429-7324-4886-b377-5dbed539193b URL-адресу и скопируйте его в try! Инструкции со страницы и вставьте их в текстовую веб-часть. Страница должна выглядеть так, как показано ниже.</span><span class="sxs-lookup"><span data-stu-id="f3b09-p104">In a Web browser, go to this URL: https://support.office.com/en-us/article/13c4e429-7324-4886-b377-5dbed539193b and copy the Try it! Instructions from the page and paste them into the Text Web part. Your page should look like the following.</span></span> 

![Страница внедрения](media/clo365teamscommandbox.png)

9.  <span data-ttu-id="f3b09-127">Нажмите кнопку **опубликовать**, а затем СКОПИРУЙТЕ URL-адрес страницы и вставьте его в блокноте.</span><span class="sxs-lookup"><span data-stu-id="f3b09-127">Click **Publish**, and then copy the URL of the page and paste it in Notepad</span></span>

#### <a name="step-2-create-the-playlist"></a><span data-ttu-id="f3b09-128">Шаг 2: Создание списка воспроизведения</span><span class="sxs-lookup"><span data-stu-id="f3b09-128">Step 2: Create the Playlist</span></span>

1. <span data-ttu-id="f3b09-p105">Перейдите на страницу **настраиваемОго администрирования обучения** в интерфейсе сайта. ![кустом_админ. png](media/custom_admin.png)</span><span class="sxs-lookup"><span data-stu-id="f3b09-p105">Navigate to the **Custom Learning Administration** page in your site experience. ![custom_admin.png](media/custom_admin.png)</span></span>
1. <span data-ttu-id="f3b09-131">Убедитесь, что выбран пункт **Категория**</span><span class="sxs-lookup"><span data-stu-id="f3b09-131">Make sure **Category** is selected</span></span> 
1. <span data-ttu-id="f3b09-132">Щелкните категорию, в которой будет отображаться новый список воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="f3b09-132">Click on the category where you'd like your new playlist to appear</span></span>
1. <span data-ttu-id="f3b09-133">Рядом с именем категории щелкните символ !["плюс" кустом_аддплай. png](media/custom_addplay.png)</span><span class="sxs-lookup"><span data-stu-id="f3b09-133">Next to the category name, click on the plus symbol ![custom_addplay.png](media/custom_addplay.png)</span></span>

1. <span data-ttu-id="f3b09-p106">ЗаПолните значения, как показано в примере ниже, и выберите **создать**. ![кустом_детаилс. png](media/custom_details.png)</span><span class="sxs-lookup"><span data-stu-id="f3b09-p106">Fill in the values as shown in the example below and select **Create**. ![custom_details.png](media/custom_details.png)</span></span>
- <span data-ttu-id="f3b09-136">**Заголовок** — отображаемое имя списка воспроизведения</span><span class="sxs-lookup"><span data-stu-id="f3b09-136">**Title** - Display name of the playlist</span></span>
- <span data-ttu-id="f3b09-137">**Description (описание** ) — сведения о том, что будет изучено</span><span class="sxs-lookup"><span data-stu-id="f3b09-137">**Description** - Information about what will be learned</span></span>
- <span data-ttu-id="f3b09-138">**Категория** — предварительно выбрано в зависимости от первоначального выбора</span><span class="sxs-lookup"><span data-stu-id="f3b09-138">**Category** - Preselected based on your initial selection</span></span>
- <span data-ttu-id="f3b09-139">\*\*\*\* ПодвыбранНая Подкатегория — предварительно выбрана в зависимости от выбранного интиал</span><span class="sxs-lookup"><span data-stu-id="f3b09-139">**Sub Category** - Preselected based on your intial selection</span></span>
- <span data-ttu-id="f3b09-140">**Технология** — выберите в качестве применимым</span><span class="sxs-lookup"><span data-stu-id="f3b09-140">**Technology** - Select as applicable</span></span>
- <span data-ttu-id="f3b09-141">**Уровень** — новичок, Интермидате или Advanced</span><span class="sxs-lookup"><span data-stu-id="f3b09-141">**Level** - Beginner, Intermidate or Advanced</span></span>
- <span data-ttu-id="f3b09-142">**Аудитория** — это позволяет запланировать контент, основанный на предварительно определенном списке ролей, предоставляемых корпорацией Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="f3b09-142">**Audience** - This allows you to target content based on a pre-defined list of roles provided by Microsoft.</span></span>

6. <span data-ttu-id="f3b09-143">Нажмите кнопку **сохранить сведения**</span><span class="sxs-lookup"><span data-stu-id="f3b09-143">Click **Save Detail**</span></span>

> [!TIP]
> <span data-ttu-id="f3b09-p107">Вы можете настроить изображение значка для списка воспроизведения.  Щелкните значок изображения и вставьте URL-адрес ранее загруженного изображения.  Убедитесь, что изображение находится в пользовательском семействе веб-сайтов обучения или в другом расположении, доступном для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="f3b09-p107">You can customize the icon image for your playlist.  Click the image icon and insert an URL of a previously uploaded image.  Make sure the image is located within the Custom Learning site collection or in another location that all users will have access to the file.</span></span>  
<span data-ttu-id="f3b09-147">![кустом_имаже. png](media/custom_image.png)</span><span class="sxs-lookup"><span data-stu-id="f3b09-147">![custom_image.png](media/custom_image.png)</span></span>

#### <a name="step-3-add-assets-to-the-playlist"></a><span data-ttu-id="f3b09-148">Шаг 3: Добавление ресурсов в список воспроизведения</span><span class="sxs-lookup"><span data-stu-id="f3b09-148">Step 3: Add assets to the playlist</span></span>
<span data-ttu-id="f3b09-149">На этом этапе вы добавите существующие ресурсы Майкрософт и страницу SharePoint, которую вы создали в списке воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="f3b09-149">In this step, you’ll add existing assets from Microsoft and the SharePoint page you created to the playlist.</span></span> 

1. <span data-ttu-id="f3b09-150">После сохранения сведений для списка воспроизведения можно использовать поиск существующих ресурсов.</span><span class="sxs-lookup"><span data-stu-id="f3b09-150">Once you have saved the details for your Playlist you can use the Search for Existing Assets.</span></span>
1. <span data-ttu-id="f3b09-p108">**Введите в любом** поисковом поле, чтобы просмотреть список предварительно определенных ресурсов, доступных из других списков воспроизведения. **Щелкните имя** актива, чтобы включить его в новый список воспроизведения. ![кустом_слист. png](media/custom_slist.png)</span><span class="sxs-lookup"><span data-stu-id="f3b09-p108">**Enter in any search term** to see a list of predefined assets that are available from other playlists. **Click on the name** of an asset to include it in your new playlist. ![custom_slist.png](media/custom_slist.png)</span></span>

<span data-ttu-id="f3b09-154">Вы также можете добавить созданную ранее страницу SharePoint или создать ее с нуля.</span><span class="sxs-lookup"><span data-stu-id="f3b09-154">You can also add the SharePoint page you created earlier or create one from scratch in the experience.</span></span>

1. <span data-ttu-id="f3b09-155">Выберите **новый ресурс** в диалоговом окне ресурсы списка воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="f3b09-155">Click on the **New Asset** option in the Playlist Assets dialog</span></span>
1. <span data-ttu-id="f3b09-p109">Дайте своему ресурсу **название**. После ввода дополнительные параметры будут отображать ![кустом_невпаже. png](media/custom_newpage.png)</span><span class="sxs-lookup"><span data-stu-id="f3b09-p109">Give your asset a **Title**. Once entered, additional options will display ![custom_newpage.png](media/custom_newpage.png)</span></span>
1. <span data-ttu-id="f3b09-158">Теперь вы можете создать новую страницу актива в SharePoint Online или ввести URL-адрес существующей страницы, чтобы добавить ее в пользовательский список воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="f3b09-158">You can now create a new asset page in SharePoint Online or enter in the URL of an existing page to add it to your custom playlist.</span></span> 
1. <span data-ttu-id="f3b09-159">Поля **Category**, **Sub Category** и **Technology** будут предварительно заполнены в соответствии с предыдущими параметрами этого списка.</span><span class="sxs-lookup"><span data-stu-id="f3b09-159">**Category**, **Sub Category** and **Technology** fields will be pre-populated based on your previous selections for this playlist.</span></span>
1. <span data-ttu-id="f3b09-160">Сделайте соответствующий выбор для уровня и аудитории для отдельного ресурса.</span><span class="sxs-lookup"><span data-stu-id="f3b09-160">Make the appropriate selections for Level and Audience for this individual asset.</span></span>  
1. <span data-ttu-id="f3b09-161">Нажмите кнопку **сохранить ресурс** , чтобы добавить его в настраиваемый список воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="f3b09-161">Click **Save Asset** to add it to the custom playlist</span></span>
1. <span data-ttu-id="f3b09-162">Повторите эти действия, как поиск, так и Добавление отдельных страниц до завершения списка воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="f3b09-162">Repeat these steps, either searching or adding individual pages, until your playlist is complete.</span></span> 
1. <span data-ttu-id="f3b09-163">Нажмите кнопку **Закрыть список воспроизведения** , чтобы сохранить</span><span class="sxs-lookup"><span data-stu-id="f3b09-163">Click **Close Playlist** to save</span></span>

<span data-ttu-id="f3b09-164">Теперь список воспроизведения с этим содержимым будет доступен в любой точке, где установлена или встроена пользовательская веб-часть Learning.</span><span class="sxs-lookup"><span data-stu-id="f3b09-164">Your playlist with this content will now be available anywhere you have installed / embedded the Custom Learning webpart.</span></span> 

> [!NOTE]
> <span data-ttu-id="f3b09-165">Если вы закрыли список воспроизведения, вы можете удалить его из категории, щелкнув значок X рядом с именем списка воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="f3b09-165">If you make a mistake once you have closed the playlist, you can delete it from the category by clicking the X next to the playlist name.</span></span>  

#### <a name="things-to-think-about"></a><span data-ttu-id="f3b09-166">Вопросы, которые следует учитывать</span><span class="sxs-lookup"><span data-stu-id="f3b09-166">Things to Think About</span></span>

<span data-ttu-id="f3b09-p110">Настраиваемые списки воспроизведения можно использовать, чтобы помочь конечным пользователям выполнять различные задачи.  У вас есть форма запроса времени отсутствия?  Форма для запроса аппаратного оборудования?  Все имеющиеся учебные ресурсы могут программироваться в интерфейсе.</span><span class="sxs-lookup"><span data-stu-id="f3b09-p110">Custom playlists can be used to assist your end users in a variety of tasks.  Do you have a time off request form?  A form to request hardware equipment?  Any existing training assets can be programmed into the experience.</span></span>  

## <a name="share-playlists"></a><span data-ttu-id="f3b09-171">Общий доступ к спискам воспроизведения</span><span class="sxs-lookup"><span data-stu-id="f3b09-171">Share Playlists</span></span>

1. <span data-ttu-id="f3b09-172">Переход к любому списку воспроизведения в веб-части или интерфейсе сайта</span><span class="sxs-lookup"><span data-stu-id="f3b09-172">Navigate to any playlist within the webpart or site experience</span></span>
1. <span data-ttu-id="f3b09-173">В верхнем левом углу отображаются три значка.</span><span class="sxs-lookup"><span data-stu-id="f3b09-173">In the upper left hand corner you will see three icons</span></span>
1. <span data-ttu-id="f3b09-174">Щелкните значок, представляющий ссылку</span><span class="sxs-lookup"><span data-stu-id="f3b09-174">Click on the icon representing a link</span></span>
1. <span data-ttu-id="f3b09-175">Копирование URL-адреса в список воспроизведения</span><span class="sxs-lookup"><span data-stu-id="f3b09-175">Copy the URL to the playlist</span></span>

<span data-ttu-id="f3b09-176">![файл Share.](media/share.png) PNG теперь этот URL-адрес можно вставить в навигацию по сайту или использовать в других сообщениях, чтобы перевести сотрудников прямо в этот список.</span><span class="sxs-lookup"><span data-stu-id="f3b09-176">![share.png](media/share.png) This URL can now be inserted in your site navigation or utilized in other communications to take your employees directly to that playlist.</span></span> 

### <a name="next-steps---drive-adoptiondriveadoptionmd"></a><span data-ttu-id="f3b09-177">Дальнейшие действия — [внедрение диска](driveadoption.md)</span><span class="sxs-lookup"><span data-stu-id="f3b09-177">Next Steps - [Drive Adoption](driveadoption.md)</span></span>

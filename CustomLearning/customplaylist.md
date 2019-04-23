---
author: karuanag
ms.author: karuanag
title: Настройка и общий доступ к спискам воспроизведения
ms.date: 02/10/2019
description: Создание настраиваемых списков воспроизведения из существующего контента или с новых страниц SharePoint
ms.openlocfilehash: d330b6e401c9020eb68877bc8a132350811a2f31
ms.sourcegitcommit: 775d6807291ab263eea5ec649d9aaf1933fb41ca
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/23/2019
ms.locfileid: "32056437"
---
# <a name="customize-and-share-playlists"></a><span data-ttu-id="dccef-103">Настройка и общий доступ к спискам воспроизведения</span><span class="sxs-lookup"><span data-stu-id="dccef-103">Customize and Share Playlists</span></span>

## <a name="create-a-playlist"></a><span data-ttu-id="dccef-104">Создание списка воспроизведения</span><span class="sxs-lookup"><span data-stu-id="dccef-104">Create a Playlist</span></span>

<span data-ttu-id="dccef-105">Список воспроизведения — это "ресурсы".</span><span class="sxs-lookup"><span data-stu-id="dccef-105">A playlist is a compliation of "assets".</span></span> <span data-ttu-id="dccef-106">"Актив" — это страница SharePoint или существующий элемент обучающих материалов Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="dccef-106">An "asset" is a SharePoint page or existing item of Microsoft training content.</span></span> <span data-ttu-id="dccef-107">При создании списка ресурсов выберите ресурсы, которые объединяются, чтобы создать учебный путь для пользователя.</span><span class="sxs-lookup"><span data-stu-id="dccef-107">When you create a playlist you select assets that go together to create a learning path for your user.</span></span>  

<span data-ttu-id="dccef-108">Преимущество добавления страниц SharePoint состоит в том, что вы можете создавать страницы SharePoint с помощью видеороликов YouTube или видеороликов, размещенных в вашей организации.</span><span class="sxs-lookup"><span data-stu-id="dccef-108">The benefit of adding SharePoint pages is that you can create SharePoint pages with a YouTube videos or videos hosted in your organization.</span></span> <span data-ttu-id="dccef-109">Кроме того, можно создавать страницы с помощью форм или другого контента Office 365.</span><span class="sxs-lookup"><span data-stu-id="dccef-109">You can also create pages with Forms or other Office 365 content.</span></span>  

#### <a name="step-1-create-a-sharepoint-page-for-your-playlist"></a><span data-ttu-id="dccef-110">Шаг 1: Создание страницы SharePoint для списка воспроизведения</span><span class="sxs-lookup"><span data-stu-id="dccef-110">Step 1: Create a SharePoint page for your playlist</span></span>
<span data-ttu-id="dccef-111">В этом примере мы сначала создадим страницу SharePoint для добавления в список воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="dccef-111">In this example, we’ll first create a SharePoint page to add to the playlist.</span></span> <span data-ttu-id="dccef-112">Мы создадим страницу с видеовеб-частью YouTube Video и текстовой веб-частью.</span><span class="sxs-lookup"><span data-stu-id="dccef-112">We’ll create a page with a YouTube video web part and Text web part.</span></span>  <span data-ttu-id="dccef-113">В этих инструкциях предполагается, что вы используете службу SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="dccef-113">These instructions assume you are using the SharePoint Online service.</span></span> 

#### <a name="create-a-new-page"></a><span data-ttu-id="dccef-114">Создайте новую страницу</span><span class="sxs-lookup"><span data-stu-id="dccef-114">Create a new page</span></span>
1.  <span data-ttu-id="dccef-115">Выберите меню Параметры _Гт_ контент сайта _Гт_ страницы сайта _Гт_ новая страница _Гт_ сайта.</span><span class="sxs-lookup"><span data-stu-id="dccef-115">Select the Settings menu > Site Contents > Site Pages > New > Site Page.</span></span>
2.  <span data-ttu-id="dccef-116">В области Заголовок введите команду использовать командное поле Teams</span><span class="sxs-lookup"><span data-stu-id="dccef-116">In the title area, type Use the Teams command box</span></span>
3.  <span data-ttu-id="dccef-117">Выберите раздел Добавить новый, а затем выберите два столбца.</span><span class="sxs-lookup"><span data-stu-id="dccef-117">Select the Add a new section, and then select Two Columns.</span></span>

![Добавление двух столбцов](media/clo365addtwocolumn.png)

4.  <span data-ttu-id="dccef-119">В левом поле выберите Добавить новую веб-часть, а затем нажмите кнопку внедрить.</span><span class="sxs-lookup"><span data-stu-id="dccef-119">In the left-hand box, select Add a new web part, and then select Embed.</span></span> 
5.  <span data-ttu-id="dccef-120">В веб-браузере перейдите по этому URL- https://youtu.be/wYrRCRphrp0 адресу и получите код внедрения для видеоролика.</span><span class="sxs-lookup"><span data-stu-id="dccef-120">In a Web browser, go to this URL https://youtu.be/wYrRCRphrp0 and get the embed code for the video.</span></span> 
6.  <span data-ttu-id="dccef-121">В веб-части SharePoint выберите добавить код внедрения и вставьте его в поле внедрить.</span><span class="sxs-lookup"><span data-stu-id="dccef-121">In the SharePoint Web part, select Add Embed code and then paste it into the Embed box.</span></span> 
7.  <span data-ttu-id="dccef-122">В правом поле выберите Добавить новую веб-часть, а затем выберите текст.</span><span class="sxs-lookup"><span data-stu-id="dccef-122">In the right-hand box, select Add a new web part, and then select Text.</span></span> 
8.  <span data-ttu-id="dccef-123">В веб-браузере перейдите по указанному ниже https://support.office.com/en-us/article/13c4e429-7324-4886-b377-5dbed539193b URL-адресу и скопируйте его в try!</span><span class="sxs-lookup"><span data-stu-id="dccef-123">In a Web browser, go to this URL: https://support.office.com/en-us/article/13c4e429-7324-4886-b377-5dbed539193b and copy the Try it!</span></span> <span data-ttu-id="dccef-124">Инструкции со страницы и вставьте их в текстовую веб-часть.</span><span class="sxs-lookup"><span data-stu-id="dccef-124">Instructions from the page and paste them into the Text Web part.</span></span> <span data-ttu-id="dccef-125">Страница должна выглядеть так, как показано ниже.</span><span class="sxs-lookup"><span data-stu-id="dccef-125">Your page should look like the following.</span></span> 

![Страница внедрения](media/clo365teamscommandbox.png)

9.  <span data-ttu-id="dccef-127">Нажмите кнопку **опубликовать**, а затем СКОПИРУЙТЕ URL-адрес страницы и вставьте его в блокноте.</span><span class="sxs-lookup"><span data-stu-id="dccef-127">Click **Publish**, and then copy the URL of the page and paste it in Notepad</span></span>

#### <a name="step-2-create-the-playlist"></a><span data-ttu-id="dccef-128">Шаг 2: Создание списка воспроизведения</span><span class="sxs-lookup"><span data-stu-id="dccef-128">Step 2: Create the Playlist</span></span>

1. <span data-ttu-id="dccef-129">Перейдите на страницу **настраиваемОго администрирования обучения** в интерфейсе сайта.</span><span class="sxs-lookup"><span data-stu-id="dccef-129">Navigate to the **Custom Learning Administration** page in your site experience.</span></span>
<span data-ttu-id="dccef-130">![кустом_админ. png](media/custom_admin.png)</span><span class="sxs-lookup"><span data-stu-id="dccef-130">![custom_admin.png](media/custom_admin.png)</span></span>
1. <span data-ttu-id="dccef-131">Убедитесь, что выбран пункт **Категория**</span><span class="sxs-lookup"><span data-stu-id="dccef-131">Make sure **Category** is selected</span></span> 
1. <span data-ttu-id="dccef-132">Щелкните категорию, в которой будет отображаться новый список воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="dccef-132">Click on the category where you'd like your new playlist to appear</span></span>
1. <span data-ttu-id="dccef-133">Рядом с именем категории щелкните символ !["плюс" кустом_аддплай. png](media/custom_addplay.png)</span><span class="sxs-lookup"><span data-stu-id="dccef-133">Next to the category name, click on the plus symbol ![custom_addplay.png](media/custom_addplay.png)</span></span>

1. <span data-ttu-id="dccef-134">ЗаПолните значения, как показано в примере ниже, и выберите **создать**.</span><span class="sxs-lookup"><span data-stu-id="dccef-134">Fill in the values as shown in the example below and select **Create**.</span></span> 
<span data-ttu-id="dccef-135">![кустом_детаилс. png](media/custom_details.png)</span><span class="sxs-lookup"><span data-stu-id="dccef-135">![custom_details.png](media/custom_details.png)</span></span>
- <span data-ttu-id="dccef-136">**Заголовок** — отображаемое имя списка воспроизведения</span><span class="sxs-lookup"><span data-stu-id="dccef-136">**Title** - Display name of the playlist</span></span>
- <span data-ttu-id="dccef-137">**Description (описание** ) — сведения о том, что будет изучено</span><span class="sxs-lookup"><span data-stu-id="dccef-137">**Description** - Information about what will be learned</span></span>
- <span data-ttu-id="dccef-138">**Категория** — предварительно выбрано в зависимости от первоначального выбора</span><span class="sxs-lookup"><span data-stu-id="dccef-138">**Category** - Preselected based on your initial selection</span></span>
- <span data-ttu-id="dccef-139">\*\*\*\* ПодвыбранНая Подкатегория — предварительно выбрана в зависимости от выбранного интиал</span><span class="sxs-lookup"><span data-stu-id="dccef-139">**Sub Category** - Preselected based on your intial selection</span></span>
- <span data-ttu-id="dccef-140">**Технология** — выберите в качестве применимым</span><span class="sxs-lookup"><span data-stu-id="dccef-140">**Technology** - Select as applicable</span></span>
- <span data-ttu-id="dccef-141">**Уровень** — новичок, Интермидате или Advanced</span><span class="sxs-lookup"><span data-stu-id="dccef-141">**Level** - Beginner, Intermidate or Advanced</span></span>
- <span data-ttu-id="dccef-142">**Аудитория** — это позволяет запланировать контент, основанный на предварительно определенном списке ролей, предоставляемых корпорацией Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="dccef-142">**Audience** - This allows you to target content based on a pre-defined list of roles provided by Microsoft.</span></span>

6. <span data-ttu-id="dccef-143">Нажмите кнопку **сохранить сведения**</span><span class="sxs-lookup"><span data-stu-id="dccef-143">Click **Save Detail**</span></span>

> [!TIP]
> <span data-ttu-id="dccef-144">Вы можете настроить изображение значка для списка воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="dccef-144">You can customize the icon image for your playlist.</span></span>  <span data-ttu-id="dccef-145">Щелкните значок изображения и вставьте URL-адрес ранее загруженного изображения.</span><span class="sxs-lookup"><span data-stu-id="dccef-145">Click the image icon and insert an URL of a previously uploaded image.</span></span>  <span data-ttu-id="dccef-146">Убедитесь, что изображение находится в пользовательском семействе веб-сайтов обучения или в другом расположении, доступном для всех пользователей.</span><span class="sxs-lookup"><span data-stu-id="dccef-146">Make sure the image is located within the Custom Learning site collection or in another location that all users will have access to the file.</span></span>  
<span data-ttu-id="dccef-147">![кустом_имаже. png](media/custom_image.png)</span><span class="sxs-lookup"><span data-stu-id="dccef-147">![custom_image.png](media/custom_image.png)</span></span>

#### <a name="step-3-add-assets-to-the-playlist"></a><span data-ttu-id="dccef-148">Шаг 3: Добавление ресурсов в список воспроизведения</span><span class="sxs-lookup"><span data-stu-id="dccef-148">Step 3: Add assets to the playlist</span></span>
<span data-ttu-id="dccef-149">На этом этапе вы добавите существующие ресурсы Майкрософт и страницу SharePoint, которую вы создали в списке воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="dccef-149">In this step, you’ll add existing assets from Microsoft and the SharePoint page you created to the playlist.</span></span> 

1. <span data-ttu-id="dccef-150">После сохранения сведений для списка воспроизведения можно использовать поиск существующих ресурсов.</span><span class="sxs-lookup"><span data-stu-id="dccef-150">Once you have saved the details for your Playlist you can use the Search for Existing Assets.</span></span>
1. <span data-ttu-id="dccef-151">**Введите в любом** поисковом поле, чтобы просмотреть список предварительно определенных ресурсов, доступных из других списков воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="dccef-151">**Enter in any search term** to see a list of predefined assets that are available from other playlists.</span></span> <span data-ttu-id="dccef-152">**Щелкните имя** актива, чтобы включить его в новый список воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="dccef-152">**Click on the name** of an asset to include it in your new playlist.</span></span>
<span data-ttu-id="dccef-153">![кустом_слист. png](media/custom_slist.png)</span><span class="sxs-lookup"><span data-stu-id="dccef-153">![custom_slist.png](media/custom_slist.png)</span></span>

<span data-ttu-id="dccef-154">Вы также можете добавить созданную ранее страницу SharePoint или создать ее с нуля.</span><span class="sxs-lookup"><span data-stu-id="dccef-154">You can also add the SharePoint page you created earlier or create one from scratch in the experience.</span></span>

1. <span data-ttu-id="dccef-155">Выберите **новый ресурс** в диалоговом окне ресурсы списка воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="dccef-155">Click on the **New Asset** option in the Playlist Assets dialog</span></span>
1. <span data-ttu-id="dccef-156">Дайте своему ресурсу **название**.</span><span class="sxs-lookup"><span data-stu-id="dccef-156">Give your asset a **Title**.</span></span> <span data-ttu-id="dccef-157">После ввода дополнительные параметры будут отображать ![кустом_невпаже. png](media/custom_newpage.png)</span><span class="sxs-lookup"><span data-stu-id="dccef-157">Once entered, additional options will display ![custom_newpage.png](media/custom_newpage.png)</span></span>
1. <span data-ttu-id="dccef-158">Теперь вы можете создать новую страницу актива в SharePoint Online или ввести URL-адрес существующей страницы, чтобы добавить ее в пользовательский список воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="dccef-158">You can now create a new asset page in SharePoint Online or enter in the URL of an existing page to add it to your custom playlist.</span></span> 
1. <span data-ttu-id="dccef-159">Поля **Category**, **Sub Category** и **Technology** будут предварительно заполнены в соответствии с предыдущими параметрами этого списка.</span><span class="sxs-lookup"><span data-stu-id="dccef-159">**Category**, **Sub Category** and **Technology** fields will be pre-populated based on your previous selections for this playlist.</span></span>
1. <span data-ttu-id="dccef-160">Сделайте соответствующий выбор для уровня и аудитории для отдельного ресурса.</span><span class="sxs-lookup"><span data-stu-id="dccef-160">Make the appropriate selections for Level and Audience for this individual asset.</span></span>  
1. <span data-ttu-id="dccef-161">Нажмите кнопку **сохранить ресурс** , чтобы добавить его в настраиваемый список воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="dccef-161">Click **Save Asset** to add it to the custom playlist</span></span>
1. <span data-ttu-id="dccef-162">Повторите эти действия, как поиск, так и Добавление отдельных страниц до завершения списка воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="dccef-162">Repeat these steps, either searching or adding individual pages, until your playlist is complete.</span></span> 
1. <span data-ttu-id="dccef-163">Нажмите кнопку **Закрыть список воспроизведения** , чтобы сохранить</span><span class="sxs-lookup"><span data-stu-id="dccef-163">Click **Close Playlist** to save</span></span>

<span data-ttu-id="dccef-164">Теперь список воспроизведения с этим содержимым будет доступен в любой точке, где установлена или встроена пользовательская веб-часть Learning.</span><span class="sxs-lookup"><span data-stu-id="dccef-164">Your playlist with this content will now be available anywhere you have installed / embedded the Custom Learning webpart.</span></span> 

> [!NOTE]
> <span data-ttu-id="dccef-165">Если вы закрыли список воспроизведения, вы можете удалить его из категории, щелкнув значок X рядом с именем списка воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="dccef-165">If you make a mistake once you have closed the playlist, you can delete it from the category by clicking the X next to the playlist name.</span></span>  

#### <a name="things-to-think-about"></a><span data-ttu-id="dccef-166">Вопросы, которые следует учитывать</span><span class="sxs-lookup"><span data-stu-id="dccef-166">Things to Think About</span></span>

<span data-ttu-id="dccef-167">Настраиваемые списки воспроизведения можно использовать, чтобы помочь конечным пользователям выполнять различные задачи.</span><span class="sxs-lookup"><span data-stu-id="dccef-167">Custom playlists can be used to assist your end users in a variety of tasks.</span></span>  <span data-ttu-id="dccef-168">У вас есть форма запроса времени отсутствия?</span><span class="sxs-lookup"><span data-stu-id="dccef-168">Do you have a time off request form?</span></span>  <span data-ttu-id="dccef-169">Форма для запроса аппаратного оборудования?</span><span class="sxs-lookup"><span data-stu-id="dccef-169">A form to request hardware equipment?</span></span>  <span data-ttu-id="dccef-170">Все имеющиеся учебные ресурсы могут программироваться в интерфейсе.</span><span class="sxs-lookup"><span data-stu-id="dccef-170">Any existing training assets can be programmed into the experience.</span></span>  

## <a name="share-playlists"></a><span data-ttu-id="dccef-171">Общий доступ к спискам воспроизведения</span><span class="sxs-lookup"><span data-stu-id="dccef-171">Share Playlists</span></span>

1. <span data-ttu-id="dccef-172">Переход к любому списку воспроизведения в веб-части или интерфейсе сайта</span><span class="sxs-lookup"><span data-stu-id="dccef-172">Navigate to any playlist within the webpart or site experience</span></span>
1. <span data-ttu-id="dccef-173">В верхнем левом углу отображаются три значка.</span><span class="sxs-lookup"><span data-stu-id="dccef-173">In the upper left hand corner you will see three icons</span></span>
1. <span data-ttu-id="dccef-174">Щелкните значок, представляющий ссылку</span><span class="sxs-lookup"><span data-stu-id="dccef-174">Click on the icon representing a link</span></span>
1. <span data-ttu-id="dccef-175">Копирование URL-адреса в список воспроизведения</span><span class="sxs-lookup"><span data-stu-id="dccef-175">Copy the URL to the playlist</span></span>

<span data-ttu-id="dccef-176">![файл Share.](media/share.png) PNG теперь этот URL-адрес можно вставить в навигацию по сайту или использовать в других сообщениях, чтобы перевести сотрудников прямо в этот список.</span><span class="sxs-lookup"><span data-stu-id="dccef-176">![share.png](media/share.png) This URL can now be inserted in your site navigation or utilized in other communications to take your employees directly to that playlist.</span></span> 

### <a name="next-steps---drive-adoptiondriveadoptionmd"></a><span data-ttu-id="dccef-177">Дальнейшие действия — [внедрение диска](driveadoption.md)</span><span class="sxs-lookup"><span data-stu-id="dccef-177">Next Steps - [Drive Adoption](driveadoption.md)</span></span>

---
author: pkrebs
ms.author: pkrebs
title: Создание страниц SharePoint для списков воспроизведения
ms.date: 02/10/2019
description: Создание страниц SharePoint для списков воспроизведения
ms.openlocfilehash: c2de66a0746260e8f6539656ad70052b209c54ba
ms.sourcegitcommit: e10085e60ca3f38029fde229fb093e6bc4a34203
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 02/19/2019
ms.locfileid: "30103694"
---
# <a name="create-sharepoint-pages-for-custom-playlists"></a><span data-ttu-id="a5c65-103">Создание страниц SharePoint для настраиваемых списков воспроизведения</span><span class="sxs-lookup"><span data-stu-id="a5c65-103">Create SharePoint pages for Custom Playlists</span></span>

<span data-ttu-id="a5c65-p101">Одной из уникальных функций настраиваемого обучения является возможность создавать списки воспроизведения, собранные из Майкрософт и из ресурсов SharePoint, которые вы создаете. В этом примере мы создадим страницу SharePoint предварительно, чтобы создать список воспроизведения. Возможность создавать списки воспроизведения из страниц SharePoint предоставляет разнообразные возможности для создания страниц с помощью веб-частей, доступных от Майкрософт или организации. Например, в список воспроизведения можно добавить страницу SharePoint с внедренными видеороликами YouTube или форму, созданную на основе форм Office 365, или встроенный отчет Power BI. В этом примере мы покажем, как создать страницу с веб-частью embed и текстовой веб-частью.</span><span class="sxs-lookup"><span data-stu-id="a5c65-p101">One of the unique features of Custom Learning is the ability to create playlists that are assembled from assets from Microsoft and from SharePoint assets that you create. In this example, we’ll create a SharePoint page in advance of creating a playlist. The ability to build playlists from SharePoint pages offers a variety of opportunities to build pages using the Web parts available from Microsoft or your organization. For example, a playlist can include a SharePoint page with embedded videos from YouTube, or a form built from Office 365 Forms, or an embedded Power BI report. In this example, we’ll show you how to build a page with the Embed web part and the Text web part.</span></span>  

## <a name="create-a-sharepoint-page-for-a-custom-playlist"></a><span data-ttu-id="a5c65-109">Создание страницы SharePoint для настраиваемого списка воспроизведения</span><span class="sxs-lookup"><span data-stu-id="a5c65-109">Create a SharePoint page for a custom playlist</span></span>

1. <span data-ttu-id="a5c65-110">Щелкните значок **шестеренки** SharePoint и выберите команду **Добавить страницу**.</span><span class="sxs-lookup"><span data-stu-id="a5c65-110">Click the SharePoint **Gear** icon, and then click **Add a page**.</span></span>
2. <span data-ttu-id="a5c65-111">Щелкните **Добавить новый раздел (+)** в левой части страницы, а затем выберите **два столбца** для макета раздела.</span><span class="sxs-lookup"><span data-stu-id="a5c65-111">Click **Add a new section (+)** on the left-hand side of the page, and then click **Two Columns** for the section layout.</span></span>
3. <span data-ttu-id="a5c65-112">В левом столбце нажмите кнопку + и выберите веб-часть **внедрить** .</span><span class="sxs-lookup"><span data-stu-id="a5c65-112">In the left column, click + , and then click the **Embed** web part.</span></span> 
4. <span data-ttu-id="a5c65-p102">В правом столбце щелкните +, а затем щелкните веб-часть " **текст** ". Страница должна выглядеть так, как показано ниже.</span><span class="sxs-lookup"><span data-stu-id="a5c65-p102">In the right column, click +, and then click the **Text** web part. Your page should look like this.</span></span>

![кг-паженевстарт. png](media/cg-pagenewstart.png)

### <a name="add-a-video-and-text-from-youtube"></a><span data-ttu-id="a5c65-116">Добавление видео и текста из YouTube</span><span class="sxs-lookup"><span data-stu-id="a5c65-116">Add a video and text from YouTube</span></span>

1. <span data-ttu-id="a5c65-p103">В браузере откройте YouTube. В этом примере выполните поиск по запросу "что такое Office 365 — лучшие приложения Майкрософт".</span><span class="sxs-lookup"><span data-stu-id="a5c65-p103">In your browser, go to YouTube. For this example, search for “What is Office 365 – Microsoft’s best productivity apps”.</span></span>
2. <span data-ttu-id="a5c65-119">Щелкните видео, чтобы его запустить, затем Приостановите его, а затем щелкните правой кнопкой мыши.</span><span class="sxs-lookup"><span data-stu-id="a5c65-119">Click the video to play it, then pause it, then right-click on it.</span></span> 
3. <span data-ttu-id="a5c65-120">Нажмите кнопку **Копировать код внедрения**, а затем вернитесь на страницу SharePoint.</span><span class="sxs-lookup"><span data-stu-id="a5c65-120">Click **Copy embed code**, then return to the SharePoint page.</span></span> 
4. <span data-ttu-id="a5c65-121">Щелкните **добавить код внедрения** в веб-части **внедрить** , а затем добавьте код из YouTube Video.</span><span class="sxs-lookup"><span data-stu-id="a5c65-121">Click **Add embed code** in the **Embed** web part, and then add the code from the YouTube video.</span></span>
5. <span data-ttu-id="a5c65-122">Вернитесь на страницу YouTube и скопируйте текст **описания** для видеоролика.</span><span class="sxs-lookup"><span data-stu-id="a5c65-122">Return to the YouTube page and copy the **Description** text for the video.</span></span> 
6. <span data-ttu-id="a5c65-123">Вернитесь на страницу SharePoint, выберите веб-часть **текст** , а затем скопируйте текст из YouTube видео на YouTube.</span><span class="sxs-lookup"><span data-stu-id="a5c65-123">Return to the SharePoint page, select the **Text** web part, then copy the text from the YouTube video.</span></span>
7. <span data-ttu-id="a5c65-124">Выберите значок **Изменить веб-часть** в области заголовка страницы SharePoint, а затем назовите страницу "пользовательское представление списка".</span><span class="sxs-lookup"><span data-stu-id="a5c65-124">Select the **Edit web part** icon  in the Title area of the SharePoint page, and then name the page “Custom Playlist Introduction”.</span></span> 
8. <span data-ttu-id="a5c65-p104">В **раскладке**выберите **простой**, а затем закройте область свойства **области заголовка** . Теперь страница должна выглядеть примерно так, как показано ниже.</span><span class="sxs-lookup"><span data-stu-id="a5c65-p104">For **Layout**, select **Plain**, then close **Title Region** properties pane. The page should now look something like the following.</span></span> 

![кг-паженевфиниш. png](media/cg-pagenewfinish.png)

### <a name="publish-the-page"></a><span data-ttu-id="a5c65-128">Публикация страницы</span><span class="sxs-lookup"><span data-stu-id="a5c65-128">Publish the page</span></span>

- <span data-ttu-id="a5c65-p105">Нажмите кнопку **опубликовать** . Теперь вы готовы добавить эту страницу SharePoint к настраиваемому списку воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="a5c65-p105">Select the **Publish** button. Now you're ready to add this SharePoint page to your custom playlist.</span></span> 
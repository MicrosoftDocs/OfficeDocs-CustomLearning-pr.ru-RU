---
author: pkrebs
ms.author: pkrebs
title: Создание страниц SharePoint для списков воспроизведения
ms.date: 02/10/2019
description: Создание страниц SharePoint для списков воспроизведения
ms.openlocfilehash: 97ef3e7fd37b11011afcc0738245f364a71f5112
ms.sourcegitcommit: 1a111a49a0413a56a880e29109ba01b5e5f33d09
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/20/2019
ms.locfileid: "34247544"
---
# <a name="create-sharepoint-pages-for-custom-playlists"></a><span data-ttu-id="761a9-103">Создание страниц SharePoint для настраиваемых списков воспроизведения</span><span class="sxs-lookup"><span data-stu-id="761a9-103">Create SharePoint pages for Custom Playlists</span></span>

<span data-ttu-id="761a9-104">Одной из уникальных функций путей обучения является возможность создавать списки воспроизведения, собранные из ресурсов Майкрософт и из ресурсов SharePoint, которые вы создаете.</span><span class="sxs-lookup"><span data-stu-id="761a9-104">One of the unique features of learning pathways is the ability to create playlists that are assembled from assets from Microsoft and from SharePoint assets that you create.</span></span> <span data-ttu-id="761a9-105">В этом примере мы создадим страницу SharePoint предварительно, чтобы создать список воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="761a9-105">In this example, we’ll create a SharePoint page in advance of creating a playlist.</span></span> <span data-ttu-id="761a9-106">Возможность создавать списки воспроизведения из страниц SharePoint предоставляет разнообразные возможности для создания страниц с помощью веб-частей, доступных от Майкрософт или организации.</span><span class="sxs-lookup"><span data-stu-id="761a9-106">The ability to build playlists from SharePoint pages offers a variety of opportunities to build pages using the Web parts available from Microsoft or your organization.</span></span> <span data-ttu-id="761a9-107">Например, в список воспроизведения можно добавить страницу SharePoint с внедренными видеороликами YouTube или форму, созданную на основе форм Office 365, или встроенный отчет Power BI.</span><span class="sxs-lookup"><span data-stu-id="761a9-107">For example, a playlist can include a SharePoint page with embedded videos from YouTube, or a form built from Office 365 Forms, or an embedded Power BI report.</span></span> <span data-ttu-id="761a9-108">В этом примере мы покажем, как создать страницу с веб-частью embed и текстовой веб-частью.</span><span class="sxs-lookup"><span data-stu-id="761a9-108">In this example, we’ll show you how to build a page with the Embed web part and the Text web part.</span></span>  

## <a name="create-a-sharepoint-page-for-a-custom-playlist"></a><span data-ttu-id="761a9-109">Создание страницы SharePoint для настраиваемого списка воспроизведения</span><span class="sxs-lookup"><span data-stu-id="761a9-109">Create a SharePoint page for a custom playlist</span></span>

1. <span data-ttu-id="761a9-110">Щелкните значок **шестеренки** SharePoint и выберите команду **Добавить страницу**.</span><span class="sxs-lookup"><span data-stu-id="761a9-110">Click the SharePoint **Gear** icon, and then click **Add a page**.</span></span>
2. <span data-ttu-id="761a9-111">Щелкните **Добавить новый раздел (+)** в левой части страницы, а затем выберите **два столбца** для макета раздела.</span><span class="sxs-lookup"><span data-stu-id="761a9-111">Click **Add a new section (+)** on the left-hand side of the page, and then click **Two Columns** for the section layout.</span></span>
3. <span data-ttu-id="761a9-112">В левом столбце нажмите кнопку + и выберите веб-часть **внедрить** .</span><span class="sxs-lookup"><span data-stu-id="761a9-112">In the left column, click + , and then click the **Embed** web part.</span></span> 
4. <span data-ttu-id="761a9-113">В правом столбце щелкните +, а затем щелкните веб-часть " **текст** ".</span><span class="sxs-lookup"><span data-stu-id="761a9-113">In the right column, click +, and then click the **Text** web part.</span></span> <span data-ttu-id="761a9-114">Страница должна выглядеть так, как показано ниже.</span><span class="sxs-lookup"><span data-stu-id="761a9-114">Your page should look like this.</span></span>

![кг-паженевстарт. png](media/cg-pagenewstart.png)

### <a name="add-a-video-and-text-from-youtube"></a><span data-ttu-id="761a9-116">Добавление видео и текста из YouTube</span><span class="sxs-lookup"><span data-stu-id="761a9-116">Add a video and text from YouTube</span></span>

1. <span data-ttu-id="761a9-117">В браузере откройте YouTube.</span><span class="sxs-lookup"><span data-stu-id="761a9-117">In your browser, go to YouTube.</span></span> <span data-ttu-id="761a9-118">В этом примере выполните поиск по запросу "что такое Office 365 — лучшие приложения Майкрософт".</span><span class="sxs-lookup"><span data-stu-id="761a9-118">For this example, search for “What is Office 365 – Microsoft’s best productivity apps”.</span></span>
2. <span data-ttu-id="761a9-119">Щелкните видео, чтобы его запустить, затем Приостановите его, а затем щелкните правой кнопкой мыши.</span><span class="sxs-lookup"><span data-stu-id="761a9-119">Click the video to play it, then pause it, then right-click on it.</span></span> 
3. <span data-ttu-id="761a9-120">Нажмите кнопку **Копировать код внедрения**, а затем вернитесь на страницу SharePoint.</span><span class="sxs-lookup"><span data-stu-id="761a9-120">Click **Copy embed code**, then return to the SharePoint page.</span></span> 
4. <span data-ttu-id="761a9-121">Щелкните **добавить код внедрения** в веб-части **внедрить** , а затем добавьте код из YouTube Video.</span><span class="sxs-lookup"><span data-stu-id="761a9-121">Click **Add embed code** in the **Embed** web part, and then add the code from the YouTube video.</span></span>
5. <span data-ttu-id="761a9-122">Вернитесь на страницу YouTube и скопируйте текст **описания** для видеоролика.</span><span class="sxs-lookup"><span data-stu-id="761a9-122">Return to the YouTube page and copy the **Description** text for the video.</span></span> 
6. <span data-ttu-id="761a9-123">Вернитесь на страницу SharePoint, выберите веб-часть **текст** , а затем скопируйте текст из YouTube видео на YouTube.</span><span class="sxs-lookup"><span data-stu-id="761a9-123">Return to the SharePoint page, select the **Text** web part, then copy the text from the YouTube video.</span></span>
7. <span data-ttu-id="761a9-124">Выберите значок **Изменить веб-часть** в области заголовка страницы SharePoint, а затем назовите страницу "пользовательское представление списка".</span><span class="sxs-lookup"><span data-stu-id="761a9-124">Select the **Edit web part** icon  in the Title area of the SharePoint page, and then name the page “Custom Playlist Introduction”.</span></span> 
8. <span data-ttu-id="761a9-125">В **раскладке**выберите **простой**, а затем закройте область свойства **области заголовка** .</span><span class="sxs-lookup"><span data-stu-id="761a9-125">For **Layout**, select **Plain**, then close **Title Region** properties pane.</span></span> <span data-ttu-id="761a9-126">Теперь страница должна выглядеть примерно так, как показано ниже.</span><span class="sxs-lookup"><span data-stu-id="761a9-126">The page should now look something like the following.</span></span> 

![кг-паженевфиниш. png](media/cg-pagenewfinish.png)

### <a name="publish-the-page"></a><span data-ttu-id="761a9-128">Публикация страницы</span><span class="sxs-lookup"><span data-stu-id="761a9-128">Publish the page</span></span>

- <span data-ttu-id="761a9-129">Нажмите кнопку **опубликовать** .</span><span class="sxs-lookup"><span data-stu-id="761a9-129">Select the **Publish** button.</span></span> <span data-ttu-id="761a9-130">Теперь вы готовы добавить эту страницу SharePoint к настраиваемому списку воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="761a9-130">Now you're ready to add this SharePoint page to your custom playlist.</span></span> 
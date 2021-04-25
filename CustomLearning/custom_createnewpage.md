---
author: pkrebs
ms.author: pkrebs
title: Создание страниц SharePoint для списков воспроизведения
ms.date: 02/10/2019
description: Создание страниц SharePoint для списков воспроизведения
ms.service: sharepoint-online
ms.openlocfilehash: 40c249fbd5b0fdaefd555f23bf20ac23240ea954
ms.sourcegitcommit: 97e175e5ff5b6a9e0274d5ec9b39fdf7e18eb387
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/25/2021
ms.locfileid: "51999095"
---
# <a name="create-sharepoint-pages-for-custom-playlists"></a><span data-ttu-id="cc858-103">Создание страниц SharePoint для пользовательских списков воспроизведения</span><span class="sxs-lookup"><span data-stu-id="cc858-103">Create SharePoint pages for Custom Playlists</span></span>

<span data-ttu-id="cc858-104">Одной из уникальных функций путей обучения является возможность создания списков воспроизведения, собранных из активов Microsoft и из создавшихся активов SharePoint.</span><span class="sxs-lookup"><span data-stu-id="cc858-104">One of the unique features of learning pathways is the ability to create playlists that are assembled from assets from Microsoft and from SharePoint assets that you create.</span></span> <span data-ttu-id="cc858-105">В этом примере мы создадим страницу SharePoint перед созданием списка воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="cc858-105">In this example, we’ll create a SharePoint page in advance of creating a playlist.</span></span> <span data-ttu-id="cc858-106">Возможность создания списков воспроизведения на страницах SharePoint предоставляет множество возможностей для создания страниц с использованием веб-частей, доступных в Microsoft или вашей организации.</span><span class="sxs-lookup"><span data-stu-id="cc858-106">The ability to build playlists from SharePoint pages offers a variety of opportunities to build pages using the Web parts available from Microsoft or your organization.</span></span> <span data-ttu-id="cc858-107">Например, список воспроизведения может включать страницу SharePoint со встроенными видео с YouTube или форму, созданную из Форм Office 365, или встроенный отчет Power BI.</span><span class="sxs-lookup"><span data-stu-id="cc858-107">For example, a playlist can include a SharePoint page with embedded videos from YouTube, or a form built from Office 365 Forms, or an embedded Power BI report.</span></span> <span data-ttu-id="cc858-108">В этом примере мы покажем, как создать страницу с веб-частью Embed и веб-частью Text.</span><span class="sxs-lookup"><span data-stu-id="cc858-108">In this example, we’ll show you how to build a page with the Embed web part and the Text web part.</span></span>  

## <a name="create-a-sharepoint-page-for-a-custom-playlist"></a><span data-ttu-id="cc858-109">Создание страницы SharePoint для пользовательского списка воспроизведения</span><span class="sxs-lookup"><span data-stu-id="cc858-109">Create a SharePoint page for a custom playlist</span></span>

1. <span data-ttu-id="cc858-110">Щелкните значок SharePoint **Gear** и нажмите **кнопку Добавить страницу**.</span><span class="sxs-lookup"><span data-stu-id="cc858-110">Click the SharePoint **Gear** icon, and then click **Add a page**.</span></span>
2. <span data-ttu-id="cc858-111">Нажмите **кнопку Добавить новый раздел (+)** на левой стороне страницы, а затем нажмите кнопку **Два столбца** для макета раздела.</span><span class="sxs-lookup"><span data-stu-id="cc858-111">Click **Add a new section (+)** on the left-hand side of the page, and then click **Two Columns** for the section layout.</span></span>
3. <span data-ttu-id="cc858-112">В левом столбце нажмите кнопку +, а затем щелкните **веб-часть Embed.**</span><span class="sxs-lookup"><span data-stu-id="cc858-112">In the left column, click + , and then click the **Embed** web part.</span></span> 
4. <span data-ttu-id="cc858-113">В правой колонке нажмите кнопку +, а затем нажмите **текстовую** веб-часть.</span><span class="sxs-lookup"><span data-stu-id="cc858-113">In the right column, click +, and then click the **Text** web part.</span></span> <span data-ttu-id="cc858-114">Ваша страница должна выглядеть так.</span><span class="sxs-lookup"><span data-stu-id="cc858-114">Your page should look like this.</span></span>

![cg-pagenewstart.png](media/cg-pagenewstart.png)

### <a name="add-a-video-and-text-from-youtube"></a><span data-ttu-id="cc858-116">Добавление видео и текста с YouTube</span><span class="sxs-lookup"><span data-stu-id="cc858-116">Add a video and text from YouTube</span></span>

1. <span data-ttu-id="cc858-117">В браузере перейдите на YouTube.</span><span class="sxs-lookup"><span data-stu-id="cc858-117">In your browser, go to YouTube.</span></span> <span data-ttu-id="cc858-118">В этом примере можно найти "Что такое Office 365 — лучшие приложения Майкрософт по производительности".</span><span class="sxs-lookup"><span data-stu-id="cc858-118">For this example, search for “What is Office 365 – Microsoft’s best productivity apps”.</span></span>
2. <span data-ttu-id="cc858-119">Щелкните видео, чтобы играть в него, а затем приостановить его, а затем правой кнопкой мыши на нем.</span><span class="sxs-lookup"><span data-stu-id="cc858-119">Click the video to play it, then pause it, then right-click on it.</span></span> 
3. <span data-ttu-id="cc858-120">Нажмите **кнопку Скопируйте встраив код,** а затем вернитесь на страницу SharePoint.</span><span class="sxs-lookup"><span data-stu-id="cc858-120">Click **Copy embed code**, then return to the SharePoint page.</span></span> 
4. <span data-ttu-id="cc858-121">Нажмите **кнопку Добавить встраив код** в веб-части **Embed,** а затем добавить код из видео YouTube.</span><span class="sxs-lookup"><span data-stu-id="cc858-121">Click **Add embed code** in the **Embed** web part, and then add the code from the YouTube video.</span></span>
5. <span data-ttu-id="cc858-122">Вернись на страницу YouTube и скопируйте текст **Описания** для видео.</span><span class="sxs-lookup"><span data-stu-id="cc858-122">Return to the YouTube page and copy the **Description** text for the video.</span></span> 
6. <span data-ttu-id="cc858-123">Вернитесь на страницу SharePoint, выберите **текстовую** веб-часть, а затем скопируйте текст из видео На YouTube.</span><span class="sxs-lookup"><span data-stu-id="cc858-123">Return to the SharePoint page, select the **Text** web part, then copy the text from the YouTube video.</span></span>
7. <span data-ttu-id="cc858-124">Выберите **значок Изменить веб-часть** в области Title страницы SharePoint, а затем назови страницу "Введение пользовательского списка воспроизведения".</span><span class="sxs-lookup"><span data-stu-id="cc858-124">Select the **Edit web part** icon  in the Title area of the SharePoint page, and then name the page “Custom Playlist Introduction”.</span></span> 
8. <span data-ttu-id="cc858-125">Для **макета** выберите **равнину,** а затем закроем область свойств **Title Region.**</span><span class="sxs-lookup"><span data-stu-id="cc858-125">For **Layout**, select **Plain**, then close **Title Region** properties pane.</span></span> <span data-ttu-id="cc858-126">Теперь страница должна выглядеть как следующая.</span><span class="sxs-lookup"><span data-stu-id="cc858-126">The page should now look something like the following.</span></span> 

![cg-pagenewfinish.png](media/cg-pagenewfinish.png)

### <a name="publish-the-page"></a><span data-ttu-id="cc858-128">Публикация страницы</span><span class="sxs-lookup"><span data-stu-id="cc858-128">Publish the page</span></span>

- <span data-ttu-id="cc858-129">Выберите **кнопку Публикация.**</span><span class="sxs-lookup"><span data-stu-id="cc858-129">Select the **Publish** button.</span></span> <span data-ttu-id="cc858-130">Теперь вы готовы добавить эту страницу SharePoint в настраиваемый список воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="cc858-130">Now you're ready to add this SharePoint page to your custom playlist.</span></span> 
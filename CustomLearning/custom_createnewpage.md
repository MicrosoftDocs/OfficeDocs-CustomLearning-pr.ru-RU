---
author: pkrebs
ms.author: pkrebs
title: Создание SharePoint страниц для списков воспроизведения
ms.date: 02/10/2019
description: Создание SharePoint страниц для списков воспроизведения
ms.service: sharepoint-online
manager: bpardi
ms.topic: article
ms.openlocfilehash: ce4a204b3072469840b6f3fa8f93d9e78833b181
ms.sourcegitcommit: 956ab22dd8ce23ee1779f1a01d34b434243c3cb1
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/11/2021
ms.locfileid: "52310663"
---
# <a name="create-sharepoint-pages-for-custom-playlists"></a><span data-ttu-id="434d1-103">Создание SharePoint страниц для пользовательских списков воспроизведения</span><span class="sxs-lookup"><span data-stu-id="434d1-103">Create SharePoint pages for Custom Playlists</span></span>

<span data-ttu-id="434d1-104">Одной из уникальных функций путей обучения является возможность создания списков воспроизведения, собранных из активов Майкрософт и из SharePoint, которые вы создаете.</span><span class="sxs-lookup"><span data-stu-id="434d1-104">One of the unique features of learning pathways is the ability to create playlists that are assembled from assets from Microsoft and from SharePoint assets that you create.</span></span> <span data-ttu-id="434d1-105">В этом примере мы создадим SharePoint страницу перед созданием списка воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="434d1-105">In this example, we’ll create a SharePoint page in advance of creating a playlist.</span></span> <span data-ttu-id="434d1-106">Возможность создания плейлистов из SharePoint страниц предоставляет множество возможностей для создания страниц с использованием веб-частей, доступных в Microsoft или вашей организации.</span><span class="sxs-lookup"><span data-stu-id="434d1-106">The ability to build playlists from SharePoint pages offers a variety of opportunities to build pages using the Web parts available from Microsoft or your organization.</span></span> <span data-ttu-id="434d1-107">Например, список воспроизведения может включать страницу SharePoint со встроенными видео с YouTube или форму, созданную из Office 365 Forms, или встроенный отчет Power BI.</span><span class="sxs-lookup"><span data-stu-id="434d1-107">For example, a playlist can include a SharePoint page with embedded videos from YouTube, or a form built from Office 365 Forms, or an embedded Power BI report.</span></span> <span data-ttu-id="434d1-108">В этом примере мы покажем, как создать страницу с веб-частью Embed и веб-частью Text.</span><span class="sxs-lookup"><span data-stu-id="434d1-108">In this example, we’ll show you how to build a page with the Embed web part and the Text web part.</span></span>  

## <a name="create-a-sharepoint-page-for-a-custom-playlist"></a><span data-ttu-id="434d1-109">Создание страницы SharePoint для настраиваемой страницы воспроизведения</span><span class="sxs-lookup"><span data-stu-id="434d1-109">Create a SharePoint page for a custom playlist</span></span>

1. <span data-ttu-id="434d1-110">Щелкните значок SharePoint **Gear** и нажмите **кнопку Добавить страницу**.</span><span class="sxs-lookup"><span data-stu-id="434d1-110">Click the SharePoint **Gear** icon, and then click **Add a page**.</span></span>
2. <span data-ttu-id="434d1-111">Нажмите **кнопку Добавить новый раздел (+)** на левой стороне страницы, а затем нажмите кнопку **Два столбца** для макета раздела.</span><span class="sxs-lookup"><span data-stu-id="434d1-111">Click **Add a new section (+)** on the left-hand side of the page, and then click **Two Columns** for the section layout.</span></span>
3. <span data-ttu-id="434d1-112">В левом столбце нажмите кнопку +, а затем щелкните **веб-часть Embed.**</span><span class="sxs-lookup"><span data-stu-id="434d1-112">In the left column, click + , and then click the **Embed** web part.</span></span> 
4. <span data-ttu-id="434d1-113">В правой колонке нажмите кнопку +, а затем нажмите **текстовую** веб-часть.</span><span class="sxs-lookup"><span data-stu-id="434d1-113">In the right column, click +, and then click the **Text** web part.</span></span> <span data-ttu-id="434d1-114">Ваша страница должна выглядеть так.</span><span class="sxs-lookup"><span data-stu-id="434d1-114">Your page should look like this.</span></span>

![cg-pagenewstart.png](media/cg-pagenewstart.png)

### <a name="add-a-video-and-text-from-youtube"></a><span data-ttu-id="434d1-116">Добавление видео и текста с YouTube</span><span class="sxs-lookup"><span data-stu-id="434d1-116">Add a video and text from YouTube</span></span>

1. <span data-ttu-id="434d1-117">В браузере перейдите на YouTube.</span><span class="sxs-lookup"><span data-stu-id="434d1-117">In your browser, go to YouTube.</span></span> <span data-ttu-id="434d1-118">В этом примере можно найти "Что Office 365 — лучшие приложения майкрософт по производительности".</span><span class="sxs-lookup"><span data-stu-id="434d1-118">For this example, search for “What is Office 365 – Microsoft’s best productivity apps”.</span></span>
2. <span data-ttu-id="434d1-119">Щелкните видео, чтобы играть в него, а затем приостановить его, а затем правой кнопкой мыши на нем.</span><span class="sxs-lookup"><span data-stu-id="434d1-119">Click the video to play it, then pause it, then right-click on it.</span></span> 
3. <span data-ttu-id="434d1-120">Нажмите **кнопку Скопируйте** встраив код, а затем SharePoint страницу.</span><span class="sxs-lookup"><span data-stu-id="434d1-120">Click **Copy embed code**, then return to the SharePoint page.</span></span> 
4. <span data-ttu-id="434d1-121">Нажмите **кнопку Добавить встраив код** в веб-части **Embed,** а затем добавить код из видео YouTube.</span><span class="sxs-lookup"><span data-stu-id="434d1-121">Click **Add embed code** in the **Embed** web part, and then add the code from the YouTube video.</span></span>
5. <span data-ttu-id="434d1-122">Вернись на страницу YouTube и скопируйте текст **Описания** для видео.</span><span class="sxs-lookup"><span data-stu-id="434d1-122">Return to the YouTube page and copy the **Description** text for the video.</span></span> 
6. <span data-ttu-id="434d1-123">Вернись на SharePoint страницу, выберите веб-часть **Text,** а затем скопируйте текст из видео YouTube.</span><span class="sxs-lookup"><span data-stu-id="434d1-123">Return to the SharePoint page, select the **Text** web part, then copy the text from the YouTube video.</span></span>
7. <span data-ttu-id="434d1-124">Выберите **значок Изменить веб-часть** в области Название страницы SharePoint, а затем назови страницу "Введение пользовательского списка воспроизведения".</span><span class="sxs-lookup"><span data-stu-id="434d1-124">Select the **Edit web part** icon  in the Title area of the SharePoint page, and then name the page “Custom Playlist Introduction”.</span></span> 
8. <span data-ttu-id="434d1-125">Для **макета** выберите **равнину,** а затем закроем область свойств **Title Region.**</span><span class="sxs-lookup"><span data-stu-id="434d1-125">For **Layout**, select **Plain**, then close **Title Region** properties pane.</span></span> <span data-ttu-id="434d1-126">Теперь страница должна выглядеть как следующая.</span><span class="sxs-lookup"><span data-stu-id="434d1-126">The page should now look something like the following.</span></span> 

![cg-pagenewfinish.png](media/cg-pagenewfinish.png)

### <a name="publish-the-page"></a><span data-ttu-id="434d1-128">Публикация страницы</span><span class="sxs-lookup"><span data-stu-id="434d1-128">Publish the page</span></span>

- <span data-ttu-id="434d1-129">Выберите **кнопку Публикация.**</span><span class="sxs-lookup"><span data-stu-id="434d1-129">Select the **Publish** button.</span></span> <span data-ttu-id="434d1-130">Теперь вы готовы добавить эту страницу SharePoint в настраиваемый список воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="434d1-130">Now you're ready to add this SharePoint page to your custom playlist.</span></span> 
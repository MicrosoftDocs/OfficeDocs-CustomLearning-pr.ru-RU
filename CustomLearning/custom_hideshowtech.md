---
author: pkrebs
ms.author: pkrebs
title: Технология скрытия и отображения
ms.date: 02/15/2019
description: Как скрыть и показать технологию
ms.openlocfilehash: 38b814b85d4e060e5387b2173476c455cfcf7160
ms.sourcegitcommit: 775d6807291ab263eea5ec649d9aaf1933fb41ca
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/23/2019
ms.locfileid: "32055677"
---
# <a name="hide-and-show-technology"></a><span data-ttu-id="a8e3c-103">Технология скрытия и отображения</span><span class="sxs-lookup"><span data-stu-id="a8e3c-103">Hide and show Technology</span></span>

<span data-ttu-id="a8e3c-104">В некоторых случаях необходимо скрыть контент для технологии, которая не поддерживается в вашей организации.</span><span class="sxs-lookup"><span data-stu-id="a8e3c-104">In some cases, you’ll want to hide content for a technology that’s not supported in your organization.</span></span> <span data-ttu-id="a8e3c-105">Технология Hide разработана, чтобы предотвратить появление технологии во всей веб-части.</span><span class="sxs-lookup"><span data-stu-id="a8e3c-105">The Hide Technology feature is designed to prevent technology from appearing throughout the Web part.</span></span> <span data-ttu-id="a8e3c-106">Он предоставляет более широкий способ скрытия и отображения содержимого, чем скрытие подкатегории или списка воспроизведения.</span><span class="sxs-lookup"><span data-stu-id="a8e3c-106">It offers a broader way to hide and show content than hiding it by subcategory or playlist.</span></span> <span data-ttu-id="a8e3c-107">Например, можно скрыть подкатегорию Yammer, но Yammer может по-прежнему отображаться в списках воспроизведения в определенных сценариях, таких как "подключение Организации к Yammer".</span><span class="sxs-lookup"><span data-stu-id="a8e3c-107">For example, you can hide a Yammer subcategory, but Yammer may still show up in certain scenario playlists such as "Connect your organization with Yammer".</span></span> <span data-ttu-id="a8e3c-108">Чтобы убедиться, что конкретная технология недоступна для конечных пользователей, ее можно скрыть с помощью технологии.</span><span class="sxs-lookup"><span data-stu-id="a8e3c-108">To ensure a specific technology is not exposed to end users, you can hide it by Technology.</span></span> 

## <a name="hide-a-technology"></a><span data-ttu-id="a8e3c-109">Скрытие технологии</span><span class="sxs-lookup"><span data-stu-id="a8e3c-109">Hide a Technology</span></span>

1. <span data-ttu-id="a8e3c-110">На настраиваемой **домашней** странице обучения щелкните плитку **обучение Office 365** .</span><span class="sxs-lookup"><span data-stu-id="a8e3c-110">From the Custom Learning **Home** page, click the **Office 365 training** tile.</span></span>
2. <span data-ttu-id="a8e3c-111">В настраиваемой веб-части обучения выберите пункт меню **система** , а затем — **Администрирование списка воспроизведения**.</span><span class="sxs-lookup"><span data-stu-id="a8e3c-111">From the Custom Learning Web part, select the **System** menu, then select **Administer Playlist**.</span></span> <span data-ttu-id="a8e3c-112">Теперь у вас должны быть две вкладки.</span><span class="sxs-lookup"><span data-stu-id="a8e3c-112">You should now have two tabs open.</span></span> <span data-ttu-id="a8e3c-113">Один с настраиваемой страницей **администрирования обучения** и другой на странице учебного руководства по **Office 365** .</span><span class="sxs-lookup"><span data-stu-id="a8e3c-113">One with the **Custom Learning Administration** page, and one with the **Office 365 training** page.</span></span> 
3. <span data-ttu-id="a8e3c-114">На странице **настраиваемОго администрирования обучения** щелкните **технологию**, а затем выберите эйебалл, чтобы скрыть ее.</span><span class="sxs-lookup"><span data-stu-id="a8e3c-114">From the **Custom Learning Administration** page, click a **Technology**, and then select the eyeball for the Technology to hide it.</span></span> <span data-ttu-id="a8e3c-115">В этом примере выберите технологию **Yammer** , а затем скройте ее.</span><span class="sxs-lookup"><span data-stu-id="a8e3c-115">For this example, click the **Yammer** technology, and then hide it.</span></span>  

![кг-хидетеч. png](media/cg-hidetech.png)

### <a name="verify-the-playlist-is-hidden"></a><span data-ttu-id="a8e3c-117">Проверка скрытости списка воспроизведения</span><span class="sxs-lookup"><span data-stu-id="a8e3c-117">Verify the playlist is hidden</span></span>
1. <span data-ttu-id="a8e3c-118">Чтобы убедиться, что технология **Yammer** скрыта, перейдите на вкладку браузер с загруженной страницей учебного заработка **Office 365** и обновите страницу.</span><span class="sxs-lookup"><span data-stu-id="a8e3c-118">To verify **Yammer** technology is hidden, select the browser tab with the **Office 365 training** page loaded, and then refresh the page.</span></span> <span data-ttu-id="a8e3c-119">Теперь Подкатегория Yammer должна отображаться как скрытая.</span><span class="sxs-lookup"><span data-stu-id="a8e3c-119">You should now see the Yammer subcategory is hidden.</span></span> 
2. <span data-ttu-id="a8e3c-120">Щелкните **рекомендуемую** подкатегорию.</span><span class="sxs-lookup"><span data-stu-id="a8e3c-120">Click the **Recommended** subcategory.</span></span> <span data-ttu-id="a8e3c-121">Обратите внимание, что элемент подключить к вашей организации с помощью списка воспроизведения Yammer скрыт.</span><span class="sxs-lookup"><span data-stu-id="a8e3c-121">You'll notice that the Connect your organization with Yammer playlist is hidden.</span></span> 

![кг-хидетечрефреш. png](media/cg-hidetechrefresh.png)

## <a name="unhide-a-technology"></a><span data-ttu-id="a8e3c-123">Отображение технологии</span><span class="sxs-lookup"><span data-stu-id="a8e3c-123">Unhide a Technology</span></span>

- <span data-ttu-id="a8e3c-124">На странице **настраиваемОго администрирования обучения** в разделе **технология**выберите технологию, а затем выберите эйебалл, чтобы скрыть эту технологию, чтобы она была скрыта.</span><span class="sxs-lookup"><span data-stu-id="a8e3c-124">From the **Custom Learning Administration** page, under **Technology**, select a technology, then select the eyeball for the hidden technology to unhide it.</span></span> <span data-ttu-id="a8e3c-125">В этом примере показано, как отобразить технологию **Yammer** .</span><span class="sxs-lookup"><span data-stu-id="a8e3c-125">For this example, unhide the **Yammer** technology.</span></span> 
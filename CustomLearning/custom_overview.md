---
author: pkrebs
ms.author: pkrebs
title: Обзор
ms.date: 02/18/2019
description: Обзор настраиваемого обучения для Office 365 для администраторов
ms.openlocfilehash: 6aee3a93a5109b37e43a7118bd98ca31e8b9ac1f
ms.sourcegitcommit: 775d6807291ab263eea5ec649d9aaf1933fb41ca
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/23/2019
ms.locfileid: "32055647"
---
# <a name="customize-the-learning-experience"></a><span data-ttu-id="5a339-103">Настройка обучающих интерфейсов</span><span class="sxs-lookup"><span data-stu-id="5a339-103">Customize the Learning Experience</span></span>

<span data-ttu-id="5a339-104">В этом разделе представлено новое решение для Office 365, разработанное корпорацией Майкрософт для ускорения использования и внедрения Office 365 в пределах организации.</span><span class="sxs-lookup"><span data-stu-id="5a339-104">Introducing Custom Learning for Office 365, a new solution from Microsoft designed to speed the usage and adoption of Office 365 within an organization.</span></span> <span data-ttu-id="5a339-105">С помощью настраиваемого обучения вы можете:</span><span class="sxs-lookup"><span data-stu-id="5a339-105">With Custom Learning, you can:</span></span>
- <span data-ttu-id="5a339-106">Планирование контента Office 365 для обучения и принятия в среде</span><span class="sxs-lookup"><span data-stu-id="5a339-106">Tailor Office 365 learning and adoption content for your environment</span></span> 
- <span data-ttu-id="5a339-107">Скрытие или отображение контента для отображения служб и компонентов, поддерживаемых в Организации</span><span class="sxs-lookup"><span data-stu-id="5a339-107">Hide or show content to reflect the services or features supported in your organization</span></span> 
- <span data-ttu-id="5a339-108">Обеспечение актуальности контента и пользователей с помощью актуального канала обучения от Майкрософт</span><span class="sxs-lookup"><span data-stu-id="5a339-108">Keep your content and users current with an up-to-date feed of learning content from Microsoft</span></span> 
- <span data-ttu-id="5a339-109">Создание настраиваемых списков воспроизведения и категорий, специально разработанных для потребностей пользователя</span><span class="sxs-lookup"><span data-stu-id="5a339-109">Build custom playlists and categories crafted specifically for your user's needs</span></span>

![кг-интродуЦинг. png](media/cg-introducing.png)

## <a name="how-does-custom-learning-work"></a><span data-ttu-id="5a339-111">Как работает пользовательское обучение?</span><span class="sxs-lookup"><span data-stu-id="5a339-111">How does Custom Learning work?</span></span>

<span data-ttu-id="5a339-112">Пользовательское обучение для Office 365 (особое обучение сокращено) состоит из трех частей:</span><span class="sxs-lookup"><span data-stu-id="5a339-112">Custom Learning for Office 365 (Custom Learning for short) consists of three parts:</span></span> 
1. <span data-ttu-id="5a339-113">динамический канал контента из каталога Microsoft Online</span><span class="sxs-lookup"><span data-stu-id="5a339-113">a live feed of content from a Microsoft online catalog</span></span>
2. <span data-ttu-id="5a339-114">сайт для общения с SharePoint</span><span class="sxs-lookup"><span data-stu-id="5a339-114">a SharePoint communication site</span></span>
3. <span data-ttu-id="5a339-115">веб-часть SharePoint</span><span class="sxs-lookup"><span data-stu-id="5a339-115">a SharePoint web part</span></span> 

![кг-ховитворкс. png](media/cg-howitworks.png)

## <a name="requirements-and-permissions"></a><span data-ttu-id="5a339-117">Требования и разрешения</span><span class="sxs-lookup"><span data-stu-id="5a339-117">Requirements and Permissions</span></span>

<span data-ttu-id="5a339-118">Прежде чем приступить к работе с этим руководством, убедитесь, что администратор клиента SharePoint настроил настраиваемый обучающий курс.</span><span class="sxs-lookup"><span data-stu-id="5a339-118">Before getting started with this guide, ensure that Custom Learning has been set up by your SharePoint Tenant Administrator.</span></span> <span data-ttu-id="5a339-119">Если вы не уверены в том, что он настроен, обратитесь к администратору клиента SharePoint, чтобы убедиться, что настроенное обучение подготовлено.</span><span class="sxs-lookup"><span data-stu-id="5a339-119">If you’re not sure if it's been set up, contact your SharePoint tenant administrator to verify that Custom Learning has been provisioned.</span></span> <span data-ttu-id="5a339-120">Кроме того, вы можете получить URL-адрес настраиваемого сайта SharePoint для обучения.</span><span class="sxs-lookup"><span data-stu-id="5a339-120">Also be sure to get the URL of the Custom Learning SharePoint site.</span></span> <span data-ttu-id="5a339-121">Если вы являетесь администратором клиента и не подготовлены дополнительные обучающие материалы, ознакомьтесь со статьей [Подготовка настраиваемОго обучения](custom_provision.md).</span><span class="sxs-lookup"><span data-stu-id="5a339-121">If you are the Tenant Administrator and Custom Learning has not been provisioned, see [Provision Custom Learning](custom_provision.md).</span></span> 

### <a name="permissions-to-provision-custom-learning"></a><span data-ttu-id="5a339-122">Разрешения на подготовку настраиваемого обучения</span><span class="sxs-lookup"><span data-stu-id="5a339-122">Permissions to provision Custom Learning</span></span>

- <span data-ttu-id="5a339-123">Администратор клиента, который также называется глобальным администратором Office 365</span><span class="sxs-lookup"><span data-stu-id="5a339-123">Tenant Administrator, also known as Office 365 Global Administrator</span></span>
- <span data-ttu-id="5a339-124">Администратор семейства веб-сайтов SharePoint с разрешениями владельца для сайта</span><span class="sxs-lookup"><span data-stu-id="5a339-124">SharePoint Site Collection Administrator with Owner permissions on the site</span></span>

### <a name="permissions-to-use-custom-learning-administration-features"></a><span data-ttu-id="5a339-125">Разрешения на использование настраиваемых функций администрирования обучения</span><span class="sxs-lookup"><span data-stu-id="5a339-125">Permissions to use Custom Learning Administration features</span></span>

- <span data-ttu-id="5a339-126">Администратор семейства веб-сайтов</span><span class="sxs-lookup"><span data-stu-id="5a339-126">Site Collection Administrator</span></span>
- <span data-ttu-id="5a339-127">Разрешения владельца или члена SharePoint</span><span class="sxs-lookup"><span data-stu-id="5a339-127">SharePoint Owner or Member permissions</span></span>

### <a name="permissions-to-use-the-custom-learning-site-as-a-user"></a><span data-ttu-id="5a339-128">Разрешения на использование настраиваемого сайта обучения в качестве пользователя</span><span class="sxs-lookup"><span data-stu-id="5a339-128">Permissions to use the Custom Learning site as a user</span></span>

- <span data-ttu-id="5a339-129">Разрешения пользователей Office 365, разрешения посетителей сайта SharePoint и выше</span><span class="sxs-lookup"><span data-stu-id="5a339-129">Office 365 user permissions/SharePoint Site Visitor permissions or higher</span></span>

## <a name="get-started-with-customization"></a><span data-ttu-id="5a339-130">Начало работы с настройками</span><span class="sxs-lookup"><span data-stu-id="5a339-130">Get started with customization</span></span>
<span data-ttu-id="5a339-131">После того, как вы убедитесь, что у вас есть необходимые разрешения на настройку сайта и веб-части, необходимо начать процесс настройки.</span><span class="sxs-lookup"><span data-stu-id="5a339-131">Once you've ensured you have the necessary permissions to customize the site and web part, it's time to get started with the customization process.</span></span> 

- <span data-ttu-id="5a339-132">Чтобы приступить к работе, ознакомьтесь со статьей ["переход на настраиваемЫй сайт обучения"](custom_goto.md).</span><span class="sxs-lookup"><span data-stu-id="5a339-132">To get started, see [Go to the Custom Learning Site](custom_goto.md).</span></span>
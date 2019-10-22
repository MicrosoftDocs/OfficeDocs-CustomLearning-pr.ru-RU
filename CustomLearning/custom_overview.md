---
author: pkrebs
ms.author: pkrebs
title: Обзор
ms.date: 02/18/2019
description: Обзор путей обучения Microsoft 365
ms.openlocfilehash: 74fac090177ad8009155e21a977b05ee2b742b3b
ms.sourcegitcommit: f5a7079d56598c14aef2f4b886c025a59ba89276
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/21/2019
ms.locfileid: "34247860"
---
# <a name="customize-the-learning-experience"></a><span data-ttu-id="c3219-103">Настройка обучающих интерфейсов</span><span class="sxs-lookup"><span data-stu-id="c3219-103">Customize the learning experience</span></span>

<span data-ttu-id="c3219-104">Знакомство с Microsoft 365 Learning, новое решение корпорации Майкрософт, предназначенное для ускорения использования и внедрения Office 365 в пределах организации.</span><span class="sxs-lookup"><span data-stu-id="c3219-104">Introducing Microsoft 365 learning pathways, a new solution from Microsoft designed to speed the usage and adoption of Office 365 within an organization.</span></span> <span data-ttu-id="c3219-105">С помощью обучающих пасвяс можно выполнять следующие действия:</span><span class="sxs-lookup"><span data-stu-id="c3219-105">With learning pathwyas, you can:</span></span>
- <span data-ttu-id="c3219-106">Адаптация контента Майкрософт 365 для обучения и принятия в среде</span><span class="sxs-lookup"><span data-stu-id="c3219-106">Tailor Microsoft 365 learning and adoption content for your environment</span></span> 
- <span data-ttu-id="c3219-107">Скрытие или отображение контента для отображения служб и компонентов, поддерживаемых в Организации</span><span class="sxs-lookup"><span data-stu-id="c3219-107">Hide or show content to reflect the services or features supported in your organization</span></span> 
- <span data-ttu-id="c3219-108">Обеспечение актуальности контента и пользователей с помощью актуального канала обучения от Майкрософт</span><span class="sxs-lookup"><span data-stu-id="c3219-108">Keep your content and users current with an up-to-date feed of learning content from Microsoft</span></span> 
- <span data-ttu-id="c3219-109">Создание настраиваемых списков воспроизведения и категорий, специально разработанных для потребностей пользователя</span><span class="sxs-lookup"><span data-stu-id="c3219-109">Build custom playlists and categories crafted specifically for your user's needs</span></span>

![кг-интродуЦинг. png](media/cg-introducing.png)

## <a name="how-does-learning-pathways-work"></a><span data-ttu-id="c3219-111">Принципы работы путей обучения</span><span class="sxs-lookup"><span data-stu-id="c3219-111">How does learning pathways work?</span></span>

<span data-ttu-id="c3219-112">пути обучения для Office 365 (краткие пути для обучения) состоят из трех частей:</span><span class="sxs-lookup"><span data-stu-id="c3219-112">learning pathways for Office 365 (learning pathways for short) consists of three parts:</span></span> 
1. <span data-ttu-id="c3219-113">динамический канал контента из каталога Microsoft Online</span><span class="sxs-lookup"><span data-stu-id="c3219-113">a live feed of content from a Microsoft online catalog</span></span>
2. <span data-ttu-id="c3219-114">сайт для общения с SharePoint</span><span class="sxs-lookup"><span data-stu-id="c3219-114">a SharePoint communication site</span></span>
3. <span data-ttu-id="c3219-115">веб-часть SharePoint</span><span class="sxs-lookup"><span data-stu-id="c3219-115">a SharePoint web part</span></span> 

![кг-ховитворкс. png](media/cg-howitworks.png)

## <a name="requirements-and-permissions"></a><span data-ttu-id="c3219-117">Требования и разрешения</span><span class="sxs-lookup"><span data-stu-id="c3219-117">Requirements and Permissions</span></span>

<span data-ttu-id="c3219-118">Прежде чем приступить к работе с этим руководством, убедитесь, что администратор клиента SharePoint настроил пути для обучения.</span><span class="sxs-lookup"><span data-stu-id="c3219-118">Before getting started with this guide, ensure that learning pathways has been set up by your SharePoint Tenant Administrator.</span></span> <span data-ttu-id="c3219-119">Если вы не уверены в том, что он настроен, обратитесь к администратору клиента SharePoint, чтобы проверить, подготовлены ли пути для обучения.</span><span class="sxs-lookup"><span data-stu-id="c3219-119">If you’re not sure if it's been set up, contact your SharePoint tenant administrator to verify that learning pathways has been provisioned.</span></span> <span data-ttu-id="c3219-120">Кроме того, вы можете получить URL-адрес сайта SharePoint "пути для обучения".</span><span class="sxs-lookup"><span data-stu-id="c3219-120">Also be sure to get the URL of the learning pathways SharePoint site.</span></span> <span data-ttu-id="c3219-121">Если вы являетесь администратором клиента и его пути для обучения не подготовлены, ознакомьтесь со статьей [Подготовка путей обучения](custom_provision.md).</span><span class="sxs-lookup"><span data-stu-id="c3219-121">If you are the Tenant Administrator and learning pathways has not been provisioned, see [Provision learning pathways](custom_provision.md).</span></span> 

### <a name="permissions-to-provision-learning-pathways"></a><span data-ttu-id="c3219-122">Разрешения для подготовки путей обучения</span><span class="sxs-lookup"><span data-stu-id="c3219-122">Permissions to provision learning pathways</span></span>

- <span data-ttu-id="c3219-123">Администратор клиента, который также называется глобальным администратором Office 365</span><span class="sxs-lookup"><span data-stu-id="c3219-123">Tenant Administrator, also known as Office 365 Global Administrator</span></span>
- <span data-ttu-id="c3219-124">Администратор семейства веб-сайтов SharePoint с разрешениями владельца для сайта</span><span class="sxs-lookup"><span data-stu-id="c3219-124">SharePoint Site Collection Administrator with Owner permissions on the site</span></span>

### <a name="permissions-to-use-learning-pathways-administration-features"></a><span data-ttu-id="c3219-125">Разрешения для использования средств администрирования путей обучения</span><span class="sxs-lookup"><span data-stu-id="c3219-125">Permissions to use learning pathways Administration features</span></span>

- <span data-ttu-id="c3219-126">Администратор семейства веб-сайтов</span><span class="sxs-lookup"><span data-stu-id="c3219-126">Site Collection Administrator</span></span>
- <span data-ttu-id="c3219-127">Разрешения владельца или члена SharePoint</span><span class="sxs-lookup"><span data-stu-id="c3219-127">SharePoint Owner or Member permissions</span></span>

### <a name="permissions-to-use-the-learning-pathways-site-as-a-user"></a><span data-ttu-id="c3219-128">Разрешения на использование сайта обучающих путей в качестве пользователя</span><span class="sxs-lookup"><span data-stu-id="c3219-128">Permissions to use the learning pathways site as a user</span></span>

- <span data-ttu-id="c3219-129">Разрешения пользователей Office 365, разрешения посетителей сайта SharePoint и выше</span><span class="sxs-lookup"><span data-stu-id="c3219-129">Office 365 user permissions/SharePoint Site Visitor permissions or higher</span></span>

## <a name="get-started-with-customization"></a><span data-ttu-id="c3219-130">Начало работы с настройками</span><span class="sxs-lookup"><span data-stu-id="c3219-130">Get started with customization</span></span>
<span data-ttu-id="c3219-131">После того, как вы убедитесь, что у вас есть необходимые разрешения на настройку сайта и веб-части, необходимо начать процесс настройки.</span><span class="sxs-lookup"><span data-stu-id="c3219-131">Once you've ensured you have the necessary permissions to customize the site and web part, it's time to get started with the customization process.</span></span> 

- <span data-ttu-id="c3219-132">Чтобы приступить к работе, ознакомьтесь со статьей [Переход на сайт пути для обучения](custom_goto.md).</span><span class="sxs-lookup"><span data-stu-id="c3219-132">To get started, see [Go to the learning pathways site](custom_goto.md).</span></span>
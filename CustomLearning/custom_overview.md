---
author: pkrebs
ms.author: pkrebs
title: Общие сведения
ms.date: 02/18/2019
description: Обзор настраиваемого обучения для Office 365 для администраторов
ms.openlocfilehash: 98187038b66252523c74d88dd9bfd0f217591bc5
ms.sourcegitcommit: e10085e60ca3f38029fde229fb093e6bc4a34203
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 02/25/2019
ms.locfileid: "30087538"
---
# <a name="customize-the-learning-experience"></a><span data-ttu-id="b7c29-103">Настройка обучающих интерфейсов</span><span class="sxs-lookup"><span data-stu-id="b7c29-103">Customize the Learning Experience</span></span>

<span data-ttu-id="b7c29-p101">В этом разделе представлено новое решение для Office 365, разработанное корпорацией Майкрософт для ускорения использования и внедрения Office 365 в пределах организации. С помощью настраиваемого обучения вы можете:</span><span class="sxs-lookup"><span data-stu-id="b7c29-p101">Introducing Custom Learning for Office 365, a new solution from Microsoft designed to speed the usage and adoption of Office 365 within an organization. With Custom Learning, you can:</span></span>
- <span data-ttu-id="b7c29-106">Планирование контента Office 365 для обучения и принятия в среде</span><span class="sxs-lookup"><span data-stu-id="b7c29-106">Tailor Office 365 learning and adoption content for your environment</span></span> 
- <span data-ttu-id="b7c29-107">Скрытие или отображение контента для отображения служб и компонентов, поддерживаемых в Организации</span><span class="sxs-lookup"><span data-stu-id="b7c29-107">Hide or show content to reflect the services or features supported in your organization</span></span> 
- <span data-ttu-id="b7c29-108">Обеспечение актуальности контента и пользователей с помощью актуального канала обучения от Майкрософт</span><span class="sxs-lookup"><span data-stu-id="b7c29-108">Keep your content and users current with an up-to-date feed of learning content from Microsoft</span></span> 
- <span data-ttu-id="b7c29-109">Создание настраиваемых списков воспроизведения и категорий, специально разработанных для потребностей пользователя</span><span class="sxs-lookup"><span data-stu-id="b7c29-109">Build custom playlists and categories crafted specifically for your user's needs</span></span>

![кг-интродуЦинг. png](media/cg-introducing.png)

## <a name="how-does-custom-learning-work"></a><span data-ttu-id="b7c29-111">Как работает пользовательское обучение?</span><span class="sxs-lookup"><span data-stu-id="b7c29-111">How does Custom Learning work?</span></span>

<span data-ttu-id="b7c29-112">Пользовательское обучение для Office 365 (особое обучение сокращено) состоит из трех частей:</span><span class="sxs-lookup"><span data-stu-id="b7c29-112">Custom Learning for Office 365 (Custom Learning for short) consists of three parts:</span></span> 
1. <span data-ttu-id="b7c29-113">динамический канал контента из каталога Microsoft Online</span><span class="sxs-lookup"><span data-stu-id="b7c29-113">a live feed of content from a Microsoft online catalog</span></span>
2. <span data-ttu-id="b7c29-114">сайт для общения с SharePoint</span><span class="sxs-lookup"><span data-stu-id="b7c29-114">a SharePoint communication site</span></span>
3. <span data-ttu-id="b7c29-115">веб-часть SharePoint</span><span class="sxs-lookup"><span data-stu-id="b7c29-115">a SharePoint web part</span></span> 

![кг-ховитворкс. png](media/cg-howitworks.png)

## <a name="requirements-and-permissions"></a><span data-ttu-id="b7c29-117">Требования и разрешения</span><span class="sxs-lookup"><span data-stu-id="b7c29-117">Requirements and Permissions</span></span>

<span data-ttu-id="b7c29-p102">Прежде чем приступить к работе с этим руководством, убедитесь, что администратор клиента SharePoint настроил настраиваемый обучающий курс. Если вы не уверены в том, что он настроен, обратитесь к администратору клиента SharePoint, чтобы проверить, установлено ли особое обучение. Кроме того, вы можете получить URL-адрес настраиваемого сайта SharePoint для обучения. Если вы являетесь администратором клиента и не установили особое обучение, ознакомьтесь с руководством по установке Office 365 Custom Learning for Office.</span><span class="sxs-lookup"><span data-stu-id="b7c29-p102">Before getting started with this guide, ensure that Custom Learning has been set up by your  SharePoint tenant administrator. If you’re not sure if it's been set up, contact your SharePoint tenant administrator to verify that Custom Learning has been installed. Also be sure to get the URL of the Custom Learning SharePoint site. If you are the Tenant Administrator and Custom Learning has not been installed, see the Custom Learning for Office 365 Installation Guide.</span></span> 

### <a name="permissions-to-install-custom-learning"></a><span data-ttu-id="b7c29-122">Разрешения на установку настраиваемого обучения</span><span class="sxs-lookup"><span data-stu-id="b7c29-122">Permissions to install Custom Learning</span></span>

- <span data-ttu-id="b7c29-123">Глобальный администратор Office 365</span><span class="sxs-lookup"><span data-stu-id="b7c29-123">Office 365 Global Administrator</span></span>
- <span data-ttu-id="b7c29-124">Администратор SharePoint</span><span class="sxs-lookup"><span data-stu-id="b7c29-124">SharePoint Administrator</span></span>

### <a name="permissions-to-use-custom-learning-administration-features"></a><span data-ttu-id="b7c29-125">Разрешения на использование настраиваемых функций администрирования обучения</span><span class="sxs-lookup"><span data-stu-id="b7c29-125">Permissions to use Custom Learning Administration features</span></span>

- <span data-ttu-id="b7c29-126">Разрешения владельца Office 365 SharePoint и владельца сайта SharePoint</span><span class="sxs-lookup"><span data-stu-id="b7c29-126">Office 365 SharePoint Administrator/SharePoint Site Owner Permissions</span></span>
- <span data-ttu-id="b7c29-127">Разрешения администратора семейства веб-сайтов SharePoint/владельца сайта SharePoint</span><span class="sxs-lookup"><span data-stu-id="b7c29-127">SharePoint Site Collection Administrator/SharePoint Site Owner Permissions</span></span>

### <a name="permissions-to-use-the-custom-learning-site-as-a-user"></a><span data-ttu-id="b7c29-128">Разрешения на использование настраиваемого сайта обучения в качестве пользователя</span><span class="sxs-lookup"><span data-stu-id="b7c29-128">Permissions to use the Custom Learning site as a user</span></span>

- <span data-ttu-id="b7c29-129">Разрешения пользователей Office 365, разрешения посетителей сайта SharePoint и выше</span><span class="sxs-lookup"><span data-stu-id="b7c29-129">Office 365 user permissions/SharePoint Site Visitor Permissions or higher</span></span>



---
author: pkrebs
ms.author: pkrebs
title: Обзор
ms.date: 02/15/2019
description: Обзор настраиваемого обучения для Office 365 для администраторов
ms.openlocfilehash: c4b9679ae5a7158306bfd53e345f8e892ab206bc
ms.sourcegitcommit: afb5502604d271f49f6d1133db9dfc499f710eec
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 02/15/2019
ms.locfileid: "30064989"
---
# <a name="overview-of-custom-learning"></a><span data-ttu-id="0379d-103">Обзор настраиваемого обучения</span><span class="sxs-lookup"><span data-stu-id="0379d-103">Overview of Custom Learning</span></span>
<span data-ttu-id="0379d-p101">В этом разделе представлено новое решение для Office 365, разработанное корпорацией Майкрософт для ускорения использования и внедрения Office 365 в пределах организации. С помощью настраиваемого обучения вы можете:</span><span class="sxs-lookup"><span data-stu-id="0379d-p101">Introducing Custom Learning for Office 365, a new solution from Microsoft designed to speed the usage and adoption of Office 365 within an organization. With Custom Learning, you can:</span></span>

- <span data-ttu-id="0379d-p102">Настройте пользовательское обучение для Office 365 в вашей среде. Изменение страниц сайта с помощью фирменного стиля и логотипа, обучающих событий и сведений о поддержке. Скрытие и отображение контента для служб и компонентов, которые не поддерживаются в вашей организации.</span><span class="sxs-lookup"><span data-stu-id="0379d-p102">Tailor Custom Learning for Office 365 to your environment. Modify site pages with your brand and logo, training events, and support info. Hide and show content for services or features that are not supported in your organization.</span></span> 
- <span data-ttu-id="0379d-109">РазРешите Майкрософт поддерживать контент и пользователей в актуальном состоянии — это динамический канал обучения, который корпорация Майкрософт хранит в актуальном состоянии.</span><span class="sxs-lookup"><span data-stu-id="0379d-109">Let Microsoft keep your content and users up-to-date – Custom Learning provides a dynamic feed of learning content that Microsoft keeps up-to-date.</span></span> 
- <span data-ttu-id="0379d-110">Создавайте категории и пользовательские списки воспроизведения, отражающие политики, процедуры и региональные параметры вашей организации, позволяющие пользователям создавать навыки с обучающими материалами, специально разработанными в соответствии с их потребностями.</span><span class="sxs-lookup"><span data-stu-id="0379d-110">Build categories and custom playlists reflecting your organization’s policies, procedures, and culture, enabling users to build skills with learning content crafted specifically to their needs.</span></span>

![кг_интродуЦинг. png](media/cg_introducing.png)

## <a name="how-does-custom-learning-word"></a><span data-ttu-id="0379d-112">Как пользовательское учебное слово?</span><span class="sxs-lookup"><span data-stu-id="0379d-112">How does Custom Learning word?</span></span>
<span data-ttu-id="0379d-113">Пользовательское обучение для Office 365 (особое обучение сокращено) состоит из трех частей:</span><span class="sxs-lookup"><span data-stu-id="0379d-113">Custom Learning for Office 365 (Custom Learning for short) consists of three parts:</span></span> 
- <span data-ttu-id="0379d-114">сайт для общения с SharePoint</span><span class="sxs-lookup"><span data-stu-id="0379d-114">a SharePoint communication site</span></span>
- <span data-ttu-id="0379d-115">веб-часть SharePoint</span><span class="sxs-lookup"><span data-stu-id="0379d-115">a SharePoint web part</span></span>
- <span data-ttu-id="0379d-116">динамический канал контента из каталога Microsoft Online</span><span class="sxs-lookup"><span data-stu-id="0379d-116">a live feed of content from a Microsoft online catalog</span></span>

![кг_ховитворкс. png](media/cg_howitworks.png)

## <a name="requirements-and-permissions"></a><span data-ttu-id="0379d-118">Требования и разрешения</span><span class="sxs-lookup"><span data-stu-id="0379d-118">Requirements and Permissions</span></span>
<span data-ttu-id="0379d-p103">Пользовательское обучение для Office 365 должно быть установлено администратором клиента вашей организации — кто, у которого есть разрешение администратора клиента. Прежде чем приступить к работе с этими процедурами настройки, описанными в этом руководстве, убедитесь, что пользовательское обучение настроено администратором клиента SharePoint. Если вы не уверены, обратитесь к администратору клиента SharePoint, чтобы проверить, установлено ли особое обучение. Кроме того, вы можете получить URL-адрес настраиваемого сайта SharePoint для обучения. Если вы являетесь администратором клиента и не установили особое обучение, ознакомьтесь с руководством по установке Office 365 Custom Learning for Office.</span><span class="sxs-lookup"><span data-stu-id="0379d-p103">Custom Learning for Office 365 must be installed by your organization’s tenant administrator - someone who has Tenant Administrator permission. Before getting started with this customization procedures covered in this guide, ensure that Custom Learning has been set up by a SharePoint tenant administrator. If you’re not sure, contact your SharePoint tenant administrator to verify that Custom Learning has been installed. Also be sure to get the URL of the Custom Learning SharePoint site. If you are the Tenant Administrator and Custom Learning has not been installed, see the Custom Learning for Office 365 Installation Guide.</span></span> 

### <a name="permissions-required-for-custom-learning"></a><span data-ttu-id="0379d-124">Разрешения, необходимые для настраиваемого обучения</span><span class="sxs-lookup"><span data-stu-id="0379d-124">Permissions required for Custom Learning</span></span> 
<span data-ttu-id="0379d-125">Ниже приведена подразделение разрешений, необходимых для установки, настройки и использования настраиваемого обучения.</span><span class="sxs-lookup"><span data-stu-id="0379d-125">Here’s a breakdown of the permissions required for installing, customizing, and using Custom Learning.</span></span> 

<span data-ttu-id="0379d-126">**Разрешения на установку настраиваемого обучения**</span><span class="sxs-lookup"><span data-stu-id="0379d-126">**Permissions to install Custom Learning**</span></span>
- <span data-ttu-id="0379d-127">Глобальный администратор Office 365</span><span class="sxs-lookup"><span data-stu-id="0379d-127">Office 365 Global Administrator</span></span>
- <span data-ttu-id="0379d-128">Администратор SharePoint</span><span class="sxs-lookup"><span data-stu-id="0379d-128">SharePoint Administrator</span></span>

<span data-ttu-id="0379d-129">**Разрешения на использование настраиваемых функций администрирования обучения**</span><span class="sxs-lookup"><span data-stu-id="0379d-129">**Permissions to use Custom Learning Administration features**</span></span>
- <span data-ttu-id="0379d-130">Разрешения владельца Office 365 SharePoint и владельца сайта SharePoint</span><span class="sxs-lookup"><span data-stu-id="0379d-130">Office 365 SharePoint Administrator/SharePoint Site Owner Permissions</span></span>
- <span data-ttu-id="0379d-131">Разрешения администратора семейства веб-сайтов SharePoint/владельца сайта SharePoint</span><span class="sxs-lookup"><span data-stu-id="0379d-131">SharePoint Site Collection Administrator/SharePoint Site Owner Permissions</span></span>

<span data-ttu-id="0379d-132">**Использование настраиваемого сайта обучения в качестве пользователя**</span><span class="sxs-lookup"><span data-stu-id="0379d-132">**To use the Custom Learning site as a user**</span></span>
- <span data-ttu-id="0379d-133">Разрешения пользователей Office 365, разрешения посетителей сайта SharePoint и выше</span><span class="sxs-lookup"><span data-stu-id="0379d-133">Office 365 user permissions/SharePoint Site Visitor Permissions or higher</span></span>
- <span data-ttu-id="0379d-134">Если вы не уверены в том, что вы предоставили необходимые разрешения, обратитесь к администратору клиента SharePoint.</span><span class="sxs-lookup"><span data-stu-id="0379d-134">If you’re not sure if you’ve been granted the necessary permissions, contact your SharePoint Tenant Administrator.</span></span>

### <a name="next-steps"></a><span data-ttu-id="0379d-135">Дальнейшие действия</span><span class="sxs-lookup"><span data-stu-id="0379d-135">Next Steps</span></span>

- [<span data-ttu-id="0379d-136">Настройка и общий доступ к спискам воспроизведения</span><span class="sxs-lookup"><span data-stu-id="0379d-136">Customize and Share Playlists</span></span>](customplaylist.md)
- [<span data-ttu-id="0379d-137">Внедрение диска</span><span class="sxs-lookup"><span data-stu-id="0379d-137">Drive Adoption</span></span>](driveadoption.md) 
---
author: pkrebs
ms.author: pkrebs
title: Настройка схем обучения
ms.date: 02/18/2019
manager: bpardi
audience: admin
ms.topic: article
description: Настройка схем обучения
ms.service: sharepoint-online
ms.openlocfilehash: a5087096ec3bd7c1194aab9dd089276fc196a736
ms.sourcegitcommit: 97e175e5ff5b6a9e0274d5ec9b39fdf7e18eb387
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/25/2021
ms.locfileid: "51999505"
---
# <a name="customize-learning-pathways"></a><span data-ttu-id="2f537-103">Настройка схем обучения</span><span class="sxs-lookup"><span data-stu-id="2f537-103">Customize learning pathways</span></span>

<span data-ttu-id="2f537-104">Пути обучения Microsoft 365 предоставляют различные способы настройки контента для организации.</span><span class="sxs-lookup"><span data-stu-id="2f537-104">Microsoft 365 learning pathways provides a variety of ways that you can customize content for your organization.</span></span> <span data-ttu-id="2f537-105">Например, вы можете:</span><span class="sxs-lookup"><span data-stu-id="2f537-105">For example, you can:</span></span>  
- <span data-ttu-id="2f537-106">Изменение путей обучения на сайте SharePoint — измените имя сайта, логотип и их.</span><span class="sxs-lookup"><span data-stu-id="2f537-106">Modify the learning pathways SharePoint site - Change the site name, logo, and them.</span></span> <span data-ttu-id="2f537-107">Измените страницу Задать вопросы и получить справку, чтобы создать собственный центр справки.</span><span class="sxs-lookup"><span data-stu-id="2f537-107">Modify the Ask Questions and Get Help page to create your own Help Center.</span></span> 
- <span data-ttu-id="2f537-108">Скрыть или показать контент, чтобы отразить службы или функции, поддерживаемые в организации</span><span class="sxs-lookup"><span data-stu-id="2f537-108">Hide or show content to reflect the services or features supported in your organization</span></span> 
- <span data-ttu-id="2f537-109">Создание пользовательских списков воспроизведения и подкатегорий, созданных специально для потребностей пользователя</span><span class="sxs-lookup"><span data-stu-id="2f537-109">Build custom playlists and subcategories crafted specifically for your user's needs</span></span>
- <span data-ttu-id="2f537-110">Создайте страницы с контентом, фильтруемым для поддержки бизнес-результатов, таких как внедрение Microsoft Teams, outlook mobile или совместная работа с Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="2f537-110">Build landing pages with content filtered to support business outcomes, such as driving the adoption of Microsoft Teams, Outlook mobile, or working more collaboratively with Microsoft 365.</span></span>

![Коллекция фотографий общих путей обучения Майкрософт.](media/cg-introducing.png)

## <a name="requirements-and-permissions"></a><span data-ttu-id="2f537-112">Требования и разрешения</span><span class="sxs-lookup"><span data-stu-id="2f537-112">Requirements and Permissions</span></span>

<span data-ttu-id="2f537-113">Перед началом работы с руководством По настройке путей обучения убедитесь, что пути обучения были настроены администратором клиента SharePoint.</span><span class="sxs-lookup"><span data-stu-id="2f537-113">Before getting started with the Customize learning pathways guidance, ensure that learning pathways has been set up by your SharePoint Tenant Administrator.</span></span> <span data-ttu-id="2f537-114">Если вы не уверены, была ли она настроена, обратитесь к администратору клиента SharePoint, чтобы убедиться, что были предусмотрены пути обучения.</span><span class="sxs-lookup"><span data-stu-id="2f537-114">If you’re not sure if it's been set up, contact your SharePoint tenant administrator to verify that learning pathways has been provisioned.</span></span> <span data-ttu-id="2f537-115">Кроме того, обязательно получите URL-адрес сайта SharePoint для путей обучения.</span><span class="sxs-lookup"><span data-stu-id="2f537-115">Also be sure to get the URL of the learning pathways SharePoint site.</span></span> <span data-ttu-id="2f537-116">Если вы администратор клиента и пути обучения не были предусмотрены, см. в пункте [Подготовка путей обучения.](custom_provision.md)</span><span class="sxs-lookup"><span data-stu-id="2f537-116">If you are the Tenant Administrator and learning pathways has not been provisioned, see [Provision learning pathways](custom_provision.md).</span></span> 

### <a name="permissions-to-provision-learning-pathways"></a><span data-ttu-id="2f537-117">Разрешения на предоставление путей обучения</span><span class="sxs-lookup"><span data-stu-id="2f537-117">Permissions to provision learning pathways</span></span>

- <span data-ttu-id="2f537-118">Администратор клиента, также известный как Глобальный администратор Office 365</span><span class="sxs-lookup"><span data-stu-id="2f537-118">Tenant Administrator, also known as Office 365 Global Administrator</span></span>
- <span data-ttu-id="2f537-119">Администратор семейства веб-сайтов SharePoint с разрешениями владельца на сайте</span><span class="sxs-lookup"><span data-stu-id="2f537-119">SharePoint Site Collection Administrator with Owner permissions on the site</span></span>

### <a name="permissions-to-use-learning-pathways-administration-features"></a><span data-ttu-id="2f537-120">Разрешения на использование функций администрирования путей обучения</span><span class="sxs-lookup"><span data-stu-id="2f537-120">Permissions to use learning pathways Administration features</span></span>

- <span data-ttu-id="2f537-121">Администратор семейства веб-сайтов</span><span class="sxs-lookup"><span data-stu-id="2f537-121">Site Collection Administrator</span></span>
- <span data-ttu-id="2f537-122">Разрешения владельца или участника SharePoint</span><span class="sxs-lookup"><span data-stu-id="2f537-122">SharePoint Owner or Member permissions</span></span>

### <a name="permissions-to-use-the-learning-pathways-site-as-a-user"></a><span data-ttu-id="2f537-123">Разрешения на использование сайта путей обучения в качестве пользователя</span><span class="sxs-lookup"><span data-stu-id="2f537-123">Permissions to use the learning pathways site as a user</span></span>

- <span data-ttu-id="2f537-124">Разрешения пользователя Office 365 и разрешения посетителя сайта SharePoint или выше</span><span class="sxs-lookup"><span data-stu-id="2f537-124">Office 365 user permissions/SharePoint Site Visitor permissions or higher</span></span>

## <a name="get-started-with-customization"></a><span data-ttu-id="2f537-125">Начало работы с настройками</span><span class="sxs-lookup"><span data-stu-id="2f537-125">Get started with customization</span></span>
<span data-ttu-id="2f537-126">После получения необходимых разрешений для настройки сайта и веб-части пришло время начать процесс настройки.</span><span class="sxs-lookup"><span data-stu-id="2f537-126">Once you've ensured you have the necessary permissions to customize the site and web part, it's time to get started with the customization process.</span></span> 

- <span data-ttu-id="2f537-127">Чтобы начать работу, [см. на сайте "Пути обучения".](custom_goto.md)</span><span class="sxs-lookup"><span data-stu-id="2f537-127">To get started, see [Go to the learning pathways site](custom_goto.md).</span></span>
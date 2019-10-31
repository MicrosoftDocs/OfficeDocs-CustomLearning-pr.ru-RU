---
author: pkrebs
ms.author: pkrebs
title: Настройка путей обучения
ms.date: 02/18/2019
description: Настройка путей обучения
ms.openlocfilehash: 15d782455204cf043937bec03041a85abc9e4ee3
ms.sourcegitcommit: 3b8896c81ad2adbcfdbda658482847af5fccb264
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/30/2019
ms.locfileid: "37886642"
---
# <a name="customize-learning-pathways"></a><span data-ttu-id="29a22-103">Настройка путей обучения</span><span class="sxs-lookup"><span data-stu-id="29a22-103">Customize learning pathways</span></span>

<span data-ttu-id="29a22-104">Microsoft 365 Learning путей предоставляет различные способы настройки контента для Организации.</span><span class="sxs-lookup"><span data-stu-id="29a22-104">Microsoft 365 learning pathways provides a variety of ways that you can customize content for your organization.</span></span> <span data-ttu-id="29a22-105">Например, вы можете:</span><span class="sxs-lookup"><span data-stu-id="29a22-105">For example, you can:</span></span>  
- <span data-ttu-id="29a22-106">Изменение сайта SharePoint "пути для обучения" — изменение имени сайта, логотипа и его имени.</span><span class="sxs-lookup"><span data-stu-id="29a22-106">Modify the learning pathways SharePoint site - Change the site name, logo, and them.</span></span> <span data-ttu-id="29a22-107">Измените страницу Ask вопросы и получение справки, чтобы создать собственный центр справки.</span><span class="sxs-lookup"><span data-stu-id="29a22-107">Modify the Ask Questions and Get Help page to create your own Help Center.</span></span> 
- <span data-ttu-id="29a22-108">Скрытие или отображение контента для отображения служб и компонентов, поддерживаемых в Организации</span><span class="sxs-lookup"><span data-stu-id="29a22-108">Hide or show content to reflect the services or features supported in your organization</span></span> 
- <span data-ttu-id="29a22-109">Создание настраиваемых списков воспроизведения и подкатегорий, специально разработанных для потребностей пользователя</span><span class="sxs-lookup"><span data-stu-id="29a22-109">Build custom playlists and subcategories crafted specifically for your user's needs</span></span>
- <span data-ttu-id="29a22-110">Создавайте целевые страницы с контентом, отфильтрованным для поддержки бизнес-результатов, таких как внедрение Microsoft Teams, Outlook Mobile или совместная работа с Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="29a22-110">Build landing pages with content filtered to support business outcomes, such as driving the adoption of Microsoft Teams, Outlook mobile, or working more collaboratively with Microsoft 365.</span></span>

![кг-интродуЦинг. png](media/cg-introducing.png)

## <a name="requirements-and-permissions"></a><span data-ttu-id="29a22-112">Требования и разрешения</span><span class="sxs-lookup"><span data-stu-id="29a22-112">Requirements and Permissions</span></span>

<span data-ttu-id="29a22-113">Прежде чем приступить к работе с рекомендациями по настройке путей для обучения, убедитесь, что администратор клиента SharePoint настроил пути для обучения.</span><span class="sxs-lookup"><span data-stu-id="29a22-113">Before getting started with the Customize learning pathways guidance, ensure that learning pathways has been set up by your SharePoint Tenant Administrator.</span></span> <span data-ttu-id="29a22-114">Если вы не уверены в том, что он настроен, обратитесь к администратору клиента SharePoint, чтобы проверить, подготовлены ли пути для обучения.</span><span class="sxs-lookup"><span data-stu-id="29a22-114">If you’re not sure if it's been set up, contact your SharePoint tenant administrator to verify that learning pathways has been provisioned.</span></span> <span data-ttu-id="29a22-115">Кроме того, вы можете получить URL-адрес сайта SharePoint "пути для обучения".</span><span class="sxs-lookup"><span data-stu-id="29a22-115">Also be sure to get the URL of the learning pathways SharePoint site.</span></span> <span data-ttu-id="29a22-116">Если вы являетесь администратором клиента и его пути для обучения не подготовлены, ознакомьтесь со статьей [Подготовка путей обучения](custom_provision.md).</span><span class="sxs-lookup"><span data-stu-id="29a22-116">If you are the Tenant Administrator and learning pathways has not been provisioned, see [Provision learning pathways](custom_provision.md).</span></span> 

### <a name="permissions-to-provision-learning-pathways"></a><span data-ttu-id="29a22-117">Разрешения для подготовки путей обучения</span><span class="sxs-lookup"><span data-stu-id="29a22-117">Permissions to provision learning pathways</span></span>

- <span data-ttu-id="29a22-118">Администратор клиента, который также называется глобальным администратором Office 365</span><span class="sxs-lookup"><span data-stu-id="29a22-118">Tenant Administrator, also known as Office 365 Global Administrator</span></span>
- <span data-ttu-id="29a22-119">Администратор семейства веб-сайтов SharePoint с разрешениями владельца для сайта</span><span class="sxs-lookup"><span data-stu-id="29a22-119">SharePoint Site Collection Administrator with Owner permissions on the site</span></span>

### <a name="permissions-to-use-learning-pathways-administration-features"></a><span data-ttu-id="29a22-120">Разрешения для использования средств администрирования путей обучения</span><span class="sxs-lookup"><span data-stu-id="29a22-120">Permissions to use learning pathways Administration features</span></span>

- <span data-ttu-id="29a22-121">Администратор семейства веб-сайтов</span><span class="sxs-lookup"><span data-stu-id="29a22-121">Site Collection Administrator</span></span>
- <span data-ttu-id="29a22-122">Разрешения владельца или члена SharePoint</span><span class="sxs-lookup"><span data-stu-id="29a22-122">SharePoint Owner or Member permissions</span></span>

### <a name="permissions-to-use-the-learning-pathways-site-as-a-user"></a><span data-ttu-id="29a22-123">Разрешения на использование сайта обучающих путей в качестве пользователя</span><span class="sxs-lookup"><span data-stu-id="29a22-123">Permissions to use the learning pathways site as a user</span></span>

- <span data-ttu-id="29a22-124">Разрешения пользователей Office 365, разрешения посетителей сайта SharePoint и выше</span><span class="sxs-lookup"><span data-stu-id="29a22-124">Office 365 user permissions/SharePoint Site Visitor permissions or higher</span></span>

## <a name="get-started-with-customization"></a><span data-ttu-id="29a22-125">Начало работы с настройками</span><span class="sxs-lookup"><span data-stu-id="29a22-125">Get started with customization</span></span>
<span data-ttu-id="29a22-126">После того, как вы убедитесь, что у вас есть необходимые разрешения на настройку сайта и веб-части, необходимо начать процесс настройки.</span><span class="sxs-lookup"><span data-stu-id="29a22-126">Once you've ensured you have the necessary permissions to customize the site and web part, it's time to get started with the customization process.</span></span> 

- <span data-ttu-id="29a22-127">Чтобы приступить к работе, ознакомьтесь со статьей [Переход на сайт пути для обучения](custom_goto.md).</span><span class="sxs-lookup"><span data-stu-id="29a22-127">To get started, see [Go to the learning pathways site](custom_goto.md).</span></span>
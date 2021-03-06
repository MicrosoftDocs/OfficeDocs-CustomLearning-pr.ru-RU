---
author: karuanag
ms.author: karuanag
manager: alexb
title: Настройка и совместное делиться списками воспроизведения
ms.date: 02/10/2019
description: Создание пользовательских списков воспроизведения из существующего контента или новых страниц SharePoint
ms.service: sharepoint-online
audience: itpro
ms.topic: article
ms.openlocfilehash: 31a0e5524181d26f4d62ae7206636c9e553b6f8f
ms.sourcegitcommit: 97e175e5ff5b6a9e0274d5ec9b39fdf7e18eb387
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/25/2021
ms.locfileid: "52000215"
---
# <a name="customize-and-share-playlists"></a>Настройка и совместное делиться списками воспроизведения

## <a name="create-a-playlist"></a>Создание списка воспроизведения

Список воспроизведения — это соответствие "активам". "Актив" — это страница SharePoint или существующий элемент обучающего контента Майкрософт. При создании списка воспроизведения вы выбираете ресурсы, которые вместе создают путь к обучению для пользователя.  

Преимущество добавления страниц SharePoint состоит в том, что вы можете создавать страницы SharePoint с помощью видео или видео на YouTube, которые будут организованы в вашей организации. Вы также можете создавать страницы с формами или другим контентом Office 365.  

#### <a name="step-1-create-a-sharepoint-page-for-your-playlist"></a>Шаг 1. Создание страницы SharePoint для списка воспроизведения
В этом примере сначала создадим страницу SharePoint, которая будет добавлена в список воспроизведения. Мы создадим страницу с веб-частью видео YouTube и веб-частью Text.  Эти инструкции предполагают, что вы используете службу SharePoint Online. 

#### <a name="create-a-new-page"></a>Создайте новую страницу
1.  Выберите меню Параметры > содержимого сайта > страниц сайта > страницу > сайта.
2.  В области заголовка введите Использование командного окна Teams
3.  Выберите добавить новый раздел, а затем выберите два столбца.

![добавление двух столбцов](media/clo365addtwocolumn.png)

4.  В левом окне выберите Добавить новую веб-часть, а затем выберите Embed. 
5.  В веб-браузере перейдите к этому URL-адресу https://youtu.be/wYrRCRphrp0 и получите встраив код для видео. 
6.  В веб-части SharePoint выберите Добавить код встраить, а затем вложить его в поле Embed. 
7.  В правом окне выберите Добавить новую веб-часть, а затем выберите Текст. 
8.  В веб-браузере перейдите к этому URL-адресу и https://support.office.com/article/13c4e429-7324-4886-b377-5dbed539193b скопируйте try it! Инструкции со страницы и вклейте их в текстовую веб-часть. Ваша страница должна выглядеть следующим образом. 
![Встраить страницу](media/clo365teamscommandbox.png)
9.  Нажмите **кнопку Опубликовать,** а затем скопируйте URL-адрес страницы и вклеите ее в Блокнот

#### <a name="step-2-create-the-playlist"></a>Шаг 2. Создание списка воспроизведения

1. Перейдите на **страницу Администрирование пользовательского** обучения в вашем опыте работы с сайтом.
![Экран, на котором вы выбираете настраиваемый администрирование обучения.](media/custom_admin.png)
1. **Убедитесь, что выбрана** категория 
1. Щелкните категорию, в которой должен появиться новый плейлист
1. Рядом с именем категории щелкните окно плюс символ с параметром ![ Category и выделенным знаком Plus.](media/custom_addplay.png)

1. Заполните значения, как показано в примере ниже, и выберите **Создать**. 
![Страница, на которой вы вводите сведения о списке воспроизведения.](media/custom_details.png)
- **Название** — отображение имени списка воспроизведения
- **Описание** . Сведения о том, что будет известно
- **Категория** — предварительно отбираемая в зависимости от первоначального выбора
- **Sub Category** - Preselected based on your intial selection
- **Технология** — выберите применимое
- **Уровень** - Beginner, Intermidate или Advanced
- **Аудитория** . Это позволяет нацелить контент на основе предварительно определенного списка ролей, предоставляемых Корпорацией Майкрософт.

6. Щелкните **сохранить деталь**

> [!TIP]
> Вы можете настроить образ значка для списка воспроизведения.  Щелкните значок изображения и вставьте URL-адрес ранее загруженного изображения.  Убедитесь, что изображение находится в коллекции настраиваемого сайта обучения или в другом расположении, чтобы все пользователи получили доступ к файлу.  
![Выберите окно изображения.](media/custom_image.png)

#### <a name="step-3-add-assets-to-the-playlist"></a>Шаг 3. Добавление активов в список воспроизведения
На этом этапе в список воспроизведения будут добавлены существующие активы из Microsoft и страница SharePoint, созданная вами. 

1. После сэкономленных сведений для списка воспроизведения можно использовать поиск существующих активов.
1. **Введите в любом термине** поиска список предопределяемых активов, доступных из других списков воспроизведения. **Щелкните имя актива,** чтобы включить его в новый плейлист.<br/>
![Страница активов playlist](media/custom_slist.png)

Вы также можете добавить страницу SharePoint, созданную ранее, или создать ее с нуля в этом опыте.

1. Щелкните параметр **New Asset** в диалоговом окте "Активы playlist".
1. Дайте вашему активу **название**. После вступив, будут отображаться дополнительные параметры.
![Форма, в которой вы вводите название и дополнительные сведения.](media/custom_newpage.png)
1. Теперь вы можете создать новую страницу активов в SharePoint Online или ввести URL-адрес существующей страницы, чтобы добавить ее в пользовательский список воспроизведения. 
1. **Поля категории,** **sub Category** и **Technology** будут предварительно заполнены в зависимости от предыдущих выборов для этого списка воспроизведения.
1. Сделайте соответствующие выборки для уровня и аудитории для этого отдельного актива.  
1. Нажмите **кнопку Сохранить актив,** чтобы добавить его в настраиваемый список воспроизведения
1. Повторите эти действия, поиск или добавление отдельных страниц до завершения списка воспроизведения. 
1. Нажмите **кнопку Закрыть список воспроизведения,** чтобы сохранить

Ваш плейлист с этим содержимым теперь будет доступен в любом месте, где вы установили или встроите веб-часть настраиваемой учебной системы. 

> [!NOTE]
> Если вы допустили ошибку после закрытия списка воспроизведения, вы можете удалить его из категории, щелкнув X рядом с именем плейлиста.  

#### <a name="things-to-think-about"></a>Что нужно думать

Настраиваемые списки воспроизведения можно использовать для оказания помощи конечным пользователям в различных задачах.  У вас есть форма запроса на время?  Форма для запроса оборудования?  Все существующие средства подготовки можно запрограммированы на опыт.  

## <a name="share-playlists"></a>Share Playlists

1. Перейдите к любому списку воспроизведения в веб-части или на сайте.
1. В верхнем левом углу вы увидите три значка
1. Щелкните значок, представляющий ссылку
1. Скопируйте URL-адрес на экран плейлиста, на ![ котором щелкните Скопируйте рядом с URL-адресом.](media/share.png)
Этот URL-адрес теперь можно вставить в навигацию по сайту или использовать в других сообщениях, чтобы вывести сотрудников непосредственно в этот плейлист. 

### <a name="next-steps---drive-adoption"></a>Дальнейшие действия — [принятие диска](driveadoption.md)

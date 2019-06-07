---
title: Рівні дозволів на сайті SharePoint
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 356fef8e02f2c1fd9d209c68194685bb0acaa367
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 06/07/2019
ms.locfileid: "34760713"
---
# <a name="sharepoint-designer-connection-issues"></a><span data-ttu-id="f3ce8-102">SharePoint Designer і FTP-клієнти</span><span class="sxs-lookup"><span data-stu-id="f3ce8-102">SharePoint Designer connection issues</span></span> 

<span data-ttu-id="f3ce8-103">Якщо SharePoint Designer переживає питання, підключення до сайтів SharePoint, будь ласка, спроба такі спільні рішення.</span><span class="sxs-lookup"><span data-stu-id="f3ce8-103">If SharePoint Designer is experiencing connection issues to SharePoint sites, please attempt the following common solutions.</span></span>

<span data-ttu-id="f3ce8-104">Крок 1: Перевірте, чи оновлено SharePoint Designer.</span><span class="sxs-lookup"><span data-stu-id="f3ce8-104">Step 1: Verify SharePoint Designer is updated.</span></span>

- [<span data-ttu-id="f3ce8-105">SharePoint Designer 2013</span><span class="sxs-lookup"><span data-stu-id="f3ce8-105">SharePoint Designer 2013</span></span>](https://www.microsoft.com/download/details.aspx?id=35491)

- [<span data-ttu-id="f3ce8-106">SharePoint Designer пакета оновлень 1 (SP1)</span><span class="sxs-lookup"><span data-stu-id="f3ce8-106">SharePoint Designer Service Pack 1 (SP1)</span></span>](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1)

- [<span data-ttu-id="f3ce8-107">Оновлення для SharePoint Designer 2013 (KB3114721)</span><span class="sxs-lookup"><span data-stu-id="f3ce8-107">Update for SharePoint Designer 2013 (KB3114721)</span></span>](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721)

<span data-ttu-id="f3ce8-108">Крок 2: Очистити кеш локальних файлів</span><span class="sxs-lookup"><span data-stu-id="f3ce8-108">Step 2: Clear the local cache files</span></span>

- <span data-ttu-id="f3ce8-109">Закрийте SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="f3ce8-109">Close SharePoint Designer 2013.</span></span>

- <span data-ttu-id="f3ce8-110">На локальному комп'ютері перейдіть до таких папок, щоб видалити кешованих файлів.</span><span class="sxs-lookup"><span data-stu-id="f3ce8-110">On the local computer, browse to the following folders to remove cached files.</span></span>

- <span data-ttu-id="f3ce8-111">Натисніть кнопку Пуск, виконати і видалити всі файли, знайти під кожним з в нижче розташуваннях.</span><span class="sxs-lookup"><span data-stu-id="f3ce8-111">Click Start, Run and delete all files found under each of the below locations.</span></span>

<span data-ttu-id="f3ce8-112">Сервер %AppData%\Microsoft\Web Extensions\Cache %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span><span class="sxs-lookup"><span data-stu-id="f3ce8-112">%APPDATA%\Microsoft\Web Server Extensions\Cache %APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache %USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span></span>

<span data-ttu-id="f3ce8-113">Відкрити SharePoint Designer 2013 і введіть обліковий запис знову, щоб побачити, якщо вона працює.</span><span class="sxs-lookup"><span data-stu-id="f3ce8-113">Open SharePoint Designer 2013 and enter the account again to see if it works.</span></span>

<span data-ttu-id="f3ce8-114">Крок 3: [ввімкнення сучасних автентифікації для Office 2013 на пристроях Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide)</span><span class="sxs-lookup"><span data-stu-id="f3ce8-114">Step 3: [Enable Modern Authentication for Office 2013 on Windows Devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication?redirectSourcePath=/article/Enable-Modern-Authentication-for-Office-2013-on-Windows-devices-7dc1c01a-090f-4971-9677-f1b192d6c910&view=o365-worldwide)</span></span>

<span data-ttu-id="f3ce8-115">Крок 4: Адміністратори повинні дозволити користувацький скрипт дозволити підключення застосунку SharePoint Designer.</span><span class="sxs-lookup"><span data-stu-id="f3ce8-115">Step 4: Administrators will need to Allow Custom Script to allow the SharePoint Designer connection.</span></span>

<span data-ttu-id="f3ce8-116">Докладно процедуру, приклади і міркування в розділі [дозволити або заборонити власний сценарій](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span><span class="sxs-lookup"><span data-stu-id="f3ce8-116">For detailed steps, examples and considerations see [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span></span>



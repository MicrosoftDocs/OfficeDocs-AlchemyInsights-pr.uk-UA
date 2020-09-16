---
title: Проблеми з підключенням до програми SharePoint Designer
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: f2b1b6b4-10c9-4e83-b9cb-529a0b8a3c55
ms.openlocfilehash: 997ba3de58485d4fe6d24b926c33348378af8cd3
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 09/14/2020
ms.locfileid: "47727192"
---
# <a name="sharepoint-designer-connection-issues"></a><span data-ttu-id="27b16-102">Проблеми з підключенням до програми SharePoint Designer</span><span class="sxs-lookup"><span data-stu-id="27b16-102">SharePoint Designer connection issues</span></span> 

<span data-ttu-id="27b16-103">Якщо у програмі SharePoint Designer виникли проблеми з підключенням до сайтів SharePoint, спробуйте виконати наведені нижче поширені рішення.</span><span class="sxs-lookup"><span data-stu-id="27b16-103">If SharePoint Designer is experiencing connection issues to SharePoint sites, please try the following common solutions.</span></span>

<span data-ttu-id="27b16-104">Крок 1. Переконайтеся, що SharePoint Designer 2013 оновлюється за допомогою [служби SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) і [2 серпня 2016 оновлення для SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).</span><span class="sxs-lookup"><span data-stu-id="27b16-104">Step 1: Verify that SharePoint Designer 2013 is updated with [SharePoint Designer Service Pack 1](https://support.microsoft.com/help/2817441/description-of-microsoft-sharepoint-designer-2013-service-pack-1-sp1) and the [August 2, 2016 Update for SharePoint Designer 2013](https://support.microsoft.com/help/3114721/august-2-2016-update-for-sharepoint-designer-2013-kb3114721).</span></span>



<span data-ttu-id="27b16-105">Крок 2: очищення локальних файлів кешу:</span><span class="sxs-lookup"><span data-stu-id="27b16-105">Step 2: Clear the local cache files:</span></span>

1. <span data-ttu-id="27b16-106">Закрийте програму SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="27b16-106">Close SharePoint Designer 2013.</span></span>

2. <span data-ttu-id="27b16-107">На локальному комп'ютері видаліть усі файли, знайдені в кожній із наведених нижче папок.</span><span class="sxs-lookup"><span data-stu-id="27b16-107">On the local computer, remove all files found in each of the following folders.</span></span>

    - <span data-ttu-id="27b16-108">%AppData%\microsoft\ веб-сервер Extensions\Cache</span><span class="sxs-lookup"><span data-stu-id="27b16-108">%APPDATA%\Microsoft\Web Server Extensions\Cache</span></span>
    - <span data-ttu-id="27b16-109">%AppData%\microsoft\ SharePoint Designer\ProxyAssemblyCache</span><span class="sxs-lookup"><span data-stu-id="27b16-109">%APPDATA%\Microsoft\SharePoint Designer\ProxyAssemblyCache</span></span>
    - <span data-ttu-id="27b16-110">%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span><span class="sxs-lookup"><span data-stu-id="27b16-110">%USERPROFILE%\AppData\Local\Microsoft\WebsiteCache</span></span>

3. <span data-ttu-id="27b16-111">Відкрийте програму SharePoint Designer 2013 і знову вкажіть обліковий запис, щоб дізнатися, чи це працює.</span><span class="sxs-lookup"><span data-stu-id="27b16-111">Open SharePoint Designer 2013 and enter the account again to see if it works.</span></span>

<span data-ttu-id="27b16-112">Крок 3: [Увімкнення сучасної автентифікації для Office 2013 на пристроях з ОС Windows](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="27b16-112">Step 3: [Enable Modern Authentication for Office 2013 on Windows Devices](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).</span></span>

<span data-ttu-id="27b16-113">Крок 4: адміністратори повинні **дозволити настроюваний сценарій** у настройках центру адміністрування SharePoint, щоб дозволити підключення конструктора SharePoint.</span><span class="sxs-lookup"><span data-stu-id="27b16-113">Step 4: Administrators will need to **Allow Custom Script** in the SharePoint Admin Center settings to allow the SharePoint Designer connection.</span></span> <span data-ttu-id="27b16-114">Дізнайтеся [, як дозволити або заборонити настроюваний сценарій](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) для отримання додаткових відомостей.</span><span class="sxs-lookup"><span data-stu-id="27b16-114">See [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) for more information.</span></span>



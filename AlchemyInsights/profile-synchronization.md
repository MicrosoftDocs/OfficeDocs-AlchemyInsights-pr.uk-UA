---
title: Синхронізація профілів
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6b695be8-eaf5-44ff-b0ae-1e0d89e7ab36
ms.openlocfilehash: eee1080a95955332e205db3852381e39aaf5ae0e
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 09/15/2020
ms.locfileid: "47801790"
---
# <a name="when-do-my-profile-changes-sync-to-the-sharepoint-user-profile-application"></a><span data-ttu-id="918f6-102">Коли мій профіль змінює синхронізацію в застосунку профілю користувача SharePoint?</span><span class="sxs-lookup"><span data-stu-id="918f6-102">When do my profile changes sync to the SharePoint User Profile Application?</span></span>

<span data-ttu-id="918f6-103">Служба SharePoint Online використовує завдання таймера імпорту Active Directory (імпорт оголошення), щоб імпортувати користувачів і групи в програму профілю користувача.</span><span class="sxs-lookup"><span data-stu-id="918f6-103">SharePoint Online uses the Active Directory Import timer job (AD Import) to import users and groups into the User Profile Application.</span></span> 
  
1. <span data-ttu-id="918f6-104">Імпорт AD синхронізує зміни з магазину каталогів SharePoint Online до застосунку профілю користувача.</span><span class="sxs-lookup"><span data-stu-id="918f6-104">AD Import syncs changes from the SharePoint Online Directory Store to the User Profile Application.</span></span> <span data-ttu-id="918f6-105">Ці зміни обробляються в партіях.</span><span class="sxs-lookup"><span data-stu-id="918f6-105">These changes are processed in batches.</span></span>
    
2. <span data-ttu-id="918f6-106">Завдання таймера запускається, доки зміни не буде синхронізовано.</span><span class="sxs-lookup"><span data-stu-id="918f6-106">The timer job runs until the changes are synced.</span></span>
    
> [!NOTE]
> <span data-ttu-id="918f6-107">Час, потрібний для виконання завдання, залежить від кількості змін, внесених до процесу.</span><span class="sxs-lookup"><span data-stu-id="918f6-107">The time it takes the job to run depends on the number of changes to process.</span></span> <span data-ttu-id="918f6-108">Велика кількість змін триває довше.</span><span class="sxs-lookup"><span data-stu-id="918f6-108">A large number of changes takes longer.</span></span> <span data-ttu-id="918f6-109">Угода про рівень служби (SLA) заявляє, що змінення користувача в каталозі SharePoint Online буде відображено в програмі профілю користувача протягом 24 годин.</span><span class="sxs-lookup"><span data-stu-id="918f6-109">The Service Level Agreement (SLA) states that a change to a user in the SharePoint Online Directory will be reflected in the User Profile Application in 24 hours.</span></span> 
  
[<span data-ttu-id="918f6-110">Докладні відомості про синхронізацію профілів користувачів у службі SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="918f6-110">More info about user profile sync in SharePoint Online</span></span>](https://go.microsoft.com/fwlink/?linkid=875671)
  


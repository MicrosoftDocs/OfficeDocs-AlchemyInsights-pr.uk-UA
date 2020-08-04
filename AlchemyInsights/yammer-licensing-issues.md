---
title: Проблеми ліцензування Yammer
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/14/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5900"
- "9003071"
ms.openlocfilehash: 6d9b2126dc1ed90968738ddb2e249dce9857f1db
ms.sourcegitcommit: b677b85395b7244b2bf2b753468b696b4cf27c8d
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 07/16/2020
ms.locfileid: "45148429"
---
# <a name="yammer-licensing-issues"></a><span data-ttu-id="c070a-102">Проблеми ліцензування Yammer</span><span class="sxs-lookup"><span data-stu-id="c070a-102">Yammer licensing issues</span></span>

<span data-ttu-id="c070a-103">Усі користувачі повинні мати ліцензію на використання служби Yammer Enterprise, але за промовчанням Yammer не вимагає, щоб користувачі мали ліцензію на доступ до служби.</span><span class="sxs-lookup"><span data-stu-id="c070a-103">All users must have a license to use the Yammer Enterprise service, but by default Yammer does not require that users have a license to access the service.</span></span> <span data-ttu-id="c070a-104">Коли адміністратор змінює параметр для блокування користувачів Microsoft 365 без ліцензій Yammer, користувачі, які не призначено ліцензією Yammer Enterprise, не можуть отримати доступ до служби Yammer.</span><span class="sxs-lookup"><span data-stu-id="c070a-104">When an administrator changes the setting to block Microsoft 365 users without Yammer licenses, users not assigned a Yammer Enterprise license can't access the Yammer service.</span></span> <span data-ttu-id="c070a-105">Щоб отримати додаткові відомості див. [керування ліцензіями користувача Yammer в Office 365](https://docs.microsoft.com/yammer/manage-yammer-users/manage-yammer-licenses-in-office-365)</span><span class="sxs-lookup"><span data-stu-id="c070a-105">For more info, see [Manage Yammer user licenses in Office 365](https://docs.microsoft.com/yammer/manage-yammer-users/manage-yammer-licenses-in-office-365)</span></span> 

<span data-ttu-id="c070a-106">Після того, як ліцензії, видаляються з користувачів, Yammer плитка більше не відображається, а також інші служби, можна використовувати ліцензії видалення приховати функції.</span><span class="sxs-lookup"><span data-stu-id="c070a-106">When licenses are removed from users, the Yammer tile is no longer displayed, and other services can use license removal to hide features.</span></span> <span data-ttu-id="c070a-107">В інших випадках функції все ще можуть з'являтися, але вимагають призначення ліцензії для роботи.</span><span class="sxs-lookup"><span data-stu-id="c070a-107">In other cases, features can still appear but require licence assignment to operate.</span></span>  

<span data-ttu-id="c070a-108">**Ліцензія не оновлюється для користувача**</span><span class="sxs-lookup"><span data-stu-id="c070a-108">**License is not getting updated for the user**</span></span>  

<span data-ttu-id="c070a-109">Іноді користувачеві призначається ліцензія, але до цих пір не вдається отримати доступ до Yammer.</span><span class="sxs-lookup"><span data-stu-id="c070a-109">Occasionally, a user is assigned a license but is still unable to access Yammer.</span></span> <span data-ttu-id="c070a-110">Затримки частіше виникають під час виконання завдання масового ліцензування.</span><span class="sxs-lookup"><span data-stu-id="c070a-110">Delays are more likely to occur when a mass license assignment is in progress.</span></span> <span data-ttu-id="c070a-111">Користувачі Yammer можуть не оновлюватись в тому самому порядку, що й ліцензії змінюються в Azure AD, оскільки система працює асинхронно.</span><span class="sxs-lookup"><span data-stu-id="c070a-111">Yammer users might not be updated in the same order as licenses are changed in Azure AD because the system runs asynchronously.</span></span> <span data-ttu-id="c070a-112">Зачекайте до 24 годин, перш ніж відкрити справу підтримки, щоб повідомити про проблеми з синхронізацією ліцензій.</span><span class="sxs-lookup"><span data-stu-id="c070a-112">Wait up to 24 hours before opening a support case to report license sync issues.</span></span>  

<span data-ttu-id="c070a-113">**Масове призначення ліцензії**</span><span class="sxs-lookup"><span data-stu-id="c070a-113">**Bulk licence assignment**</span></span>  

<span data-ttu-id="c070a-114">Ліцензії можна призначити через центр адміністрування або сценаріїв PowerShell.</span><span class="sxs-lookup"><span data-stu-id="c070a-114">Licenses can be assigned through the admin center or PowerShell scripting.</span></span> <span data-ttu-id="c070a-115">Щоб отримати додаткові відомості див. [призначте ліцензії користувачам](https://docs.microsoft.com/microsoft-365/admin/manage/assign-licenses-to-users) і [призначте ліцензії для облікових записів користувачів за допомогою Office 365 PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/assign-licenses-to-user-accounts-with-office-365-powershell).</span><span class="sxs-lookup"><span data-stu-id="c070a-115">For more info, see [Assign licenses to users](https://docs.microsoft.com/microsoft-365/admin/manage/assign-licenses-to-users) and [Assign licenses to user accounts with Office 365 PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/assign-licenses-to-user-accounts-with-office-365-powershell).</span></span> 

<span data-ttu-id="c070a-116">Служба підтримки Microsoft не надає допомоги у створенні сценаріїв, але документація на призначення ліцензії Yammer доступна.</span><span class="sxs-lookup"><span data-stu-id="c070a-116">Microsoft Support does not provide assistance with creating scripts, but documentation on Yammer license assignment is available.</span></span> <span data-ttu-id="c070a-117">Для отримання додаткових відомостей див. [керування ліцензіями Yammer за допомогою оболонки Windows PowerShell](https://docs.microsoft.com/yammer/manage-yammer-users/manage-yammer-licenses-in-office-365#manage-yammer-licenses-by-using-windows-powershell).</span><span class="sxs-lookup"><span data-stu-id="c070a-117">For more info, see [Manage Yammer licenses by using Windows PowerShell](https://docs.microsoft.com/yammer/manage-yammer-users/manage-yammer-licenses-in-office-365#manage-yammer-licenses-by-using-windows-powershell).</span></span>
---
title: Створення сайту SharePoint
ms.author: kirks
author: Techwriter40
ms.date: 1/16/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1386"
- "2303"
- "5200004"
ms.assetid: e62b9f80-b017-42dc-9464-f4e32c19d6c9
ms.openlocfilehash: 022f572aadae3b4d9f6665f9f8be871d79b51817
ms.sourcegitcommit: f81c56dd4ae7cb2eedc383dd671b9012f3089286
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 07/19/2019
ms.locfileid: "35802987"
---
# <a name="create-a-sharepoint-site"></a><span data-ttu-id="eb1bf-102">Створення сайту SharePoint</span><span class="sxs-lookup"><span data-stu-id="eb1bf-102">Create a SharePoint site</span></span>

<span data-ttu-id="eb1bf-103">Ви можете побачити такі відомості про створення сайту SharePoint:</span><span class="sxs-lookup"><span data-stu-id="eb1bf-103">You can see the following for information about SharePoint site creation:</span></span>
- <span data-ttu-id="eb1bf-104">[Керування сайтів нового центру адміністрування SharePoint](https://docs.microsoft.com/sharepoint/manage-site-creation): дізнатися про створення варіантів сайту, включаючи те, як створити класичний сайту або команд сайт, який не включає Office 365 Група.</span><span class="sxs-lookup"><span data-stu-id="eb1bf-104">[Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-site-creation): Learn about site creation options, including how to create a classic site or a teams site that doesn't include an Office 365 group.</span></span>
- <span data-ttu-id="eb1bf-105">[Створити сайт групи в SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d?ui=en-US&amp;rs=en-US&amp;ad=US): Дізнайтеся, як створити сайт групи.</span><span class="sxs-lookup"><span data-stu-id="eb1bf-105">[Create a team site in SharePoint](https://support.office.com/article/create-a-team-site-in-sharepoint-ef10c1e7-15f3-42a3-98aa-b5972711777d?ui=en-US&amp;rs=en-US&amp;ad=US): Learn how to create a team site.</span></span>
- <span data-ttu-id="eb1bf-106">[Створити повідомлення сайту в SharePoint Online](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb): Дізнайтеся, як створити сайт комунікацій.</span><span class="sxs-lookup"><span data-stu-id="eb1bf-106">[Create a communication site in SharePoint Online](https://support.office.com/article/7fb44b20-a72f-4d2c-9173-fc8f59ba50eb): Learn how to create a communications site.</span></span>
- <span data-ttu-id="eb1bf-107">[Керування сайтів нового центру адміністрування SharePoint](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site): Дізнайтеся, як створити класичний сайту або сайту групи, яка не включає групу Office 365.</span><span class="sxs-lookup"><span data-stu-id="eb1bf-107">[Manage sites in the new SharePoint admin center](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#create-a-site):  Learn how to create a classic site or a team site that doesn't include an Office 365 group.</span></span>


  
> [! Поради]
> - <span data-ttu-id="eb1bf-109">Не вдалося створити сайт з однакову URL-адресу існуючого сайту.</span><span class="sxs-lookup"><span data-stu-id="eb1bf-109">You cannot create a site with the same URL of an existing site.</span></span> <span data-ttu-id="eb1bf-110">Якщо ви видалили сайт і бажає повторне використання URL-адреси, виключено, видалені сайт все ще існує під **Видалені сайтів**.</span><span class="sxs-lookup"><span data-stu-id="eb1bf-110">If you deleted a site and are wishing to re-use the URL, it's possible the deleted site still exists under **Deleted sites**.</span></span> <span data-ttu-id="eb1bf-111">Керувати видалено сайти див, [видалення сайту](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site).</span><span class="sxs-lookup"><span data-stu-id="eb1bf-111">To manage deleted sites see, [Delete a Site](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site).</span></span> <span data-ttu-id="eb1bf-112">Щоб повністю видалити сайт з Powershell, дивіться приклад командлета [Видалити SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) .</span><span class="sxs-lookup"><span data-stu-id="eb1bf-112">To completely remove a site with Powershell, see the [Remove-SPSite](https://docs.microsoft.com/sharepoint/manage-sites-in-new-admin-center#delete-a-site) cmdlet example.</span></span>
> - <span data-ttu-id="eb1bf-113">Деякі користувачі не можуть створити сайт.</span><span class="sxs-lookup"><span data-stu-id="eb1bf-113">Some users may not be able to create a site.</span></span> <span data-ttu-id="eb1bf-114">Переглянути [керування створення сайту в SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).</span><span class="sxs-lookup"><span data-stu-id="eb1bf-114">See [Manage site creation in SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation).</span></span>
> - <span data-ttu-id="eb1bf-115">Виключено, що сайт з'явиться застряг на **створення** довше, ніж очікувалося.</span><span class="sxs-lookup"><span data-stu-id="eb1bf-115">It's possible the site appears stuck at **Creating** longer than expected.</span></span> <span data-ttu-id="eb1bf-116">Якщо більш ніж 24 години пройшло з тих пір ви вперше побачив це питання, будь ласка, увійдіть квиток підтримки.</span><span class="sxs-lookup"><span data-stu-id="eb1bf-116">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="eb1bf-117">У багатьох випадках ми вже працюємо над вирішенням.</span><span class="sxs-lookup"><span data-stu-id="eb1bf-117">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="eb1bf-118">Будь ласка, надайте нам принаймні за 24 години до виконання рішення.</span><span class="sxs-lookup"><span data-stu-id="eb1bf-118">Please give us at least 24 hours to complete a solution.</span></span>
> - <span data-ttu-id="eb1bf-119">Якщо потрібно створити новий сайт команди, яка не включає групу Office 365</span><span class="sxs-lookup"><span data-stu-id="eb1bf-119">If you need to create a new team site that doesn't include an Office 365 group,</span></span> 



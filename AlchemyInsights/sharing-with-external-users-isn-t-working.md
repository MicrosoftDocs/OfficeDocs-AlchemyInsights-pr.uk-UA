---
title: Спільний доступ із зовнішніми користувачами не працює
ms.author: mikeplum
author: MikePlumleyMSFT
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: d3d0b69b-214e-4859-8957-621fd6306b30
ms.openlocfilehash: bd3a6c0d7206801ff76be121c4878b8343cc9886
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 09/14/2020
ms.locfileid: "47691596"
---
# <a name="fix-problems-sharing-sharepoint-content-with-external-users"></a><span data-ttu-id="38f7b-102">Вирішення проблем зі спільним доступом до вмісту SharePoint зовнішнім користувачам</span><span class="sxs-lookup"><span data-stu-id="38f7b-102">Fix problems sharing SharePoint content with external users</span></span>

<span data-ttu-id="38f7b-103">Переконайтеся, що для вашої організації ввімкнуто зовнішній спільний доступ.</span><span class="sxs-lookup"><span data-stu-id="38f7b-103">Make sure external sharing is turned on for your organization:</span></span>
  
1. <span data-ttu-id="38f7b-104">Перейдіть на [сторінку надбудови "служби" &amp; в центрі адміністрування Microsoft 365](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns)і виберіть пункт **сайти**.</span><span class="sxs-lookup"><span data-stu-id="38f7b-104">Go to the [Services &amp; add-ins page in the Microsoft 365 admin center](https://portal.office.com/adminportal/home#/Settings/ServicesAndAddIns), and click **Sites**.</span></span>
    
2. <span data-ttu-id="38f7b-105">Переконайтеся, що для параметра увімкнуто значення "увімкнуто".</span><span class="sxs-lookup"><span data-stu-id="38f7b-105">Make sure the setting is turned to "On."</span></span> <span data-ttu-id="38f7b-106">Якщо вибрано параметр "лише існують зовнішні користувачі", переконайтеся, що зовнішній користувач відображається в центрі адміністрування Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="38f7b-106">If "Only existing external users" is selected, make sure the external user is listed in the Microsoft 365 admin center.</span></span>
    
<span data-ttu-id="38f7b-107">Переконайтеся, що для сайту ввімкнуто зовнішній спільний доступ.</span><span class="sxs-lookup"><span data-stu-id="38f7b-107">Make sure external sharing it turned on for the site.</span></span> <span data-ttu-id="38f7b-108">Для класичної колекції сайтів:</span><span class="sxs-lookup"><span data-stu-id="38f7b-108">For a classic site collection:</span></span>
  
1. <span data-ttu-id="38f7b-109">У новому центрі адміністрування SharePoint в області ліворуч виберіть елемент **сайти**.</span><span class="sxs-lookup"><span data-stu-id="38f7b-109">In the new SharePoint admin center, in the left pane, click **sites**.</span></span>
    
2. <span data-ttu-id="38f7b-110">Виберіть сайт або сайти, а потім на стрічці натисніть кнопку **спільний доступ**.</span><span class="sxs-lookup"><span data-stu-id="38f7b-110">Select the site or sites, and on the ribbon, click **Sharing**.</span></span>
    
<span data-ttu-id="38f7b-111">Для сайту групи, що належить до групи Microsoft 365 або сайту спілкування:</span><span class="sxs-lookup"><span data-stu-id="38f7b-111">For a team site that belongs to a Microsoft 365 group, or a communication site:</span></span>
  
- <span data-ttu-id="38f7b-112">Ці нові типи сайтів мають однаковий параметр спільного доступу, як і для всієї організації, якщо в межах всієї організації не можна надавати спільний доступ до файлів за допомогою посилань, які не потребують входу.</span><span class="sxs-lookup"><span data-stu-id="38f7b-112">These new site types have the same sharing setting as your organization-wide setting, unless the organization-wide setting allows sharing files using links that don't require sign-in.</span></span> <span data-ttu-id="38f7b-113">У цьому випадку сайти дають змогу надавати спільний доступ новим і наявним зовнішнім користувачам, які ввійшли в систему.</span><span class="sxs-lookup"><span data-stu-id="38f7b-113">In this case, the sites allow sharing with new and existing external users who sign in.</span></span> <span data-ttu-id="38f7b-114">Щоб змінити параметр для певних сайтів, використовуйте новий Центр адміністрування SharePoint або PowerShell.</span><span class="sxs-lookup"><span data-stu-id="38f7b-114">To change the setting for specific sites, use the new SharePoint admin center or PowerShell.</span></span> <span data-ttu-id="38f7b-115">[Докладні відомості](https://go.microsoft.com/fwlink/?linkid=871863).</span><span class="sxs-lookup"><span data-stu-id="38f7b-115">[Learn more](https://go.microsoft.com/fwlink/?linkid=871863).</span></span>
    
> [!NOTE]
> <span data-ttu-id="38f7b-116">Параметр зовнішнього спільного доступу для будь-якого сайту може бути більш обмежувальним, ніж для всієї організації, але не більш сприятливий, ніж для всієї організації.</span><span class="sxs-lookup"><span data-stu-id="38f7b-116">The external sharing setting for any site can be more restrictive than your organization-wide setting, but not more permissive than the organization-wide setting.</span></span> 
  


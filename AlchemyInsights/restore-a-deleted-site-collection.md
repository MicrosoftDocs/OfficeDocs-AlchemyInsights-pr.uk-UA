---
title: Відновлення видаленої вузлів
ms.author: kaarins
author: kaarins
manager: scotv
ms.date: 5/1/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cf7521c3-97b4-465a-97eb-6c0a41338a30
ms.openlocfilehash: 1f9a66daf7bee43291b785b6260aec8725ee782f
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/22/2019
ms.locfileid: "30753807"
---
# <a name="restore-a-deleted-site-collection"></a><span data-ttu-id="62727-102">Відновлення видаленої вузлів</span><span class="sxs-lookup"><span data-stu-id="62727-102">Restore a deleted site collection</span></span>

<span data-ttu-id="62727-103">Коли адміністратор видаляє класичний вузлів, вона перебуває у колекції сайтів кошика, де вона зберігається на 93 днів, перш ніж вона видаляється остаточно.</span><span class="sxs-lookup"><span data-stu-id="62727-103">When an admin deletes a classic site collection, it's placed in the site collection Recycle Bin, where it's kept for 93 days before it's permanently deleted.</span></span> <span data-ttu-id="62727-104">Щоб відновити колекції сайтів:</span><span class="sxs-lookup"><span data-stu-id="62727-104">To restore the site collection:</span></span>
  
1. <span data-ttu-id="62727-105">Класичний центру адміністрування SharePoint клацніть **«Кошик»** на стрічці.</span><span class="sxs-lookup"><span data-stu-id="62727-105">In the classic SharePoint admin center, click **Recycle Bin** on the ribbon.</span></span> 
    
2. <span data-ttu-id="62727-106">Установіть прапорець поруч із колекції сайтів, для відновлення.</span><span class="sxs-lookup"><span data-stu-id="62727-106">Select the check box next to the site collection you want to restore.</span></span>
    
3. <span data-ttu-id="62727-107">Натисніть кнопку **відновити видалені елементи**.</span><span class="sxs-lookup"><span data-stu-id="62727-107">Click **Restore Deleted Items**.</span></span>
    
<span data-ttu-id="62727-108">Щоб відновити видалене повідомлення сайту, можна використовувати нові SharePoint admin центр попереднього перегляду.</span><span class="sxs-lookup"><span data-stu-id="62727-108">To restore a deleted communication site, you can use the new SharePoint admin center preview.</span></span> <span data-ttu-id="62727-109">В іншому випадку ви повинні використовувати PowerShell.</span><span class="sxs-lookup"><span data-stu-id="62727-109">Otherwise, you need to use PowerShell.</span></span> <span data-ttu-id="62727-110">Щоб відновити сайт, що належить до групи Office 365, потрібно буде відновити група Exchange центру адміністрування.</span><span class="sxs-lookup"><span data-stu-id="62727-110">To restore a site that belongs to an Office 365 group, you need to restore the group in the Exchange admin center.</span></span> <span data-ttu-id="62727-111">Групи можуть бути відновлені протягом 30 днів після того, як вони ви видалили.</span><span class="sxs-lookup"><span data-stu-id="62727-111">Groups can be restored for 30 days after they're deleted.</span></span>
  


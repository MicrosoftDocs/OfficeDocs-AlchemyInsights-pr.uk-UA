---
title: Скористайтеся Windows PowerShell для Політик спільного доступу та Зв’язків організації
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3800014"
- "898"
ms.openlocfilehash: cd1d34e4dae474e61c799ca9234b2f18c718f27b
ms.sourcegitcommit: 0eb4f9bde53395b5fd4b5cd4ffc56ca96db91298
ms.translationtype: HT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/10/2021
ms.locfileid: "50709487"
---
# <a name="use-powershell-for-sharing-policies-and-organization-relationships"></a><span data-ttu-id="b3b12-102">Скористайтеся Windows PowerShell для Політик спільного доступу та Зв’язків організації</span><span class="sxs-lookup"><span data-stu-id="b3b12-102">Use PowerShell for Sharing policies and Organization relationships</span></span>


<span data-ttu-id="b3b12-103">Для Зв’язків організації перегляньте докладні відомості про синтаксис і параметри для : [Get-FederationInformation](https://docs.microsoft.com/powershell/module/exchange/get-federationinformation), [New-OrganizationRelationship](https://docs.microsoft.com/powershell/module/exchange/new-organizationrelationship), [Set-OrganizationRelationship](https://docs.microsoft.com/powershell/module/exchange/set-organizationrelationship) ТА [Remove-OrganizationRelationship](https://docs.microsoft.com/powershell/module/exchange/remove-organizationrelationship).</span><span class="sxs-lookup"><span data-stu-id="b3b12-103">For Organization relationships please review the detailed syntax and parameter information for : [Get-FederationInformation](https://docs.microsoft.com/powershell/module/exchange/get-federationinformation), [New-OrganizationRelationship](https://docs.microsoft.com/powershell/module/exchange/new-organizationrelationship), [Set-OrganizationRelationship](https://docs.microsoft.com/powershell/module/exchange/set-organizationrelationship)  AND  [Remove-OrganizationRelationship](https://docs.microsoft.com/powershell/module/exchange/remove-organizationrelationship).</span></span>

<span data-ttu-id="b3b12-104">Щоб створити політику спільного доступу, скористайтеся [New-SharingPolicy](https://docs.microsoft.com/powershell/module/exchange/new-sharingpolicy).</span><span class="sxs-lookup"><span data-stu-id="b3b12-104">To create sharing policy use [New-SharingPolicy](https://docs.microsoft.com/powershell/module/exchange/new-sharingpolicy).</span></span> <span data-ttu-id="b3b12-105">Щоб [застосувати політику спільного доступу до поштової скриньки або користувача](https://docs.microsoft.com/exchange/sharing/sharing-policies/apply-a-sharing-policy#use-exchange-online-powershell-to-apply-a-sharing-policy-to-one-or-more-mailboxes), потрібно використовувати з новою політикою поєднання [Set-Mailbox](https://docs.microsoft.com/powershell/module/exchange/set-mailbox) і [Get-Mailbox](https://docs.microsoft.com/powershell/module/exchange/get-mailbox).</span><span class="sxs-lookup"><span data-stu-id="b3b12-105">To  [apply a sharing policy to a mailbox or user](https://docs.microsoft.com/exchange/sharing/sharing-policies/apply-a-sharing-policy#use-exchange-online-powershell-to-apply-a-sharing-policy-to-one-or-more-mailboxes)  you need to use a combination of  [Set-Mailbox](https://docs.microsoft.com/powershell/module/exchange/set-mailbox) and [Get-Mailbox](https://docs.microsoft.com/powershell/module/exchange/get-mailbox) with the newly created policy.</span></span> <span data-ttu-id="b3b12-106">Щоб [змінити, вимкнути або видалити політику спільного доступу](https://docs.microsoft.com/exchange/sharing/sharing-policies/modify-a-sharing-policy), потрібно використовувати [Set-SharingPolicy](https://docs.microsoft.com/powershell/module/exchange/set-sharingpolicy) і [Remove-SharingPolicy](https://docs.microsoft.com/powershell/module/exchange/remove-sharingpolicy).</span><span class="sxs-lookup"><span data-stu-id="b3b12-106">To  [modify, disable or remove a sharing policy](https://docs.microsoft.com/exchange/sharing/sharing-policies/modify-a-sharing-policy)  you need to use  [Set-SharingPolicy](https://docs.microsoft.com/powershell/module/exchange/set-sharingpolicy) and [Remove-SharingPolicy](https://docs.microsoft.com/powershell/module/exchange/remove-sharingpolicy).</span></span>

<span data-ttu-id="b3b12-107">**Щоб мати повне розуміння цієї теми, див.:**</span><span class="sxs-lookup"><span data-stu-id="b3b12-107">**For full understanding of this topic please read:**</span></span>

[<span data-ttu-id="b3b12-108">Надання спільного доступу в Exchange Online</span><span class="sxs-lookup"><span data-stu-id="b3b12-108">Sharing in Exchange Online</span></span>](https://docs.microsoft.com/exchange/sharing/sharing)
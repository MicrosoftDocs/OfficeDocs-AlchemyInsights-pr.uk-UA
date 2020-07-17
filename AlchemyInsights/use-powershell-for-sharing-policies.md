---
title: Використання PowerShell для спільного використання політик і зв'язків організації
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3800014"
- "898"
ms.openlocfilehash: 717cdd6827e243ac6bf375209a911937c97088d2
ms.sourcegitcommit: 722e9a0ed058cb1eab2dd053be2418b60f7d4aac
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 06/23/2020
ms.locfileid: "44862160"
---
# <a name="use-powershell-for-sharing-policies-and-organization-relationships"></a><span data-ttu-id="c127a-102">Використання PowerShell для спільного використання політик і зв'язків організації</span><span class="sxs-lookup"><span data-stu-id="c127a-102">Use PowerShell for Sharing policies and Organization relationships</span></span>


<span data-ttu-id="c127a-103">Для організації відносин перегляньте докладні відомості про синтаксис і параметр для: [Get-Федераціїінформація](https://docs.microsoft.com/powershell/module/exchange/get-federationinformation), [нове організаціїзв'язок](https://docs.microsoft.com/powershell/module/exchange/new-organizationrelationship), [настроїти організацію відносин](https://docs.microsoft.com/powershell/module/exchange/set-organizationrelationship) і [видалення](https://docs.microsoft.com/powershell/module/exchange/remove-organizationrelationship)організацій.</span><span class="sxs-lookup"><span data-stu-id="c127a-103">For Organization relationships please review the detailed syntax and parameter information for : [Get-FederationInformation](https://docs.microsoft.com/powershell/module/exchange/get-federationinformation), [New-OrganizationRelationship](https://docs.microsoft.com/powershell/module/exchange/new-organizationrelationship), [Set-OrganizationRelationship](https://docs.microsoft.com/powershell/module/exchange/set-organizationrelationship)  AND  [Remove-OrganizationRelationship](https://docs.microsoft.com/powershell/module/exchange/remove-organizationrelationship).</span></span>

<span data-ttu-id="c127a-104">Щоб створити спільний доступ до політики, скористайтеся [SharingPolicy](https://docs.microsoft.com/powershell/module/exchange/new-sharingpolicy).</span><span class="sxs-lookup"><span data-stu-id="c127a-104">To create sharing policy use [New-SharingPolicy](https://docs.microsoft.com/powershell/module/exchange/new-sharingpolicy).</span></span> <span data-ttu-id="c127a-105">Щоб [Застосувати політику спільного доступу до поштової скриньки або користувача](https://docs.microsoft.com/exchange/sharing/sharing-policies/apply-a-sharing-policy%23use-exchange-online-powershell-to-apply-a-sharing-policy-to-one-or-more-mailboxes) , потрібно скористатися комбінацією [Set-поштової скриньки](https://docs.microsoft.com/powershell/module/exchange/set-mailbox) та [Get-поштової скриньки](https://docs.microsoft.com/powershell/module/exchange/get-mailbox) з новоствореним політикою.</span><span class="sxs-lookup"><span data-stu-id="c127a-105">To  [apply a sharing policy to a mailbox or user](https://docs.microsoft.com/exchange/sharing/sharing-policies/apply-a-sharing-policy%23use-exchange-online-powershell-to-apply-a-sharing-policy-to-one-or-more-mailboxes)  you need to use a combination of  [Set-Mailbox](https://docs.microsoft.com/powershell/module/exchange/set-mailbox) and [Get-Mailbox](https://docs.microsoft.com/powershell/module/exchange/get-mailbox) with the newly created policy.</span></span> <span data-ttu-id="c127a-106">Щоб [змінити, вимкнути або видалити політику спільного доступу,](https://docs.microsoft.com/exchange/sharing/sharing-policies/modify-a-sharing-policy) потрібно використовувати [параметр-sharingpolicy](https://docs.microsoft.com/powershell/module/exchange/set-sharingpolicy) та [Видалити sharingpolicy](https://docs.microsoft.com/powershell/module/exchange/remove-sharingpolicy).</span><span class="sxs-lookup"><span data-stu-id="c127a-106">To  [modify, disable or remove a sharing policy](https://docs.microsoft.com/exchange/sharing/sharing-policies/modify-a-sharing-policy)  you need to use  [Set-SharingPolicy](https://docs.microsoft.com/powershell/module/exchange/set-sharingpolicy) and [Remove-SharingPolicy](https://docs.microsoft.com/powershell/module/exchange/remove-sharingpolicy).</span></span>

<span data-ttu-id="c127a-107">**Для повного розуміння цієї теми, будь ласка, прочитайте:**</span><span class="sxs-lookup"><span data-stu-id="c127a-107">**For full understanding of this topic please read:**</span></span>

[<span data-ttu-id="c127a-108">Спільне використання в Exchange Online</span><span class="sxs-lookup"><span data-stu-id="c127a-108">Sharing in Exchange Online</span></span>](https://docs.microsoft.com/exchange/sharing/sharing)
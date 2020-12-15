---
title: Увімкнення розміщення голосової пошти
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 12/09/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9002347"
- "7563"
ms.openlocfilehash: 26eb22054d246a6ca5a2491c68a5d9e4ed90d45b
ms.sourcegitcommit: 523098560e54a50184a99c974809dfbfffadacb5
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 12/09/2020
ms.locfileid: "49679161"
---
# <a name="how-to-enable-hosted-voicemail"></a><span data-ttu-id="dd976-102">Увімкнення розміщення голосової пошти</span><span class="sxs-lookup"><span data-stu-id="dd976-102">How to enable Hosted Voicemail</span></span>

<span data-ttu-id="dd976-103">Щоб активувати голосову пошту, потрібно настроїти **голосову пошту** на $True.</span><span class="sxs-lookup"><span data-stu-id="dd976-103">To enable Voicemail, **HostedVoicemail** must be set to $true.</span></span>

<span data-ttu-id="dd976-104">Властивість **Hostedvoicemail пошта** користувача за допомогою віддаленого PowerShell (RPS).</span><span class="sxs-lookup"><span data-stu-id="dd976-104">The **HostedVoicemail** property on the user using Remote PowerShell (RPS).</span></span>

<span data-ttu-id="dd976-105">Щоб отримати докладніші відомості про підключення до RPS, ознайомтеся з додатковими відомостями про підключення до RPS у [програмі Microsoft](https://docs.microsoft.com/microsoftteams/teams-powershell-overview) .</span><span class="sxs-lookup"><span data-stu-id="dd976-105">For more information on connecting to RPS, see [Microsoft Teams PowerShell Overview](https://docs.microsoft.com/microsoftteams/teams-powershell-overview) for more information on connecting to RPS.</span></span>

1. <span data-ttu-id="dd976-106">Адміністратор команди має увійти в віддалений PowerShell для команд.</span><span class="sxs-lookup"><span data-stu-id="dd976-106">The Teams Admin should be logged into Remote PowerShell for Teams.</span></span>
1. <span data-ttu-id="dd976-107">У програмі PowerShell запит адміністратор команди може запустити **Set-csuser user@contoso.com-HostedVoiceMail пошта $True** , де SIP URI має користувача в питанні.</span><span class="sxs-lookup"><span data-stu-id="dd976-107">From PowerShell prompt the Teams Admin can run **set-csuser user@contoso.com -HostedVoiceMail $true** where the sip uri is of the user in question.</span></span>

> [!NOTE]
> <span data-ttu-id="dd976-108">Зміни в політиці можуть знадобитися до 24 годин, щоб реплікувати.</span><span class="sxs-lookup"><span data-stu-id="dd976-108">Changes to policies can take up to 24 hours to replicate.</span></span>
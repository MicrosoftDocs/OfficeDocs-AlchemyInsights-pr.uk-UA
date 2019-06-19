---
title: 2419-для увімкнути аудит
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 2419
ms.assetid: ''
ms.openlocfilehash: 3af01c03711eed646f0009afb5bea685bc358196
ms.sourcegitcommit: 87153fec6f6468b57893abf4aac073ba4068e67b
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 06/19/2019
ms.locfileid: "35065725"
---
# <a name="unable-to-enable-unified-auditing"></a><span data-ttu-id="62864-102">Не вдається увімкнути уніфікований аудит</span><span class="sxs-lookup"><span data-stu-id="62864-102">Unable to enable unified auditing</span></span>

<span data-ttu-id="62864-103">Коли ви намагаєтеся ввімкнути уніфікованих аудиту поштових скриньок для організації Office 365, може з'явитися повідомлення про помилку, схоже нижче:</span><span class="sxs-lookup"><span data-stu-id="62864-103">When you try to enable unified auditing for your Office 365 organization, you may receive an error similar the following:</span></span>

```
Request: /api/adminauditlogconfig/EnableUnifiedAuditLogIngestion Status code: 500 Exception message: {"Message":"The command you tried to run isn't currently allowed in your organization. To run this command, you first need to run the command: Enable-OrganizationCustomization."
```

<span data-ttu-id="62864-104">Щоб вирішити цю проблему, виконайте такі дії:</span><span class="sxs-lookup"><span data-stu-id="62864-104">To resolve this issue, follow these steps:</span></span>

1. <span data-ttu-id="62864-105">[Підключитися до обміну онлайн Powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell).</span><span class="sxs-lookup"><span data-stu-id="62864-105">[Connect to Exchange Online Powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell).</span></span>

2. <span data-ttu-id="62864-106">Запустіть наступну команду:</span><span class="sxs-lookup"><span data-stu-id="62864-106">Run the following cmdlet:</span></span>

   ```
   Enable-OrganizationCustomization
   ```

3. <span data-ttu-id="62864-107">Чекати на 60 хвилин для попередньої настройки вступили в силу.</span><span class="sxs-lookup"><span data-stu-id="62864-107">Wait for 60 minutes for the previous setting to take effect.</span></span>

4. <span data-ttu-id="62864-108">Запустіть таку команду в Exchange Online PowerShell:</span><span class="sxs-lookup"><span data-stu-id="62864-108">Run the following command in Exchange Online PowerShell:</span></span>

   ```
   Set-AdminAuditLogConfig -UnifiedAuditLogIngestionEnabled $true
   ```

<span data-ttu-id="62864-109">Щоб отримати додаткові відомості перегляньте наступні статті:</span><span class="sxs-lookup"><span data-stu-id="62864-109">For additional information, see the following articles:</span></span>

- [<span data-ttu-id="62864-110">Підключитися до Exchange Online PowerShell багатофакторну автентифікацію</span><span class="sxs-lookup"><span data-stu-id="62864-110">Connect to Exchange Online PowerShell using multi-factor authentication</span></span>](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/mfa-connect-to-exchange-online-powershell)

-  [<span data-ttu-id="62864-111">Вмикається Office 365 аудиту журнал пошуку</span><span class="sxs-lookup"><span data-stu-id="62864-111">Turn Office 365 audit log search on or off</span></span>](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off)

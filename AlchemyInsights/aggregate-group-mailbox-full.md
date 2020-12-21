---
title: Повне повідомлення про НЕДОСТАВКУ, отримане для електронної пошти, надісланого до групи Microsoft 365
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/18/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004286"
- "7656"
ms.openlocfilehash: 9de09ab4cbd2f09648305b11da6273ed990907cf
ms.sourcegitcommit: 2ffdf6096de5608b117c6677d3cd7dd4c23ea024
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 12/18/2020
ms.locfileid: "49722075"
---
# <a name="aggregategroupmailbox-full-ndr-received-for-email-sent-to-microsoft-365-group"></a>Повне повідомлення про НЕДОСТАВКУ, отримане для електронної пошти, надісланого до групи Microsoft 365

За допомогою команди EXO Shell можна створити правило транспортування Exchange до повідомлень електронної пошти, надісланих до поштової скриньки агрегатної групи:

`New-TransportRule -SentTo @("AggregateGroupMailbox.A.201708181918@contoso.onmicrosoft.com") -DeleteMessage:$true -Name 'Agg1' -StopRuleProcessing:$false -Mode 'Enforce' -Comments '' -RuleErrorAction 'Ignore' -SenderAddressLocation 'Header'`

> [!NOTE]
> Замініть адресу SMTP в **-Санто** на адресу SMTP агрегатної групи поштової скриньки в клієнті. Ви можете отримати SMTP-адресу агрегатної групи поштової скриньки з отриманого повідомлення про НЕДОСТАВКУ.




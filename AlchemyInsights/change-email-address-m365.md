---
title: Змінення адреси електронної пошти групи Microsoft 365
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
- "1200024"
- "4704"
ms.openlocfilehash: f54ca5df09d0604f6d58c6c8a41dc907485e1f04
ms.sourcegitcommit: beb9715ac0c8e8333fef6764ecd346b7401a2612
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 10/10/2020
ms.locfileid: "48462061"
---
# <a name="change-email-address-of-a-microsoft-365-group"></a>Змінення адреси електронної пошти групи Microsoft 365

Ви можете змінити адресу електронної пошти групи Microsoft 365 за допомогою Центру адміністрування. Просто виберіть групу та виберіть @edit адресу електронної пошти.

Ви також можете скористатися командою EXO PowerShell, щоб змінити основну адресу SMTP групи Microsoft 365.

`Set-UnifiedGroup <Group Name> -PrimarySmtpAddress <new SMTP Address>`

Наприклад

`et-UnifiedGroup Marketing -PrimarySmtpAddress marketing@contoso.com`

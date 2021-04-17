---
title: Керування синхронізованим користувачем
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000609"
- "2444"
ms.openlocfilehash: 0dc2ecfa0bb5703c619dc1b2d6b4d517f999da0d
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/15/2021
ms.locfileid: "51823988"
---
# <a name="unable-to-set-primary-email-address-change-user-attributes-or-removedelete-a-synchronized-user"></a>Не вдається вказати основну адресу електронної пошти, змінити атрибути користувача або видалити синхронізованого користувача

Якщо синхронізацію служби каталогів увімкнуто для вашого середовища, деякі атрибути користувача або об'єкта не можна змінити в Центрі адміністрування Microsoft 365.

Щоб повністю керувати синхронізованими користувачами та їхніми атрибутами, використовуйте локальну консоль керування користувачами Active Directory та групами (adsiedit.msc).  

Крім того, ви можете змінити окремих користувачів або атрибути для синхронізних користувачів за допомогою PowerShell, як показано в наведених нижче прикладах.

`Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com`

`Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"`

`Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com`

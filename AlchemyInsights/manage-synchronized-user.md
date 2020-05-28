---
title: Керування синхронізованими користувачами
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000609"
- "2444"
ms.openlocfilehash: 84e337a7224fdd3c3ab7ad0f61240692fe007d5a
ms.sourcegitcommit: 82af227ac6d075e748e27c4ce6bdcf56628559cb
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 05/28/2020
ms.locfileid: "44407371"
---
# <a name="unable-to-set-primary-email-address-change-user-attributes-or-removedelete-a-synchronized-user"></a>Не вдається встановити основну адресу електронної пошти, змінити атрибути користувача або видалити або видалити синхронізований користувач

Якщо синхронізацію каталогів увімкнуто для вашого середовища, деякі користувацькі або об'єктні атрибути не можна змінити за допомогою Центру адміністрування Microsoft 365.

Щоб повністю керувати синхронізованими користувачами та всіма їх атрибутами, використовуйте локальну консоль керування Active Directory та групами (adsiedit. msc).  

Крім того, ви можете змінити окремих користувачів або атрибутів для синхронізованих користувачів за допомогою PowerShell, таких як показано в цих поширених прикладах: 
- `Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com`

- `Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"`

- `Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com`

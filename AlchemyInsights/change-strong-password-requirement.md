---
title: Зміна надійного пароля
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000105"
- "1600"
ms.openlocfilehash: 21f80a7cc8b00ac56acdb05add1e1bfdfac9d827
ms.sourcegitcommit: c061f1dfa6f557a9ec083dd030b73b121d9864ea
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/14/2020
ms.locfileid: "43286299"
---
# <a name="change-strong-password-requirement"></a>Зміна надійного пароля

За умовчанням корпорація Майкрософт вимагає надійних паролів. 

За допомогою PowerShell можна вимкнути надійні паролі для певних користувачів за допомогою цієї команди:<br>
*Набір-MsolUser – ім'я <UserPrincipalName> користувача – стронпасворсобов'язково $false*

- [Більш детальну інформацію про політику паролів](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [Як підключитися до Office 365 з PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [Додаткові відомості про команди PowerShell MsolUser](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)
- [Установлення пароля окремого користувача, який ніколи не закінчиться](https://docs.microsoft.com/microsoft-365/admin/add-users/set-password-to-never-expire)

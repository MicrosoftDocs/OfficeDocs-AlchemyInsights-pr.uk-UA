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
ms.openlocfilehash: a054735a0c139c90d76098297bb9984d37464d3b
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/22/2020
ms.locfileid: "43706582"
---
# <a name="change-strong-password-requirement"></a>Зміна надійного пароля

За умовчанням корпорація Майкрософт вимагає надійних паролів. 

За допомогою PowerShell можна вимкнути надійні паролі для певних користувачів за допомогою цієї команди:<br>
*Набір-MsolUser – ім'я <UserPrincipalName> користувача – стронпасворсобов'язково $false*

- [Більш детальну інформацію про політику паролів](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [Як підключитися до Microsoft 365 з PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [Додаткові відомості про команди PowerShell MsolUser](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)

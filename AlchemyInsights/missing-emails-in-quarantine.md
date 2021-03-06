---
title: Відсутні електронні листи в карантині
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
- "5668"
- "9002625"
ms.openlocfilehash: 563f76f624f428a46894268b478cf05eb757b497
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 05/19/2021
ms.locfileid: "52539845"
---
# <a name="missing-emails-in-quarantine"></a>Повідомлення електронної пошти відсутні в карантинах

Адміністратори можуть [переглядати, випускати та видаляти ці повідомлення.](/microsoft-365/security/office-365-security/manage-quarantined-messages-and-files)

Щоб відкрити Центр безпеки &, перейдіть [https://protection.office.com](https://protection.office.com/) до . Щоб відкрити сторінку безпосередньо в карантин, перейдіть на сторінку [https://protection.office.com/quarantine](https://protection.office.com/quarantine) .  

Ви можете шукати за такими значеннями:  

- **Ідентифікатор повідомлення:** глобальний унікальний ідентифікатор повідомлення. Якщо вибрати повідомлення в списку, в **області** Відомості,  що з'явиться, з'явиться значення Ідентифікатор повідомлення. Адміністратори можуть використовувати [трасування повідомлень,](/microsoft-365/security/office-365-security/message-trace-scc) щоб знаходити повідомлення та відповідні значення ідентифікаторів повідомлень.
- **Адреса електронної пошти відправника:** адреса електронної пошти одного відправника.
- **Адреса електронної пошти одержувача**: адреса електронної пошти одного одержувача.
- **Тема**– використовуйте всю тему повідомлення. У результатах пошуку не врагується регістр.

Ввівши умови пошуку, натисніть кнопку Оновити, щоб ![ ](/microsoft-365/media/scc-quarantine-refresh.png?view=o365-worldwide) **відфільтрувати** результати.

Командлети, які використовуються для перегляду повідомлень і файлів і керування ними в карантині:
- [Delete-QuarantineMessage](/powershell/module/exchange/delete-quarantinemessage)
- [Export-QuarantineMessage](/powershell/module/exchange/export-quarantinemessage)
- [Get-QuarantineMessage](/powershell/module/exchange/get-quarantinemessage)
- [Preview-QuarantineMessage:](/powershell/module/exchange/preview-quarantinemessage)зверніть увагу, що цей командлет доступний лише для повідомлень, а не файлів зі зловмисних програм із Microsoft Defender для Office 365 для SharePoint Online, OneDrive для бізнесу або Teams.
- [Release-QuarantineMessage](/powershell/module/exchange/release-quarantinemessage)
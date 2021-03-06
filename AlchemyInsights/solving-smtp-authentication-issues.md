---
title: Увімкнення автентифікації SMTP та виправлення неполадок
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3000003"
- "5652"
ms.openlocfilehash: 4695a2f111823739c4d87fa2b262a5e64e080955
ms.sourcegitcommit: 2103d706492ad7ee9596344714c0520569ebd6af
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 06/23/2021
ms.locfileid: "53077672"
---
# <a name="enable-smtp-authentication-and-troubleshooting"></a>Увімкнення автентифікації SMTP та виправлення неполадок

Якщо потрібно активувати автентифікацію SMTP для поштової скриньки або ви отримуєте "Клієнт не автентифіковано", Помилка "Автентифікація невдала" або "SmtpClientAuthentication" з кодом 5.7.57 або 5.7.3 або 5.7.139 під час спроби надіслати повідомлення електронної пошти, автентифікацію пристрою або програми за допомогою Microsoft 365, щоб вирішити цю проблему, виконайте такі три дії:

1. [Вимкніть стандартні параметри безпеки Azure,](/azure/active-directory/fundamentals/concept-fundamentals-security-defaults) установлювши перемикач **Увімкнути стандартні параметри безпеки** в значення **Ні.**

    а. Увійдіть на портал Azure як адміністратор безпеки, адміністратор умовного доступу або глобальний адміністратор.<BR/>
    б. Перейдіть до Azure Active Directory > **Властивості.**<BR/>
    в. Виберіть **Елемент Керування параметрами безпеки за замовчуванням**.<BR/>
    г. Установіть для **параметра Увімкнути безпеку за замовчуванням значення** **Ні**.<BR/>
    е. Натисніть **кнопку Зберегти**.

2. [Увімкніть надсилання SMTP клієнта](/exchange/clients-and-mobile-in-exchange-online/authenticated-client-smtp-submission#enable-smtp-auth-for-specific-mailboxes) в ліцензованій поштовій скриньці.

    а. У Центр адміністрування Microsoft 365 перейдіть до **пункту Активні** користувачі та виберіть користувача.<BR/>
    б. Перейдіть на вкладку Пошта та в розділі Програми **електронної пошти** виберіть керування **програмами електронної пошти**.<BR/>
    г. **Переконайтеся, що прапорець Автентифікований SMTP** (увімкнуто).<BR/>
    е. Виберіть **Save changes (Зберегти зміни).**<BR/>

3. [Вимкніть багатофакторну автентифікацію (MFA)](/microsoft-365/admin/security-and-compliance/set-up-multi-factor-authentication#turn-off-legacy-per-user-mfa) у ліцензованій поштовій скриньці.

    а. Перейдіть до меню Центр адміністрування Microsoft 365 в меню переходів ліворуч виберіть **Активні**  >  **користувачі.**<BR/>
    б. Виберіть **Багатофакторна автентифікація.**<BR/>
    в. Виберіть користувача та **вимкніть multi-Factor auth.**<BR/>

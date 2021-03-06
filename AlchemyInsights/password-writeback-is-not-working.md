---
title: Не працює з Wriтиповернення пароля
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004595"
- "8210"
ms.openlocfilehash: d7766f908f025b5db8299aa45d01dc5389b321ec
ms.sourcegitcommit: 2f39850ac0fba9fbeba9b8b7939ae79b505d3b67
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 02/12/2021
ms.locfileid: "50243731"
---
# <a name="password-writeback-is-not-working"></a>Не працює з Wriтиповернення пароля

**У мене виникли проблеми з настроюванням запису пароля**

- Password wriтиback – це Преміальний компонент.
- Переконайтеся, що ви зрозуміли вимоги до ліцензування:
  - Потрібно мати принаймні одну ліцензію, призначену в організації
  - **Хмарні тільки користувачі** – будь-який Office 365 (O365) платний обліковий номер або ЛАЗУРНЕ AD Basic
  - **Хмарні та/або Локальні користувачі** – AZURE AD Premium P1 або P2, Enterprise Mobility + Security (EMS) або захищене продуктивне підприємство (SPE).
    - Додаткові відомості про вимоги до ліцензування наведено в статті [вимоги до ліцензування для скидання пароля служби самообслуговування Azure AD](https://docs.microsoft.com/azure/active-directory/active-directory-passwords-licensing) .
- У вас є принаймні один обліковий запис адміністратора, а один тестовий обліковий запис користувача з однією з відповідної ліцензії.
- Ви повинні підключити Azure AD Connect до головного емулятора контролера домену для wriveback для роботи з паролем. Ви можете налаштувати Azure AD Connect для використання основного контролера домену, клацнувши правою кнопкою миші **Властивості** сполучної лінії синхронізації Active Directory, а потім виберіть пункт **настроїти розділи каталогів**. Звідти знайдіть розділ **Параметри підключення контролера домену** та установіть прапорець **використовувати лише контролери домену**.
  > [!NOTE]
  > Якщо перевага для постійного струму не є емулятором PDC, то "Azure AD Connect" все одно буде досягнуто в службі PDC для визначення пароля.
- Скидання пароля настроєно та ввімкнуто в клієнті. Щоб отримати докладніші відомості, Дізнайтеся, як [дозволити користувачам скинути їхні паролі Azure AD](https://docs.microsoft.com/azure/active-directory/active-directory-passwords-getting-started).
- Переконайтеся, що обліковий запис адміністратора, який використовується для того, щоб увімкнути Wriтиback – обліковий запис адміністратора хмари (створений у Лазурому, не локальний РЕКЛАМНИЙ)
- У вас є один або кілька лісових ОБ'ЯВ локального розгортання під керуванням Windows Server 2008 R2, Windows Server 2012 або Windows Server 2012 R2 з найновішими інстальованими пакетами оновлень
- У вас інстальовано засіб Azure AD Connect, і ви підготували середовище для синхронізації до хмари. Перш ніж протестувати пароль writeback, переконайтеся, що спочатку потрібно виконати повне імпортування та повну синхронізацію з AD і Azure AD Connect Azure.
- Дізнайтеся більше про те, як виконати [повну синхронізацію та повний імпорт у лазурому для підключення до мережі](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-operations)

**У мене виникли проблеми з підключенням до wriтиповернення пароля**

1. Завантажте та активуйте найновішу версію служби [Azure AD Connect](https://www.microsoft.com/download/details.aspx?id=47594)
2. Конфігурація брандмауера: засіб Azure AD Connect (1.1.443 і вище) матиме доступ до **ВИХІДНОГО HTTPS** :
    - passwordreset.microsoftonline.com
    - servicebus. Windows. Networks
3. Дозволити простоювання підключень протягом щонайменше 2-3 хвилин

**У мене все ще виникають проблеми з wriтиповернення пароля**

- Якщо ви все ще відчуваєте труднощі, скористайтеся вимкненням та повторно активованою службою wriveback для використання в засобі створення Лазурової програми AD Connect
- Щоб дізнатися більше, Дізнайтеся більше про те, як [Вимкнути та знову ввімкнути wriтиповернутися паролем](https://docs.microsoft.com/azure/active-directory/active-directory-passwords-troubleshoot)

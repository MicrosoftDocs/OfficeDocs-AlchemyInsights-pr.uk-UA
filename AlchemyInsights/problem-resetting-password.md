---
title: Помилка скидання пароля
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 03/09/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003259"
- "9360"
ms.openlocfilehash: aa1eba1efef6a4c28aa6b9229071304093395922
ms.sourcegitcommit: 9a00005546c2fe473e3cea2b06e38c27eada88c4
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/09/2021
ms.locfileid: "50696282"
---
# <a name="problems-resetting-password"></a>Проблеми з відновленням пароля

Нижче наведено деякі з проблем, які можуть виникнути під час скидання пароля та можливих рішень.

**У мене виникла проблема з скидлення пароля, не охоплених іншими категоріями**

- Переконайтеся, що ви авторизовані для скидання паролів. Скинути паролі користувачів можна лише за глобальними, паролем і адміністраторами користувачів. Глобальні адміністратори також можуть скинути паролі іншого привілейованого адміністратора.
- Переконайтеся, що ви розумієте вимоги до ліцензування:
    - Потрібно мати принаймні одну ліцензію, призначену в організації
        - Хмарні тільки користувачі – будь-який Office 365 (O365) платний ОБЛІКОВИЙ номер або Лазурне AD Basic
        - Хмарні та/або Локальні користувачі – Azure AD Premium P1 або P2, Enterprise Mobility + Security (EMS) або захищене продуктивне підприємство (SPE).
        - Додаткові відомості про вимоги до ліцензування наведено в статті [вимоги до ліцензування для неавтоматичного скидання пароля служби "Лазурний](https://docs.microsoft.com/azure/active-directory/active-directory-passwords-licensing?WT.mc_id=Portal-Microsoft_Azure_Support)".

**Утруднення під час перевірки політики скидання пароля**

- Нещодавно застосовані політики можуть виконувати кілька хвилин, щоб реплікувати всі центри даних і кінцеві точки. Фізична відстань від центру обробки даних також вплине на спосіб застосування швидко внесених змін.
- Перевірка з кінцевим користувачем, а не адміністратором і пілотом з невеликим набором користувачів. Політики, настроєні на порталі "Лазурний", призначено лише кінцевим користувачам, а не адміністраторам. Корпорація Майкрософт застосовує сильну політику скидання пароля за два ворота для будь-якого роль (приклад: Глобальний адміністратор, адміністратор служби підтримки, адміністратор паролів тощо).
    - Дізнайтеся більше про [політики для адміністраторів](https://docs.microsoft.com/azure/active-directory/active-directory-passwords-policy?WT.mc_id=Portal-Microsoft_Azure_Support#administrator-password-policy-differences).

**Я хочу розгорнути скидання пароля, але я не хочу, щоб мої користувачі реєструватимемо додаткові відомості про безпеку**

Попередньо заповніть дані для користувачів, щоб їх не було! -Адміністратор дає змогу налаштувати параметри телефону та електронної пошти для користувачів, перш ніж установлювати скидання пароля до вашої організації. Ви можете зробити це за допомогою API, PowerShell або Azure AD Connect. Додаткові відомості тут:
- [Розгортання скидання пароля без необхідності реєструвати користувачів](https://docs.microsoft.com/azure/active-directory/active-directory-passwords-policy?WT.mc_id=Portal-Microsoft_Azure_Support#administrator-password-policy-differences)
- [Дані, які використовуються для скидання пароля](https://docs.microsoft.com/azure/active-directory/active-directory-passwords-data?WT.mc_id=Portal-Microsoft_Azure_Support)

**Кнопка "скидання пароля"**

Ви не авторизовані для скидання паролів цього користувача. Скинути паролі користувачів можна лише за глобальними, паролем і адміністраторами користувачів. Глобальні адміністратори також можуть скинути паролі іншого привілейованого адміністратора.

**Не відображається лезо скидання пароля**

Ви не авторизовані для скидання паролів. Скинути паролі користувачів можна лише за глобальними, паролем і адміністраторами користувачів. Глобальні адміністратори також можуть скинути паролі іншого привілейованого адміністратора.

**У разі скидання пароля не відображається локальна відповідь для інтеграції**

- Локальна відповідь на інтеграцію відображається лише в гібридних середовищах – тобто ви використовуєте перезапису пароля, щоб маніпулювати паролями локального користувача.
- Цей Клинок не відображається, якщо:
    - Ви не використовуєте wriтиback пароля
    - Виникла проблема з інсталяцією та підключенням облікового запису для wriadback
    - Виникла проблема з інсталяцією та підключенням служби Azure AD Connect
    - Додаткові кроки з виправлення неполадок, які допоможуть вирішити проблему з wriseback, ознайомтеся з розділом [Виправлення неполадок із wriseback](https://docs.microsoft.com/azure/active-directory/active-directory-passwords-data?WT.mc_id=Portal-Microsoft_Azure_Support)

**Я не знаю, як скинути пароль користувача**

1. Увійдіть на портал "Лазурний" як відповідний адміністратор.
1. Перейдіть до леза "користувачі та групи", виберіть **усі користувачі**.
1. Виберіть користувача зі списку.
1. Для вибраного користувача виберіть **Огляд**, а потім на панелі команд натисніть кнопку **скинути пароль**.
1. Дотримуйтеся вказівок на екрані.
    - Тільки скидання здійснюється за допомогою облікового запису "wrireback".

**Я скину пароль локального користувача з порталу адміністрування Office 365 або Office 365 для мобільних пристроїв, але користувач все ще не зможе ввійти**

На цьому порталі не підтримується Wriтиповернення пароля. Знову скиньте пароль користувача на порталі Azure-portal.azure.com


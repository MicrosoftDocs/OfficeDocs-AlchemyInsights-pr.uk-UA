---
title: Відстеження умовного доступу
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 02/25/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004636"
- "8386"
ms.openlocfilehash: e2803a49aaf087ac55b1fd62056e2b0af3fcd919
ms.sourcegitcommit: 229bd519ec1c14c65a243226a94eee23e117a7fc
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/03/2021
ms.locfileid: "50428311"
---
# <a name="monitor-intune-conditional-access"></a>Відстеження умовного доступу

Користувачі, які націлені на умовний доступ, отримають сповіщення електронною поштою, якщо вони не відповідатимуть вимогам доступу до вашої організації. Щоб вирішити цю проблему, радимо виконати одну або кілька з наведених нижче рішень.

1. Якщо пристрій має бути зареєстровано, радимо користувачу перейти до програми "портал компанії" та переконатися, що вона з'явиться на порталі компанії. Якщо це не так, користувач має зареєструвати пристрій.
1. На порталі Лазурне перейдіть до   >  **відповідності пристрою** inune. 
1. Щоб переглянути звіт про відповідність пристрою, щоб переконатися, що пристрій користувача позначено як сумісний, у розділі **монітор** виберіть елемент **відповідність пристрою**.
1. На порталі Лазурне перейдіть до   >  **відповідності пристрою** inune. У розділі **керування** виберіть елемент **політики**. У списку політик відповідності переконайтеся, що профіль призначається для вашого пристрою користувача. Якщо не призначено профіль, функція Inune не зможе підтвердити стан відповідності пристрою.
1. Редагування призначення умовного доступу користувача.
1. На порталі "Лазурний" **перейдіть на** вкладку "політики  >  **умовного доступу**  >  ", виберіть політику зі списку, а потім клацніть елемент **користувачі та групи**.
1. Щоб націлити певну політику на когось, додайте їх до **списку include**. Щоб переконатися, що особу пропущено від політики, додайте їх до **списку винятків**.

**Корисні посилання:**

- [Огляд відповідності пристрою](https://docs.microsoft.com/intune/device-compliance-get-started)
- [Виправлення неполадок із CA](https://docs.microsoft.com/intune/troubleshoot-conditional-access)
- [Виправлення неполадок із політикою](https://docs.microsoft.com/intune/troubleshoot-policies-in-microsoft-intune)
- [Відстеження відповідності пристрою](https://docs.microsoft.com/intune/compliance-policy-monitor)

> [!NOTE]
> Ці дії доступні лише для виправлення неполадок із умовною доступом до функції "Лазурний". Крім того, можна використовувати карантин пристрою, що блокує доступ до електронної пошти з політикою Exchange. Додаткові відомості про керування пристроями Exchange можна знайти [**тут**](https://docs.microsoft.com/previous-versions/office/exchange-server-2010/ff959225(v=exchg.141)).

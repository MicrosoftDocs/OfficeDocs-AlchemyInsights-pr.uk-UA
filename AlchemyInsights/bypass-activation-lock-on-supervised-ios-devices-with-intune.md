---
title: Обхід блокування активації на контрольованих пристроях iOS з InTune
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/23/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1277"
- "6700008"
ms.openlocfilehash: 16be4e0cd2e47fe5d5888cbbe1380774f859e4d6
ms.sourcegitcommit: 07e56267dedfc4cec1143072c791670cbf81186b
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 07/24/2020
ms.locfileid: "45424208"
---
# <a name="bypass-activation-lock-on-supervised-ios-devices-with-intune"></a>Обхід блокування активації на контрольованих пристроях iOS з InTune

Можливість обійти блокування активації на пристроях iOS полегшує відновлення за сценарієм, коли користувач активує блокування активації на корпоративному пристрої, а потім залишає компанію.

Передумови для обходу блокування активації включають:

- Пристрій, що "контролюється".
- Блокування активації успішно ввімкнуто, використовуючи iOS пристрою обмеження політики в InTune.

Крім того, при минаючи блокування активації вам необхідно:

- Фізично володіти пристроєм, що знищили.
- Скопіюйте код, перш ніж видати стирання.

**Примітка:** Код стирання не чутливий до регістру, тому символи "-" не потрібні.

Докладні відомості наведено в [обхід блокування активації на контрольованих пристроях IOS із InTune](https://docs.microsoft.com/intune/device-activation-lock-bypass).

**Запитання й відповіді**

Q: **я видав віддалену дію, щоб видалити дані компанії з пристрою, і тепер він застряг у стані очікування.**

В: для віддаленої дії, щоб успішно завершити, цільовий пристрій повинен бути онлайн і здоровим. У таких ситуаціях Віддалена дія залишається в стані очікування протягом 30 днів або поки пристрій не визнає команду, коли пристрій:

- Не має підключення.
- Втрачає статус керування з InTune.

Якщо ви вважаєте, що пристрій більше не перевірятися, і що він не видаляє дані компанії, виберіть Видалити. Видалення видаляє запис пристрою так, що він більше не відображається у списку InTune пристроїв. Щоб пристрій став активним знову, його користувач повинен повторно зареєструвати пристрій.

П: **чому деякі віддалені дії недоступні для мене?**

В: не всі платформи підтримують всі дії з віддаленим пристроєм. Такі віддалені дії є специфічними для платформи.

- Обхід блокування активації (лише для iOS)
- Чистий запуск (лише для Windows)
- Втрачений режим (лише для iOS)
- Пошук пристрою (лише для iOS)
- Перезапустити (лише для Windows)

Щоб отримати докладніші відомості про кожну дію, перегляньте [доступні дії пристрою](https://docs.microsoft.com/intune/device-management#available-device-actions).
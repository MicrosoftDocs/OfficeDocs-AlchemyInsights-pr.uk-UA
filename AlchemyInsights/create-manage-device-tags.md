---
title: Створення тегів або груп пристроїв і керування ними
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 06/01/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "11446"
- "9003537"
ms.openlocfilehash: 3a7d53beaaf830055904f0634f09a3e9e447006e
ms.sourcegitcommit: 1226e9a9601dc8fc8ec427235f3c2dd88ff84ced
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 06/02/2021
ms.locfileid: "52731972"
---
# <a name="create-and-manage-device-tags-or-groups"></a>Створення тегів або груп пристроїв і керування ними

Додайте позначки на пристроях, щоб створити зв'язку в логічній групі. Позначки пристроїв підтримують правильне зіставлення мережі, що дає змогу прикріпити різні позначки для записування контексту та активувати динамічне створення списку в складі інциденту. Позначки можна використовувати як фільтр у поданні списку "Пристрої" або групувати пристрої. Докладні відомості про групування пристроїв див. в розділі [Створення тегів пристроїв і керування ними.](/microsoft-365/security/defender-endpoint/machine-tags)

Теги можна додавати на пристроях:

- Використання порталу

- Настроювання значення розділу реєстру
 
**Примітка.** Можливо, між часом додавання позначки до пристрою та його доступністю в списку пристроїв і на сторінці пристрою може виникати затримка.

Щоб дізнатися, як додати позначки пристроїв за допомогою API, див. номери Додавання та видалення [API-тегів пристроїв.](/microsoft-365/security/defender-endpoint/add-or-remove-machine-tags)

## <a name="add-and-manage-device-tags-using-the-portal"></a>Додавання тегів пристроїв і керування ними за допомогою порталу

1. Виберіть пристрій, на якому потрібно керувати позначками. Ви можете вибрати або знайти пристрій у будь-якому з таких подань:

    - **Приладна дошка операцій безпеки** Виберіть ім'я пристрою в розділі Найпопулярніші пристрої з активними оповіщеннями.
    - **Черга оповіщень–** виберіть ім'я пристрою поруч із піктограмою пристрою в черзі оповіщень.
    - **Список Пристрої** – виберіть ім'я пристрою зі списку пристроїв.
    - **Поле пошуку.** У розкривному меню виберіть пункт Пристрій і введіть ім'я пристрою.

    Сторінку оповіщення також можна відкрити в поданнях файлів і IP-адрес.

1. У **рядку Дій** із відповіддю виберіть керування позначками.

1. Введіть, щоб знайти або створити позначки.

Позначки додаються до подання пристрою та відображаються в поданні списку Пристрої. Потім можна скористатися фільтром "Позначки", щоб переглянути відповідний список пристроїв.

Докладні відомості див. в [розділі Створення позначок пристроїв і керування ними.](/microsoft-365/security/defender-endpoint/machine-tags)
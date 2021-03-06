---
title: Визначення IP-адреси в журналі аудиту
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 02/26/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3100005"
- "7327"
ms.openlocfilehash: 7a01aa3cc0d875e6534435f3e8f90a24f2832dc3
ms.sourcegitcommit: 251e2e82571fb3bb1fbe3dbf7bfca30e004b3373
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/05/2021
ms.locfileid: "50483713"
---
# <a name="find-the-ip-address-in-audit-log"></a>Визначення IP-адреси в журналі аудиту

1. IP-адреса, що відповідає діяльності, що виконується користувачем або адміністратором, відображається в журналах аудиту. Відомості про клієнта також записуються. Ось як можна визначити IP-адресу:

1. Перейдіть до [центру відповідності & безпеки Office 365](https://go.microsoft.com/fwlink/p/?linkid=2077143).
1. Виберіть **пункт**  >  **[Пошук у журналі аудиту](https://go.microsoft.com/fwlink/?linkid=2103759)**.
    > [!NOTE]
    > Якщо відображається повідомлення про те, що потрібно ввімкнути відстеження, перейдіть вперед і ввімкніть її зараз. Якщо цю функцію не активовано, результати пошуку не зможуть витягнути дані з попередніх дат.
1. Якщо вас цікавить певна дія, виберіть його зі списку **дії** ; в іншому разі за замовчуванням всі дії буде повернуто вибраному користувачу. Зверніть увагу, що деякі дії можуть бути недоступні для вибраного в меню " **дії** ". Проте ці елементи аудиту буде повернуто, якщо вибрано параметр **Відображати результати для всіх дій** (Настроювання за замовчуванням).
1. Укажіть проміжок часу, а потім у полі **користувачі** виберіть ім'я користувача, яке потрібно дослідити.
1. Виберіть елемент **Пошук**. Дії відображаються в розділі **результати**. IP-адресу для кожної дії можна переглянути.
1. Щоб переглянути відомості, виберіть потрібну дію, а потім виберіть пункт **додаткові відомості**.

Докладні відомості наведено в статті пошук у [журналі аудиту Office 365 для виправлення поширених сценаріїв](https://go.microsoft.com/fwlink/?linkid=2103944).
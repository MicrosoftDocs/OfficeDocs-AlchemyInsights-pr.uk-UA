---
title: Автоматичне шифрування певних повідомлень електронної пошти Office 365
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/24/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000078"
- "7342"
ms.openlocfilehash: e4b2f4ffcacf03e145b4c6d5ff6e73a75cb7c184
ms.sourcegitcommit: c202c0df2d141e63f4f7eb13a56efbfc2f57348f
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/05/2021
ms.locfileid: "50527615"
---
# <a name="automatically-encrypt-certain-office-365-email-messages"></a>Автоматичне шифрування певних повідомлень електронної пошти Office 365

Ви можете автоматично шифрувати повідомлення, які користувачі надсилають певним зовнішнім користувачам або організаціям. Для цього виконайте наведені нижче дії.

1. У [центрі адміністрування Exchange](https://outlook.office365.com/ecp/)виберіть пункт **правила передавання пошти >**. 
2. Клацніть піктограму **Створити (+)** , а потім виберіть команду "**Додати шифрування повідомлень Office 365" і "захист прав" до повідомлень**.
3. У полі **ім'я** введіть ім'я для правила, наприклад *шифрувати повідомлення, надіслані до DrToniRamos@gmail.com*.
4. У **разі використання цього правила, якщо** вибрати **одержувача > цей користувач**. 
5. У вікні **вибір учасників** виберіть ім'я особи, до якої потрібно застосувати правило шифрування, і натисніть кнопку **Додати**. 
6. Завершивши додавання користувачів, натисніть кнопку **OK**.
7. Поруч із полем **виконати наведені нижче дії** натисніть кнопку **вибрати один**. 
8. У розкривному меню **шаблон RMS** виберіть пункт **Зашифрувати**, а потім натисніть кнопку **OK**. (Якщо цей параметр не відображається, це означає, що план не містить автоматичного шифрування. Але його можна додати!)
9. Виберіть будь-яке необов'язкове виділення (зі списку необов'язкових варіантів, які можна зробити в цій точці, багато з яких можна використовувати за замовчуванням для простоти).
10. Натисніть кнопку **Зберегти**.

> [!IMPORTANT]
> Ви завжди можете повернутися та відредагувати це правило згодом.

Щоб отримати докладні відомості про створення правил для шифрування, Дізнайтеся, як [визначити правила передавання пошти для шифрування повідомлень електронної пошти в Office 365](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).

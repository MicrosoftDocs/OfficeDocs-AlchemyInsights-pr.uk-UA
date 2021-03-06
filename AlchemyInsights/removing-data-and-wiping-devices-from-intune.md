---
title: Видалення даних та стирання пристроїв з Intune
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/27/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1279"
- "6700008"
- "9004638"
- "8392"
ms.openlocfilehash: cada3c6f1e7d1dcd576baa1245fb5a62ed938613
ms.sourcegitcommit: 229bd519ec1c14c65a243226a94eee23e117a7fc
ms.translationtype: HT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/03/2021
ms.locfileid: "50416334"
---
# <a name="removing-data-and-wiping-devices-from-intune"></a>Видалення даних та стирання пристроїв з Intune

Віддалені дії "Списання пристрою" і "Стирання пристрою" можуть бути використані для видалення даних організації, якими керує Intune, або для скидання до заводських налаштувань та повернення пристрою до налаштувань за замовчуванням.

1. Увійдіть на інформаційну панель "Керування пристроями в Microsoft 365" та перейдіть у розділ **Пристрої** > **Усі пристрої**.
2. Виберіть пристрій, який необхідно стерти.
3. Виберіть тип віддаленого стирання. Списання видаляє лише організаційну інформацію, а повне стирання відновлює пристрій до заводських налаштувань.
4. Натисніть кнопку **Так** для підтвердження. Поки стирання не завершиться, у статусі дії пристрою відображатиметься *Триває списання*.
    Після завершення дії ви більше не бачитимете мобільний пристрій у списку керованих.

> [!NOTE]
> Дані організації не можна видалити з пристроїв, ПРИЄДНАНИХ до Microsoft Azure AD. 

Повну інформацію про ефект дій "Списати" та "Стерти", зокрема те, що збережено та що видалено, див. у таких документах:

- [Видалення пристроїв за допомогою функцій стирання, списання або відключення пристрою вручну](https://docs.microsoft.com/mem/intune/remote-actions/devices-wipe).
- [Як видалити лише корпоративні дані з керованих Intune програм](https://docs.microsoft.com/mem/intune/apps/apps-selective-wipe)
- [Видалення всіх даних із пристрою macOS](https://docs.microsoft.com/mem/intune/remote-actions/device-erase).
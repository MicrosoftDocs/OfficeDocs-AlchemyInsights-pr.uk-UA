---
title: Змінення Microsoft EDGE за допомогою змінних каталогів даних, а не жорстко-кодованих шляхів
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 03/19/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "8222"
- "9004596"
ms.openlocfilehash: 23ce69157c465c56d0fc5ada7c2c159e3192fd75
ms.sourcegitcommit: c08bed4071baa3bb5879496df3ed44fb828c8367
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/19/2021
ms.locfileid: "51036861"
---
# <a name="modify-microsoft-edge-by-using-data-directory-variables-rather-than-hard-coded-paths"></a>Змінення Microsoft EDGE за допомогою змінних каталогів даних, а не жорстко-кодованих шляхів

Наприклад, у Windows для зберігання даних профілю в розділі Локальні дані програми користувача, а не в розташуванні за замовчуванням, установіть політику *UserDataDir* to **$ {local_app_data} \Edge\Profile**.

Докладні відомості наведено в статті [створення змінних каталогів даних Microsoft EDGE](https://docs.microsoft.com/deployedge/microsoft-edge-policies).
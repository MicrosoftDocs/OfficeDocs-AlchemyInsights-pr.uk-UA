---
title: Код помилки 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: У разі появи повідомлення про помилку під час активації Office 2013 віддалений робочий стіл служб (РДС) розгортання, розглянути питання про включення ADAL шляхом редагування реєстру.
ms.openlocfilehash: e2249d8ebbd2313c64dda5656a3243fa76d97a9a
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 06/28/2019
ms.locfileid: "35388266"
---
У разі появи повідомлення про помилку під час активації Office 2013 віддалений робочий стіл служб (РДС) розгортання, розглянути питання про включення ADAL шляхом редагування реєстру.
  
|**Ключ реєстру**|**Тип**|**Значення**|
|:-----|:-----|:-----|
|HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL  <br/> |REG_DWORD  <br/> |1  <br/> |

Докладніше перегляньте [Увімкнути сучасних автентикації Office 2013 на пристроях Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).
  
> [!NOTE]
>  АДАЛІЯ типово увімкнено у Office 365 ProPlus і Office 2016. > віддалений робочий стіл служб (РДС) була названа служб терміналів.
  
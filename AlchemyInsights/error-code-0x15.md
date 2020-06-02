---
title: Код помилки 0x15
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Якщо ви отримуєте повідомлення про помилку під час активації Office 2013 на розгортання служб віддалених робочих столів (RDS), спробуйте увімкнути ADAL, редагуючи реєстр.
ms.openlocfilehash: 468d13e59602cf173ed2e17af44c66babfc28703
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506867"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a>Помилка під час активації Office 2013 на службах віддалених робочих столів

Якщо ви отримуєте повідомлення про помилку під час активації Office 2013 на розгортання служб віддалених робочих столів (RDS), спробуйте увімкнути ADAL, редагуючи реєстр.
  
|**Реєстру**|**Тип**|**Значення**|
|:-----|:-----|:-----|
|HKEY_CURRENT_USER \Software\Microsoft\Office\15.0\Common\Identity\EnableADAL  <br/> |REG_DWORD  <br/> |1  <br/> |

Щоб отримати додаткові відомості див. [Увімкнення сучасних автентифікації для Office 2013 на пристроях Windows](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).
  
> [!NOTE]
>  ADAL увімкнуто за промовчанням у програмах Microsoft 365 для підприємств і Office 2016. Служби віддалених робочих столів (RDS) раніше називали служби терміналів.
  
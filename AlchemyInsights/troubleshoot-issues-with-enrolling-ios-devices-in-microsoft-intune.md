---
title: Усунення несправностей із записуванням пристроїв iOS у Microsoft Intune
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d717bcc9-1cc1-44f6-b5e6-c1bc059c1973
ms.openlocfilehash: 14f7a897f0c7504db1b605485e170183c3a1afb2
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/15/2021
ms.locfileid: "51823484"
---
# <a name="troubleshoot-issues-with-enrolling-ios-devices-in-microsoft-intune"></a>Усунення несправностей із записуванням пристроїв iOS у Microsoft Intune

Перегляньте наведені нижче ресурси, щоб усунути проблему зараз. 
  
Деякі типові повідомлення про помилки та кроки з їх усунення:
  
- **Досягнуто максимальної потужності пристрою** Користувач має більше пристроїв, ніж максимальна кількість пристроїв. Перегляньте ці [документи, щоб видалити пристрій](https://docs.microsoft.com/intune/devices-wipe) або змінити обмеження для [пристрою](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).
    
- **Ця служба не підтримується. Немає політики членство.** Потрібно налаштувати або поновити службу push-сповіщень Apple. Перегляньте [цей документ,](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) щоб дізнатися, як це зробити. 
    
- **Неприпустимий тип ліцензії користувача або не розпізнано ім'я користувача:** Користувачу потрібно призначити ліцензію Intune або EMS. Перегляньте ці документи, щоб призначити ліцензію через: [Центр адміністрування Office](https://docs.microsoft.com/intune/licenses-assign) або портал [Azure.](https://docs.microsoft.com/azure/active-directory/license-users-groups)
    
Додаткові ресурси, які допоможуть вирішити вашу проблему:
  
1. На [порталі виправлення неполадок Intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) можна діагностувати та усунути поширені помилки входу. Перегляньте [цей документ,](https://docs.microsoft.com/intune/help-desk-operators) щоб дізнатися більше. 
    
2. Перегляньте ці документи, щоб отримати список типових помилок, які [](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) запобігають веденю та вирішене проблем із кожним [документом:](https://docs.microsoft.com/troubleshoot/mem/intune/troubleshoot-device-enrollment-in-intune)Посібник із виправлення неполадок і Виправлення неполадок.
    
3. [Дізнайтеся, як створити пристрої з iOS у Microsoft Intune.](https://docs.microsoft.com/intune/ios-enroll)
    


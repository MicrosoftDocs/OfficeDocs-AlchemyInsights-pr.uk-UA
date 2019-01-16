---
title: UPN синхронізацію вимкнено
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 2a3489fe-c2a8-4e43-96c2-be4b3c5e978c
ms.openlocfilehash: d00f10688ec775c22d60a9089e291c265ada46f1
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 01/15/2019
ms.locfileid: "28319843"
---
# <a name="upn-sync-disabled"></a><span data-ttu-id="9799d-102">UPN синхронізацію вимкнено</span><span class="sxs-lookup"><span data-stu-id="9799d-102">UPN sync disabled</span></span>

<span data-ttu-id="9799d-103">Якщо ви почали синхронізацію блакитні оголошення до 30 березня 2016 року запустити командлет наступні Azure оголошення PowerShell включити м'які матч UPN для організації лише:</span><span class="sxs-lookup"><span data-stu-id="9799d-103">If you started syncing to Azure AD before March 30, 2016, run the following Azure AD PowerShell cmdlet to enable UPN soft match for your organization only:</span></span>
  
 <span data-ttu-id="9799d-104">**Set-MsolDirSyncFeature-вирізняються EnableSoftMatchOnUpn-увімкнути $True**</span><span class="sxs-lookup"><span data-stu-id="9799d-104">**Set-MsolDirSyncFeature -Feature EnableSoftMatchOnUpn -Enable $True**</span></span>
  
<span data-ttu-id="9799d-105">М'які матч UPN автоматично ввімкнено для організацій, які почали синхронізацію блакитні оголошення або після 30 березня 2016.</span><span class="sxs-lookup"><span data-stu-id="9799d-105">UPN soft match is automatically turned on for organizations that started syncing to Azure AD on or after March 30, 2016.</span></span>
  
<span data-ttu-id="9799d-106">Щоб дізнатися більше про ввімкнення м'які матч на UPN та інші функції синхронізації, будь ласка, дивіться [Azure оголошення підключення служби синхронізації функції](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span><span class="sxs-lookup"><span data-stu-id="9799d-106">To learn more about enabling soft match on UPN and other sync features, please see [Azure AD Connect sync service features](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span></span>
  


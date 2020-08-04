---
title: Підключення сценаріїв PowerShell для Exchange Online
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "6069"
- "3500011"
ms.openlocfilehash: 34301e62a25e11c5d4c353166f8208ef74245dfa
ms.sourcegitcommit: 9e44b852d18a2816acac0aacb78cb99b4c114368
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 07/22/2020
ms.locfileid: "45423774"
---
# <a name="connecting-powershell-scripts-to-exchange-online"></a><span data-ttu-id="662cd-102">Підключення сценаріїв PowerShell для Exchange Online</span><span class="sxs-lookup"><span data-stu-id="662cd-102">Connecting PowerShell scripts to Exchange Online</span></span>

<span data-ttu-id="662cd-103">Базову автентифікацію в Exchange Online буде вилучено, а шлях вперед – підключення за допомогою автентифікації на основі сертифіката для сценаріїв і автоматичного завдання.</span><span class="sxs-lookup"><span data-stu-id="662cd-103">Basic Authentication in Exchange Online is going to be deprecated, and the way forward is to connect by using certificate-based authentication for scripts and unattended tasks.</span></span> <span data-ttu-id="662cd-104">Щоб дізнатися більше, ознайомтеся [з автентифікацією лише програми для автоматичної перевірки сценаріїв у МОДУЛІ EXO V2](https://docs.microsoft.com/powershell/exchange/app-only-auth-powershell-v2).</span><span class="sxs-lookup"><span data-stu-id="662cd-104">To learn more, see [App-only authentication for unattended scripts in the EXO V2 module](https://docs.microsoft.com/powershell/exchange/app-only-auth-powershell-v2).</span></span>
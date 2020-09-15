---
title: Виправлення неполадок із підказкою перевірки безпеки для виявлення шахрайства
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 96ebe3c5-66ea-4662-98b7-052c2181c2f3
ms.custom:
- "275"
- "3100004"
ms.openlocfilehash: e42b498070bf5d9bfc36110667da8cc0fd431524
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 09/14/2020
ms.locfileid: "47658431"
---
# <a name="troubleshooting-the-safety-tip-for-fraud-detection-checks"></a><span data-ttu-id="4aeba-102">Виправлення неполадок із підказкою перевірки безпеки для виявлення шахрайства</span><span class="sxs-lookup"><span data-stu-id="4aeba-102">Troubleshooting the safety tip for fraud detection checks</span></span>

<span data-ttu-id="4aeba-103">Якщо ви одержуєте підказку про безпеку, що вказує на те, що відправник не пройшов перевірку шахрайства, а також не може бути, а відправник не пройшов перевірку автентифікації DKIM або SPF.</span><span class="sxs-lookup"><span data-stu-id="4aeba-103">If you are getting a safety tip that says "The sender failed our fraud detection checks and may not be who they appear to be", then the sender failed to pass either DKIM or SPF authentication checks.</span></span> <span data-ttu-id="4aeba-104">Найкращим способом вирішення цієї проблеми є надання дозволу відправнику.</span><span class="sxs-lookup"><span data-stu-id="4aeba-104">The best method to resolve this is for the sender to authorize themselves.</span></span> <span data-ttu-id="4aeba-105">Якщо відправник надсилає від вашого імені, потрібно авторизувати їх, додавши IP-адресу відправника до запису SPF.</span><span class="sxs-lookup"><span data-stu-id="4aeba-105">If the sender is sending on your behalf, you need to authorize them by adding the sender's IP address to your SPF record.</span></span>
  
<span data-ttu-id="4aeba-106">Перегляньте [Виправлення неполадок із червоним (підозрілим) підказкою для виявлення шахрайства,](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) щоб отримати докладні відомості.</span><span class="sxs-lookup"><span data-stu-id="4aeba-106">See [Troubleshooting the red (suspicious) safety tip for fraud detection checks](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) for more info.</span></span>
  
<span data-ttu-id="4aeba-107">Нижче наведено кілька інших посилань, які можуть допомогти.</span><span class="sxs-lookup"><span data-stu-id="4aeba-107">Here are some other links that can help:</span></span>
  
- [<span data-ttu-id="4aeba-108">Принцип використання програми Microsoft (SPF) для запобігання спуфінгу</span><span class="sxs-lookup"><span data-stu-id="4aeba-108">How Microsoft uses sender policy framework (SPF) to prevent spoofing</span></span>](https://docs.microsoft.com/microsoft-365/security/office-365-security/how-office-365-uses-spf-to-prevent-spoofing)

- [<span data-ttu-id="4aeba-109">Настроювання SPF для запобігання спуфінгу</span><span class="sxs-lookup"><span data-stu-id="4aeba-109">Set up SPF to help prevent spoofing</span></span>](https://docs.microsoft.com/microsoft-365/security/office-365-security/set-up-spf-in-office-365-to-help-prevent-spoofing)

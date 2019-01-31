---
title: Виправлення неполадок для виявлення шахрайства, рада безпеки перевіряє
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 96ebe3c5-66ea-4662-98b7-052c2181c2f3
ms.openlocfilehash: 06a0b5b8d29052e6033de5938b8ea67ceabc9848
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 01/30/2019
ms.locfileid: "29658136"
---
# <a name="troubleshooting-the-safety-tip-for-fraud-detection-checks"></a><span data-ttu-id="6ff71-102">Виправлення неполадок для виявлення шахрайства, рада безпеки перевіряє</span><span class="sxs-lookup"><span data-stu-id="6ff71-102">Troubleshooting the safety tip for fraud detection checks</span></span>



<span data-ttu-id="6ff71-p101">Якщо ти отримую Безпека Підказка, яка говорить "відправник не вдалося наші чеки виявлення шахрайства і може не бути тим, ким вони, як видається, бути", а потім відправник не змогла пройти DKIM або SPF перевірки автентичності. Кращий спосіб вирішити це є для відправника авторизації себе. Якщо відправник надсилає від вашого імені, вам потрібно авторизувати їх, додавши IP адреса відправника до запису SPF.</span><span class="sxs-lookup"><span data-stu-id="6ff71-p101">If you are getting a safety tip that says "The sender failed our fraud detection checks and may not be who they appear to be", then the sender failed to pass either DKIM or SPF authentication checks. The best method to resolve this is for the sender to authorize themselves. If the sender is sending on your behalf, you need to authorize them by adding the sender's IP address to your SPF record.</span></span>
  
<span data-ttu-id="6ff71-106">Для отримання додаткової інформації див [усунення несправностей червоний (підозрілі) Безпека Підказка для виявлення шахрайства перевіряє](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) .</span><span class="sxs-lookup"><span data-stu-id="6ff71-106">See [Troubleshooting the red (suspicious) safety tip for fraud detection checks](https://blogs.msdn.microsoft.com/tzink/2016/11/02/troubleshooting-the-red-suspicious-safety-tip-for-fraud-detection-checks/) for more info.</span></span> 
  
<span data-ttu-id="6ff71-107">Ось кілька посилань, які можуть допомогти:</span><span class="sxs-lookup"><span data-stu-id="6ff71-107">Here are some other links that can help:</span></span>
  
- [<span data-ttu-id="6ff71-108">Як Office 365 використовує відправника політичні рамки (SPF) для запобігання підміни</span><span class="sxs-lookup"><span data-stu-id="6ff71-108">How Office 365 uses sender policy framework (SPF) to prevent spoofing</span></span>](https://docs.microsoft.com/office365/SecurityCompliance/how-office-365-uses-spf-to-prevent-spoofing)
    
- [<span data-ttu-id="6ff71-109">Настроювання SPF у службі Office 365 для запобігання підміни</span><span class="sxs-lookup"><span data-stu-id="6ff71-109">Set up SPF in Office 365 to help prevent spoofing</span></span>](https://docs.microsoft.com/office365/SecurityCompliance/set-up-spf-in-office-365-to-help-prevent-spoofing)
    


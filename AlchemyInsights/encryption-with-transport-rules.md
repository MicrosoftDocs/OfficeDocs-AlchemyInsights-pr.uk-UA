---
title: Шифрування за допомогою правил транспортування
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002635"
- "5154"
ms.openlocfilehash: 3f16c7e7be99a50cd57f47ea2801b3022c4aec95
ms.sourcegitcommit: 07725fcaf073f0ac145f98653b989afdb34c5ad0
ms.translationtype: HT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/28/2020
ms.locfileid: "43915284"
---
# <a name="encryption-with-transport-rules"></a><span data-ttu-id="d6ecf-102">Шифрування за допомогою правил транспортування</span><span class="sxs-lookup"><span data-stu-id="d6ecf-102">Encryption with transport rules</span></span>

<span data-ttu-id="d6ecf-103">У [Центрі адміністрування Exchange](https://go.microsoft.com/fwlink/p/?linkid=834822) (EAC) для активації шифрування повідомлень можна використовувати можливості шифрування повідомлень Office (OME) у правилах передавання пошти.</span><span class="sxs-lookup"><span data-stu-id="d6ecf-103">In the [Exchange Admin Center](https://go.microsoft.com/fwlink/p/?linkid=834822) (EAC), you can use Office Message Encryption(OME) capabilities in your mail flow rules to trigger message encryption.</span></span> <span data-ttu-id="d6ecf-104">Виберіть параметр правила транспортування **Застосувати шифрування повідомлень Office 365 і захист прав**.</span><span class="sxs-lookup"><span data-stu-id="d6ecf-104">Choose the **Apply Office 365 Message Encryption and rights protection** option on the Transport Rule condition.</span></span>

- <span data-ttu-id="d6ecf-105">Докладні відомості див. в статті [Визначення правила передавання пошти для шифрування](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).</span><span class="sxs-lookup"><span data-stu-id="d6ecf-105">For more information, see [Define Mail flow rule to encrypt](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).</span></span>

- <span data-ttu-id="d6ecf-106">У PowerShell скористайтеся командлетом [New-TransportRule](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email?view=o365-worldwide#use-exchange-online-powershell-to-create-a-mail-flow-rule-for-encrypting-email-messages-without-the-new-ome-capabilities) і задайте значення "$true" для параметра *ApplyOME*.</span><span class="sxs-lookup"><span data-stu-id="d6ecf-106">In Powershell, use the [New-TransportRule](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email?view=o365-worldwide#use-exchange-online-powershell-to-create-a-mail-flow-rule-for-encrypting-email-messages-without-the-new-ome-capabilities) cmdlet and set the *ApplyOME* parameter to $true.</span></span>

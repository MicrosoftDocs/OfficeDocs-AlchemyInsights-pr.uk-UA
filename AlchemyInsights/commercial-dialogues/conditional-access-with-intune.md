---
title: Використання умовного доступу за допомогою функції InTune
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "6700002"
- "7680"
ms.openlocfilehash: 6e86c6b4c9c6adcbeac504acd5a10f2139d04237
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/11/2021
ms.locfileid: "50749267"
---
# <a name="using-conditional-access-with-intune"></a><span data-ttu-id="f709a-102">Використання умовного доступу за допомогою функції InTune</span><span class="sxs-lookup"><span data-stu-id="f709a-102">Using Conditional Access with Intune</span></span>

<span data-ttu-id="f709a-103">Використання умовного доступу за допомогою функції Inune вимагає 3 кроків:</span><span class="sxs-lookup"><span data-stu-id="f709a-103">Using Conditional Access with Intune requires 3 steps:</span></span>

- [<span data-ttu-id="f709a-104">Створіть політику відповідності, щоб визначити параметри, які потрібно виконати перед тим, як пристрій вважається сумісним. Наприклад, для пристрою має бути PIN-код принаймні на 6 цифр, перш ніж вона вважається відповідним.</span><span class="sxs-lookup"><span data-stu-id="f709a-104">Create a Compliance Policy to define settings that must be met before the device is considered compliant. For example, a device must have a pin of at least 6 digits before it is considered compliant.</span></span>](https://docs.microsoft.com/mem/intune/protect/create-compliance-policy)
- [<span data-ttu-id="f709a-105">Створіть політику умовного доступу, яка визначає, які ресурси захищено, і які умови потрібно виконати для доступу до цих ресурсів. Наприклад, пристрій має бути сумісним, перш ніж отримувати доступ до корпоративної електронної пошти.</span><span class="sxs-lookup"><span data-stu-id="f709a-105">Create a Conditional Access Policy that defines what resources are being protected, and what conditions need to be met to access those resources. For example, a device must be compliant before accessing corporate email.</span></span>](https://docs.microsoft.com/mem/intune/protect/tutorial-protect-email-on-unmanaged-devices#create-conditional-access-policies)
- [<span data-ttu-id="f709a-106">Переконайтеся, що політики відповідності та політики умовного доступу орієнтовані на потрібні групи користувачів. Для цього може знадобитися створити певні групи користувачів у службі Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="f709a-106">Ensure both Compliance Policies and Conditional Access Policies are targeted to the desired groups of users. This may require creating specific groups of users in Azure Active Directory.</span></span>](https://docs.microsoft.com/troubleshoot/mem/intune/troubleshoot-conditional-access)

[<span data-ttu-id="f709a-107">Докладніше...</span><span class="sxs-lookup"><span data-stu-id="f709a-107">Read more...</span></span>](https://docs.microsoft.com/mem/intune/protect/device-compliance-get-started)

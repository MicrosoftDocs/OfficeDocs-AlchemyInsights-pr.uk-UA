---
title: Ключі відновлення BitLocker
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1922"
- "9000220"
ms.openlocfilehash: 4e06e0e43b63836b9e9cf923e554dd474b82c671
ms.sourcegitcommit: 123e9fe46e99719dd271e75a66555861e968f4a2
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 12/30/2019
ms.locfileid: "40908835"
---
# <a name="accessing-bitlocker-recovery-keys"></a><span data-ttu-id="c0d8c-102">Доступ до ключів відновлення BitLocker</span><span class="sxs-lookup"><span data-stu-id="c0d8c-102">Accessing Bitlocker recovery keys</span></span>

<span data-ttu-id="c0d8c-103">Під час настроювання параметрів BitLocker, InTune endPoint Protection політики, можна визначити, чи слід зберігати відомості відновлення BitLocker в Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="c0d8c-103">When configuring Bitlocker settings Intune Endpoint Protection Policy, it is possible to define whether Bitlocker recovery information should be stored in Azure Active Directory.</span></span>

<span data-ttu-id="c0d8c-104">Якщо цей параметр налаштовано, дані для відновлення зберігаються на InTune адміністратора як частину даних запису пристрою в InTune пристроїв Blade двома способами:</span><span class="sxs-lookup"><span data-stu-id="c0d8c-104">If that setting is configured, the stored recovery data should be visible to an Intune admin as part of the device record data in Intune Devices blade in two ways:</span></span>

<span data-ttu-id="c0d8c-105">Пристрої-Azure AD-пристрої > "пристрій" або пристрої-> всі пристрої-> "пристрій"-> відновлення ключів</span><span class="sxs-lookup"><span data-stu-id="c0d8c-105">Devices - Azure AD devices -> "Device"  OR Devices -> All Devices -> "Device" -> Recovery keys</span></span>

<span data-ttu-id="c0d8c-106">Крім того, якщо є адміністративний доступ до самого пристрою, ключ відновлення (пароль) можна побачити, виконавши таку команду в командному рядку в режимі адміністратора:</span><span class="sxs-lookup"><span data-stu-id="c0d8c-106">Alternatively, if there is administrative access to the device itself, the recovery key (Password) can be seen by running the following command from an elevated command prompt:</span></span>

```
manage-bde -protectors c: -get
Example
Volume C: []
All Key Protectors
    TPM:
      ID: {8A5D13D6-7ED9-46C8-A74F-AC3ADF016EC8}
      PCR Validation Profile:
        0, 2, 4, 8, 9, 10, 11
    Numerical Password:
      ID: {DFA26333-XXXX-402C-YYYY-A8C40AF3ZZZZ}
      Password:
        393943-22222-281721-555554-577984-77777-194700-99999
```
<span data-ttu-id="c0d8c-107">Якщо пристрій було зашифровано до зарахування в InTune, ключ відновлення може бути пов'язано з "обліковий запис Microsoft" (MSA), який використовується для входу на пристрій під час першого запуску.</span><span class="sxs-lookup"><span data-stu-id="c0d8c-107">If the device was encrypted prior to enrolment in Intune, the recovery key may have been associated with the "Microsoft Account" (MSA) used to sign in to the device during the OOBE process.</span></span> <span data-ttu-id="c0d8c-108">Якщо це так, доступ https://onedrive.live.com/recoverykey і вхід в с, що MSA повинні показати пристрої, для яких були збережені ключі відновлення.</span><span class="sxs-lookup"><span data-stu-id="c0d8c-108">If that was the case, accessing  https://onedrive.live.com/recoverykey and signing in with that MSA should show the devices for which recovery keys were stored.</span></span>
 
<span data-ttu-id="c0d8c-109">Якщо пристрій було зашифровано в результаті конфігурації за допомогою доменної групової політики, відомості про відновлення можуть зберігатися в локально Active Directory.</span><span class="sxs-lookup"><span data-stu-id="c0d8c-109">If the device was encrypted as a result of configuration through domain-based group policy, the recovery information may be stored in the on-premise Active Directory.</span></span>
 


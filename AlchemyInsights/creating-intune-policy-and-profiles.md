---
title: Створення політики та профілів для InTune
ms.author: mandia
author: mandia
manager: dougeby
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1064"
- "6700005"
ms.openlocfilehash: af8f1a3dfaccaca52f187f387274d63b22631b2d
ms.sourcegitcommit: 0eb4f9bde53395b5fd4b5cd4ffc56ca96db91298
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/10/2021
ms.locfileid: "50704663"
---
# <a name="creating-intune-policy-and-profiles"></a><span data-ttu-id="045c9-102">Створення політики та профілів Inune</span><span class="sxs-lookup"><span data-stu-id="045c9-102">Creating Intune policy and profiles</span></span>

<span data-ttu-id="045c9-103">У програмі Inune можна створювати політики та профілі, які роблять різні дії.</span><span class="sxs-lookup"><span data-stu-id="045c9-103">In Intune, you can create policies and profiles that do different things.</span></span>

- <span data-ttu-id="045c9-104">**Профілі реєстрації**: попередньо налаштуйте свої пристрої за допомогою платформи, увімкніть близькість користувачів, використовуйте багатофакторну автентифікацію та багато іншого.</span><span class="sxs-lookup"><span data-stu-id="045c9-104">**Enrollment profiles**: Preconfigure your devices by platform, enable user affinity, use multi-factor authentication, and more.</span></span>

  <span data-ttu-id="045c9-105">[Що таке Реєстрація пристроїв](https://docs.microsoft.com/intune/device-enrollment)і створення профілів реєстрації для [Android](https://docs.microsoft.com/intune/android-enroll), [IOS](https://docs.microsoft.com/intune/ios-enroll), [macOS](https://docs.microsoft.com/intune/macos-enroll)і [Windows](https://docs.microsoft.com/intune/windows-enrollment-methods) – корисні ресурси.</span><span class="sxs-lookup"><span data-stu-id="045c9-105">[What is device enrollment](https://docs.microsoft.com/intune/device-enrollment), and create enrollment profiles for [Android](https://docs.microsoft.com/intune/android-enroll), [iOS](https://docs.microsoft.com/intune/ios-enroll), [macOS](https://docs.microsoft.com/intune/macos-enroll), and [Windows](https://docs.microsoft.com/intune/windows-enrollment-methods) are good resources.</span></span>

- <span data-ttu-id="045c9-106">**Політики відповідності**: Визначте правила та настройки, які пристрої мають стежити, щоб бути сумісними.</span><span class="sxs-lookup"><span data-stu-id="045c9-106">**Compliance policies**: Define the rules and settings that devices must follow to be compliant.</span></span> <span data-ttu-id="045c9-107">Ви також можете використовувати політики відповідності для відстеження пристроїв і сповіщати користувачів про недотримання.</span><span class="sxs-lookup"><span data-stu-id="045c9-107">You can also use compliance policies to monitor devices, and notify users of non-compliance.</span></span>

  <span data-ttu-id="045c9-108">Початок роботи з [політиками відповідності для пристроїв](https://docs.microsoft.com/intune/device-compliance-get-started).</span><span class="sxs-lookup"><span data-stu-id="045c9-108">Get started with [device compliance policies](https://docs.microsoft.com/intune/device-compliance-get-started).</span></span>
- <span data-ttu-id="045c9-109">**Політики умовного доступу**: захист організаційних ресурсів залежно від введених умов.</span><span class="sxs-lookup"><span data-stu-id="045c9-109">**Conditional access policies**: Help secure organizational resources, depending on conditions that you enter.</span></span> <span data-ttu-id="045c9-110">Наприклад, щоб обмежити доступ до електронної пошти та SharePoint, використовуйте умовний доступ для пристроїв, які не сумісні.</span><span class="sxs-lookup"><span data-stu-id="045c9-110">For example, for devices that aren't compliant, use conditional access to restrict access to email and SharePoint.</span></span>

  <span data-ttu-id="045c9-111">[Що таке умовний доступ](https://docs.microsoft.com/intune/conditional-access) і [загальні способи використання умовного доступу](https://docs.microsoft.com/intune/conditional-access-intune-common-ways-use) – це гарні ресурси для початку роботи.</span><span class="sxs-lookup"><span data-stu-id="045c9-111">[What is conditional access](https://docs.microsoft.com/intune/conditional-access) and [common ways to use conditional access](https://docs.microsoft.com/intune/conditional-access-intune-common-ways-use) are good resources to get started.</span></span>

- <span data-ttu-id="045c9-112">**Профілі конфігурації**: керування функціями та параметрами на пристроях, включно з параметрами електронної пошти, додавання мережі Wi-Fi, використання вбудованих шаблонів, керування IOS і функціями macOS пристроїв тощо.</span><span class="sxs-lookup"><span data-stu-id="045c9-112">**Configuration profiles**: Manage features and settings on devices, including email settings, add a WiFi network, use built-in templates, control iOS and macOS device features, and more.</span></span>

  <span data-ttu-id="045c9-113">Початок роботи на [профілях конфігурації пристроїв](https://docs.microsoft.com/intune/device-profiles).</span><span class="sxs-lookup"><span data-stu-id="045c9-113">Get started at [device configuration profiles](https://docs.microsoft.com/intune/device-profiles).</span></span>

<span data-ttu-id="045c9-114">Корисні посилання:</span><span class="sxs-lookup"><span data-stu-id="045c9-114">Helpful links:</span></span>

- [<span data-ttu-id="045c9-115">Поширені запитання, проблеми та резолюції з політиками пристроїв і профілями в InTune</span><span class="sxs-lookup"><span data-stu-id="045c9-115">Common questions, issues, and resolutions with device policies and profiles in Intune</span></span>](https://docs.microsoft.com/intune/device-profile-troubleshoot)

- [<span data-ttu-id="045c9-116">Усунення несправностей політики та профілів в програмі Inune</span><span class="sxs-lookup"><span data-stu-id="045c9-116">Troubleshoot policies and profiles in Intune</span></span>](https://docs.microsoft.com/troubleshoot/mem/intune/troubleshoot-policies-in-microsoft-intune)

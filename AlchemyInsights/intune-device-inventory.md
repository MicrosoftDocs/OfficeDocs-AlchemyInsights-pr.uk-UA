---
title: InTune пристрій інвентаризації
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/27/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1281"
- "6700008"
ms.openlocfilehash: d59ee014a64de39d01837e90909619f30ec35e89
ms.sourcegitcommit: e34bb95fb93250f1dc7aec6a13578bb3bb355935
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 07/28/2020
ms.locfileid: "45440481"
---
# <a name="intune-device-inventory"></a><span data-ttu-id="dc344-102">InTune пристрій інвентаризації</span><span class="sxs-lookup"><span data-stu-id="dc344-102">Intune Device Inventory</span></span>

<span data-ttu-id="dc344-103">Лезо «пристрої» надає адміністратору уявлення про пристрої в розділі керування в InTune на основі кожного пристрою.</span><span class="sxs-lookup"><span data-stu-id="dc344-103">The Devices blade provides the administrator insight into devices under management in Intune on a per device basis.</span></span> <span data-ttu-id="dc344-104">Наведені відомості включають: Устаткування, виявлені програми, стан відповідності пристрою та стан конфігурації пристрою.</span><span class="sxs-lookup"><span data-stu-id="dc344-104">The information shown includes: Hardware, Discovered applications, Device Compliance state, and Device Configuration state.</span></span>

<span data-ttu-id="dc344-105">Дані про запаси обладнання та виявлені програми збираються на семиденний цикл.</span><span class="sxs-lookup"><span data-stu-id="dc344-105">Inventory data for hardware and discovered applications is collected on a seven-day cycle.</span></span> <span data-ttu-id="dc344-106">Програми та конкретні елементи апаратних повідомили відрізняються в залежності від операційної системи пристрою і чи є пристрій особисто або корпоративною власністю.</span><span class="sxs-lookup"><span data-stu-id="dc344-106">The applications and specific elements of hardware reported differ depending on the device operating system and whether the device is personally or corporate owned.</span></span>

<span data-ttu-id="dc344-107">Докладніші відомості наведено в переглянути [відомості про пристрій у InTune](https://docs.microsoft.com/intune/device-inventory).</span><span class="sxs-lookup"><span data-stu-id="dc344-107">For more information, see [See device details in Intune](https://docs.microsoft.com/intune/device-inventory).</span></span>

<span data-ttu-id="dc344-108">**Запитання й відповіді**</span><span class="sxs-lookup"><span data-stu-id="dc344-108">**FAQ**</span></span>

<span data-ttu-id="dc344-109">Q: я не отримую повний список інвентаризації програм, присутніх на InTune-надійшло пристроїв Windows.</span><span class="sxs-lookup"><span data-stu-id="dc344-109">Q: I am not receiving a full inventory list of applications present on Intune-enrolled Windows devices.</span></span> <span data-ttu-id="dc344-110">Чому ні?</span><span class="sxs-lookup"><span data-stu-id="dc344-110">Why not?</span></span>

<span data-ttu-id="dc344-111">В: на даний момент, тільки сучасні програми перераховані для Windows 10 ПК, які визначені як корпоративні пристрої.</span><span class="sxs-lookup"><span data-stu-id="dc344-111">A: At this time, only modern apps are listed for Windows 10 PCs that are identified as corporate devices.</span></span> <span data-ttu-id="dc344-112">InTune не збирає відомості про додатки Win32, інстальовані на цих пристроях.</span><span class="sxs-lookup"><span data-stu-id="dc344-112">Intune doesn't collect information about Win32 apps installed on these devices.</span></span>

<span data-ttu-id="dc344-113">Q: чому номери телефонів не збираються з усіх пристроїв?</span><span class="sxs-lookup"><span data-stu-id="dc344-113">Q: Why are phone numbers not collected from all devices?</span></span>

<span data-ttu-id="dc344-114">В: телефони, які класифікуються як корпоративні пристрої в InTune не визначені з їх повний номер телефону, коли, наприклад, ви запускаєте мобільного пристрою інвентаризації звіт.</span><span class="sxs-lookup"><span data-stu-id="dc344-114">A: Phones categorized as corporate devices in Intune are not identified with their full phone number when, for example, you run a mobile device inventory report.</span></span> <span data-ttu-id="dc344-115">Номери телефонів із власним пристроєм завжди частково маскуються зірочками (\* \* \* \*) і показують лише останні чотири цифри.</span><span class="sxs-lookup"><span data-stu-id="dc344-115">Bring-you-own-device phone numbers are always partially masked with asterisks (\*\*\*\*), and show only the last four digits.</span></span>
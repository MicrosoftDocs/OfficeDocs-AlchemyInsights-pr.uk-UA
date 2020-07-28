---
title: Пошук втрачених пристроїв iOS з InTune
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
- "1283"
- "6700008"
ms.openlocfilehash: faaea65c7edc345bb676d2fb266e20f85ba2cbe5
ms.sourcegitcommit: e34bb95fb93250f1dc7aec6a13578bb3bb355935
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 07/28/2020
ms.locfileid: "45440433"
---
# <a name="locating-lost-ios-devices-with-intune"></a><span data-ttu-id="7caab-102">Пошук втрачених пристроїв iOS з InTune</span><span class="sxs-lookup"><span data-stu-id="7caab-102">Locating lost iOS devices with Intune</span></span>

<span data-ttu-id="7caab-103">Увімкнення втраченого режиму на пристрої iOS дозволяє адміністратору мати повідомлення та контактний номер телефону, який відображається на екрані блокування.</span><span class="sxs-lookup"><span data-stu-id="7caab-103">Enabling lost mode on an iOS device allows an administrator to have a message and contact phone number displayed on the lock screen.</span></span>

<span data-ttu-id="7caab-104">Після того, як втрачений режим увімкнуто, адміністратор може використовувати дію "знайти пристрій" для визначення фізичного розташування пристрою.</span><span class="sxs-lookup"><span data-stu-id="7caab-104">After lost mode is enabled the admin can use the Locate device action to identify the physical location of the device.</span></span>

<span data-ttu-id="7caab-105">Дія "знайти пристрій" у InTune працює з пристроями iOS, щоб відобразити розташування певного пристрою на карті.</span><span class="sxs-lookup"><span data-stu-id="7caab-105">The Locate device action in Intune works with iOS devices to show the location of a specific device on a map.</span></span>

<span data-ttu-id="7caab-106">За допомогою цієї дії потрібно, щоб пристрій iOS був у:</span><span class="sxs-lookup"><span data-stu-id="7caab-106">Using this action requires the iOS device to be in:</span></span>

- <span data-ttu-id="7caab-107">Режим спостереження</span><span class="sxs-lookup"><span data-stu-id="7caab-107">Supervised mode</span></span>
- <span data-ttu-id="7caab-108">Втрачений режим</span><span class="sxs-lookup"><span data-stu-id="7caab-108">Lost mode</span></span>

<span data-ttu-id="7caab-109">Для отримання додаткових відомостей див. [Увімкнути втрачений режим на пристроях IOS/Ipадос з InTune](https://docs.microsoft.com/intune/device-lost-mode) та [знайти втрачені або вкрадені пристрої IOS/ipадос з InTune](https://docs.microsoft.com/intune/device-locate).</span><span class="sxs-lookup"><span data-stu-id="7caab-109">For more info, see [Enable lost mode on iOS/iPadOS devices with Intune](https://docs.microsoft.com/intune/device-lost-mode) and [Locate lost or stolen iOS/iPadOS devices with Intune](https://docs.microsoft.com/intune/device-locate).</span></span>

<span data-ttu-id="7caab-110">**Запитання й відповіді**</span><span class="sxs-lookup"><span data-stu-id="7caab-110">**FAQ**</span></span>

<span data-ttu-id="7caab-111">Q: я видав віддалену дію, щоб видалити дані компанії з пристрою, і тепер він застряг у стані очікування.</span><span class="sxs-lookup"><span data-stu-id="7caab-111">Q: I issued a remote action to remove company data from a device, and now it’s stuck in a pending state.</span></span>

<span data-ttu-id="7caab-112">В: для віддаленої дії, щоб успішно завершити, цільовий пристрій повинен бути онлайн і здоровим.</span><span class="sxs-lookup"><span data-stu-id="7caab-112">A: For a remote action to successfully complete, the targeted device must be online and healthy.</span></span> <span data-ttu-id="7caab-113">У таких ситуаціях Віддалена дія залишається в стані очікування протягом 30 днів або поки пристрій не визнає команду:</span><span class="sxs-lookup"><span data-stu-id="7caab-113">In the following situations, the remote action stays in a pending state for 30 days, or until the device acknowledges the command:</span></span>

- <span data-ttu-id="7caab-114">Коли пристрій не має підключення</span><span class="sxs-lookup"><span data-stu-id="7caab-114">When the device does not have connectivity</span></span>
- <span data-ttu-id="7caab-115">Коли пристрій втрачає статус керування за допомогою InTune</span><span class="sxs-lookup"><span data-stu-id="7caab-115">When the device loses its management status with Intune</span></span>

<span data-ttu-id="7caab-116">Якщо ви вважаєте, що пристрій більше не перевірятися, і що він не зможе видалити дані компанії, виберіть Видалити.</span><span class="sxs-lookup"><span data-stu-id="7caab-116">If you think a device is no longer checking in, and that it won’t be able to remove company data, select Delete.</span></span> <span data-ttu-id="7caab-117">Видалення видаляє запис пристрою так, що він більше не відображається у списку InTune пристроїв.</span><span class="sxs-lookup"><span data-stu-id="7caab-117">Deleting removes the device record so that it no longer appears in the Intune list of devices.</span></span> <span data-ttu-id="7caab-118">Якщо пристрій знову стає активним, його потрібно буде повторно зареєструвати.</span><span class="sxs-lookup"><span data-stu-id="7caab-118">If the device becomes active again, its user will have to re-enroll it.</span></span>

<span data-ttu-id="7caab-119">П: чому деякі віддалені дії недоступні для мене?</span><span class="sxs-lookup"><span data-stu-id="7caab-119">Q: Why are certain remote actions not available for me to use?</span></span>

<span data-ttu-id="7caab-120">В: не всі платформи підтримують всі дії з віддаленим пристроєм.</span><span class="sxs-lookup"><span data-stu-id="7caab-120">A: Not all platforms support all remote device actions.</span></span> <span data-ttu-id="7caab-121">Такі віддалені дії є специфічними для платформи, тому вони доступні лише для платформ.</span><span class="sxs-lookup"><span data-stu-id="7caab-121">The following remote actions are platform-specific, so they are available only for the platforms noted.</span></span>

- <span data-ttu-id="7caab-122">Обхід блокування активації (лише для iOS)</span><span class="sxs-lookup"><span data-stu-id="7caab-122">Bypass Activation Lock (iOS only)</span></span>
- <span data-ttu-id="7caab-123">Чистий запуск (лише для Windows)</span><span class="sxs-lookup"><span data-stu-id="7caab-123">Fresh Start (Windows only)</span></span>
- <span data-ttu-id="7caab-124">Втрачений режим (лише для iOS)</span><span class="sxs-lookup"><span data-stu-id="7caab-124">Lost mode (iOS only)</span></span>
- <span data-ttu-id="7caab-125">Пошук пристрою (лише для iOS)</span><span class="sxs-lookup"><span data-stu-id="7caab-125">Locate device (iOS only)</span></span>
- <span data-ttu-id="7caab-126">Перезапустити (лише для Windows)</span><span class="sxs-lookup"><span data-stu-id="7caab-126">Restart (Windows only)</span></span>

<span data-ttu-id="7caab-127">Щоб отримати докладніші відомості про кожну дію, перегляньте [доступні дії пристрою](https://docs.microsoft.com/intune/device-management#available-device-actions).</span><span class="sxs-lookup"><span data-stu-id="7caab-127">For more details about each action, see [Available device actions](https://docs.microsoft.com/intune/device-management#available-device-actions).</span></span>
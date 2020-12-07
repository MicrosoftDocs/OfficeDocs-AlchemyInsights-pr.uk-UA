---
title: Настроювання параметрів політики в Microsoft EDGE у Windows
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 12/05/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003845"
- "6894"
ms.openlocfilehash: 7f626152c3833638436dfe05e8dcd13fc86ef594
ms.sourcegitcommit: 2e4a5153e530bf15744a52e982eeb0d99757e9d2
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 12/04/2020
ms.locfileid: "49583749"
---
# <a name="configure-microsoft-edge-policy-settings-on-windows"></a><span data-ttu-id="5ad8e-102">Настроювання параметрів політики в Microsoft EDGE у Windows</span><span class="sxs-lookup"><span data-stu-id="5ad8e-102">Configure Microsoft Edge policy settings on Windows</span></span>

<span data-ttu-id="5ad8e-103">Щоб настроїти параметри політики та керовані оновлення для Microsoft EDGE, використовуйте об'єкти групової політики (GPOs).</span><span class="sxs-lookup"><span data-stu-id="5ad8e-103">To configure policy settings and managed updates for Microsoft Edge, use Group Policy Objects (GPOs).</span></span> <span data-ttu-id="5ad8e-104">Ви також можете підготувати політику через реєстр; Це буде доречним для (1) пристроїв із Windows, підключеному до домену Active Directory, а також для (2) Windows 10 Pro і Enterprise екземплярів, зарахованих для керування пристроями в Microsoft InTune.</span><span class="sxs-lookup"><span data-stu-id="5ad8e-104">You can also provision policy through the registry; this would be appropriate for (1) Windows devices joined to a Microsoft Active Directory domain and for (2) Windows 10 Pro and Enterprise instances enrolled for device management in Microsoft Intune.</span></span>

<span data-ttu-id="5ad8e-105">Щоб настроїти Microsoft EDGE за допомогою GPOs, виконайте наведені нижче дії.</span><span class="sxs-lookup"><span data-stu-id="5ad8e-105">To configure Microsoft Edge by using GPOs, do the following:</span></span>

1. <span data-ttu-id="5ad8e-106">У центральному сховищі групової політики в домені Active Directory або в папку шаблон визначення політики на окремих комп'ютерах інсталюйте всі адміністративні шаблони, які додають правила та настройки для Microsoft EDGE.</span><span class="sxs-lookup"><span data-stu-id="5ad8e-106">To the Group Policy Central Store in your Active Directory domain, or to the Policy Definition template folder on individual computers, install all administrative templates that add rules and settings for Microsoft Edge.</span></span>
2. <span data-ttu-id="5ad8e-107">Настройте певні політики, які потрібно встановити.</span><span class="sxs-lookup"><span data-stu-id="5ad8e-107">Configure the specific policies you want to set.</span></span>

<span data-ttu-id="5ad8e-108">Докладні відомості можна знайти в статті [Настроювання параметрів політики Microsoft EDGE у Windows](https://go.microsoft.com/fwlink/?linkid=2135024).</span><span class="sxs-lookup"><span data-stu-id="5ad8e-108">To learn more, see [Configure Microsoft Edge policy settings on Windows](https://go.microsoft.com/fwlink/?linkid=2135024).</span></span>

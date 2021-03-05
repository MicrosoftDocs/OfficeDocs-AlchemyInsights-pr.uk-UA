---
title: Вимкнення перевірки мережі
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/25/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001464"
- "3492"
ms.openlocfilehash: 7b0f5c21a7e6afda0ee3000e75ee725cbadcedb7
ms.sourcegitcommit: 6741a997fff871d263f92d3ff7fb61e7755956a9
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/04/2021
ms.locfileid: "50483001"
---
# <a name="disable-network-scan"></a><span data-ttu-id="1849c-102">Вимкнення перевірки мережі</span><span class="sxs-lookup"><span data-stu-id="1849c-102">Disable network scan</span></span>

<span data-ttu-id="1849c-103">Сканування мережного спільного доступу може вплинути на продуктивність.</span><span class="sxs-lookup"><span data-stu-id="1849c-103">Network share scans may impact performance.</span></span>  <span data-ttu-id="1849c-104">Щоб переконатися, що клієнт не сканує спільний доступ до мережі або файли за замовчуванням, настройте наведені нижче параметри в програмі захисника Windows, щоб мати **значення TRUE**.</span><span class="sxs-lookup"><span data-stu-id="1849c-104">To ensure the client does not scan network shares/files by default, configure the following settings in the Windows Defender application to **True**:</span></span>

- <span data-ttu-id="1849c-105">Посилання на елементи, які не вдалося переглянути</span><span class="sxs-lookup"><span data-stu-id="1849c-105">DisableScanningMappedNetworkDrivesForFullScan</span></span>
- <span data-ttu-id="1849c-106">Файли, які не мають параметрів</span><span class="sxs-lookup"><span data-stu-id="1849c-106">DisableScanningNetworkFiles</span></span>
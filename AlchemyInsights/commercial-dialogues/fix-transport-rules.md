---
title: Виправлення правил транспортування
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
- "9000760"
- "7391"
ms.openlocfilehash: 635009ed4b78d2b05b0eef1f3298765b10f86ede
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/11/2021
ms.locfileid: "50750570"
---
# <a name="fix-transport-rules"></a><span data-ttu-id="2b343-102">Виправлення правил транспортування</span><span class="sxs-lookup"><span data-stu-id="2b343-102">Fix transport rules</span></span>

<span data-ttu-id="2b343-103">Це повідомлення вплинуло на настроюване правило потоку пошти.</span><span class="sxs-lookup"><span data-stu-id="2b343-103">A custom mail flow rule affected this message.</span></span> <span data-ttu-id="2b343-104">Щоб переглянути точне правило, виконайте наведені нижче дії.</span><span class="sxs-lookup"><span data-stu-id="2b343-104">To review the exact rule, do the following:</span></span>

1. <span data-ttu-id="2b343-105">У результатах надсилання в розділі **додаткові відомості** зверніть увагу на **ідентифікатор GUID** або **ім'я політики**.</span><span class="sxs-lookup"><span data-stu-id="2b343-105">In the submission results, under **Additional information**, note the **GUID** or the **Policy Name**.</span></span>
2. <span data-ttu-id="2b343-106">Запуск оболонки керування Exchange.</span><span class="sxs-lookup"><span data-stu-id="2b343-106">Launch Exchange Management Shell.</span></span> <span data-ttu-id="2b343-107">Докладні відомості наведено в статті [відкриття оболонки керування Exchange](https://go.microsoft.com/fwlink/?linkid=2101432).</span><span class="sxs-lookup"><span data-stu-id="2b343-107">For more information, see [Open the Exchange Management Shell](https://go.microsoft.com/fwlink/?linkid=2101432).</span></span>
3. <span data-ttu-id="2b343-108">Виконати цю команду (за допомогою ідентифікатора GUID у поданні):  **Get-Transportule-ідентичність "GUID" | FL \* Опис**\*</span><span class="sxs-lookup"><span data-stu-id="2b343-108">Run this command (using the GUID from your submission):  **Get-TransportRule -identity "GUID" | fl \* Description**\*</span></span>
4. <span data-ttu-id="2b343-109">Перегляньте опис, щоб переглянути настроєні умови, які вплинули на повідомлення.</span><span class="sxs-lookup"><span data-stu-id="2b343-109">Review the description to see the configured conditions that affected the message.</span></span>

<span data-ttu-id="2b343-110">Щоб дізнатися більше, перегляньте статтю [Get-TransportRule](https://go.microsoft.com/fwlink/?linkid=2101523).</span><span class="sxs-lookup"><span data-stu-id="2b343-110">To learn more, see [Get-TransportRule](https://go.microsoft.com/fwlink/?linkid=2101523).</span></span>
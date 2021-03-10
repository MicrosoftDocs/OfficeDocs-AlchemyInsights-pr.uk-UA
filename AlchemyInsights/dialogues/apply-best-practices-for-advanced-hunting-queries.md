---
title: Застосування передового досвіду для розширених запитів на полювання
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
ms.openlocfilehash: cd13e2e8801db3df91140ce371813d900d72e38b
ms.sourcegitcommit: bd6a9cb5d357baee5134c0dea430afc2a035c810
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/09/2021
ms.locfileid: "50696079"
---
# <a name="apply-best-practices-for-advanced-hunting-queries"></a><span data-ttu-id="0bef9-102">Застосування передового досвіду для розширених запитів на полювання</span><span class="sxs-lookup"><span data-stu-id="0bef9-102">Apply best practices for advanced hunting queries</span></span>

<span data-ttu-id="0bef9-103">Щоб швидше отримати результати, а щоб уникнути часу очікування під час виконання складних запитів, використовуйте ці рекомендації:</span><span class="sxs-lookup"><span data-stu-id="0bef9-103">To get results faster and to avoid timeouts while running complex queries, apply these best practices:</span></span>

- <span data-ttu-id="0bef9-104">Під час спроби отримати нові запити завжди використовуйте обмеження, щоб уникнути появи дуже великих результатів.</span><span class="sxs-lookup"><span data-stu-id="0bef9-104">When trying new queries, always use a limit, to avoid getting extremely large result sets.</span></span> <span data-ttu-id="0bef9-105">Крім того, використовуйте, `count` щоб зробити початкову оцінку розміру результуючий набір.</span><span class="sxs-lookup"><span data-stu-id="0bef9-105">Also, use `count` to make an initial assessment of the result set's size.</span></span>
- <span data-ttu-id="0bef9-106">Спочатку використовуйте фільтри часу.</span><span class="sxs-lookup"><span data-stu-id="0bef9-106">Use time filters first.</span></span> <span data-ttu-id="0bef9-107">У ідеалі Обмежте запити до семи днів.</span><span class="sxs-lookup"><span data-stu-id="0bef9-107">Ideally, limit your queries to seven days.</span></span>
- <span data-ttu-id="0bef9-108">На початку запиту одразу після фільтра часу додайте фільтри, які очікують видалення більшості даних.</span><span class="sxs-lookup"><span data-stu-id="0bef9-108">In the beginning of a query, right after the time filter, add the filters expected to remove most of the data.</span></span>
- <span data-ttu-id="0bef9-109">Коли ви шукаєте повні маркери, використовуйте `has` оператор, а не `contains` .</span><span class="sxs-lookup"><span data-stu-id="0bef9-109">When looking for full tokens, use the `has` operator rather than `contains`.</span></span>
- <span data-ttu-id="0bef9-110">Виконайте пошук у певному стовпці, а не в усіх стовпцях.</span><span class="sxs-lookup"><span data-stu-id="0bef9-110">Run a search on a specific column rather than across all columns.</span></span>
- <span data-ttu-id="0bef9-111">Під час приєднання до таблиць спочатку вкажіть таблицю з меншою кількістю рядків.</span><span class="sxs-lookup"><span data-stu-id="0bef9-111">When joining tables, first specify the table with fewer rows.</span></span>
- <span data-ttu-id="0bef9-112">`project` лише необхідні стовпці з таблиць, до яких ви приєдналися.</span><span class="sxs-lookup"><span data-stu-id="0bef9-112">`project` only the necessary columns from the tables you've joined.</span></span>

<span data-ttu-id="0bef9-113">Щоб отримати докладні відомості, ознайомтеся з [додатковими практиками пошуку за запитом](https://go.microsoft.com/fwlink/?linkid=2144812).</span><span class="sxs-lookup"><span data-stu-id="0bef9-113">To learn more, see [Advanced hunting query best practices](https://go.microsoft.com/fwlink/?linkid=2144812).</span></span>

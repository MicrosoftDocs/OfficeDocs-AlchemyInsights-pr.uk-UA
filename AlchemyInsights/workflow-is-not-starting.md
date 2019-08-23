---
title: Робочий процес не запускається
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 8/2/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000144"
- "1670"
ms.openlocfilehash: d4bfdb44c04eb6838f4a265e55a4873d14c78f6d
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 08/22/2019
ms.locfileid: "36558011"
---
# <a name="workflow-is-not-starting"></a><span data-ttu-id="6260e-102">Робочий процес не запускається</span><span class="sxs-lookup"><span data-stu-id="6260e-102">Workflow is not starting</span></span>

- <span data-ttu-id="6260e-103">SharePoint 2010 і SharePoint 2013 робочі процеси не запускається.</span><span class="sxs-lookup"><span data-stu-id="6260e-103">SharePoint 2010 and SharePoint 2013 workflows are not starting.</span></span>

    - <span data-ttu-id="6260e-104">Якщо робочого процесу не запускається, можливо питання тимчасові обслуговування де користувачів можуть виникнути тимчасовим затримкам з робочого процесу прогресу.</span><span class="sxs-lookup"><span data-stu-id="6260e-104">If your workflow is not starting, there may be a temporary service issue where users may experience intermittent delays with workflow progress.</span></span> <span data-ttu-id="6260e-105">Перевірте [Службу здоров'я Dashboard](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) щоб побачити, якщо ваша організація є вплив.</span><span class="sxs-lookup"><span data-stu-id="6260e-105">Check the [Service Health Dashboard](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) to see if your organization is impacted.</span></span>

    - <span data-ttu-id="6260e-106">Якщо більш ніж 24 години пройшло з тих пір ви вперше побачив це питання, будь ласка, увійдіть квиток підтримки.</span><span class="sxs-lookup"><span data-stu-id="6260e-106">If more than 24 hours have passed since you first saw this issue, please log a support ticket.</span></span> <span data-ttu-id="6260e-107">У багатьох випадках ми вже працюємо над вирішенням.</span><span class="sxs-lookup"><span data-stu-id="6260e-107">In many cases, we're already working on a solution.</span></span> <span data-ttu-id="6260e-108">Будь ласка, надайте нам принаймні за 24 години до виконання рішення.</span><span class="sxs-lookup"><span data-stu-id="6260e-108">Please give us at least 24 hours to complete a solution.</span></span>

- <span data-ttu-id="6260e-109">SharePoint 2010 робочі процеси затримується на старті.</span><span class="sxs-lookup"><span data-stu-id="6260e-109">SharePoint 2010 workflows delayed on start.</span></span>

    - <span data-ttu-id="6260e-110">Це відбувається, якщо робочий процес спрацьовує у великих партіях.</span><span class="sxs-lookup"><span data-stu-id="6260e-110">This occurs if the workflow is triggered in large batches.</span></span> <span data-ttu-id="6260e-111">(наприклад, коли кілька елементів додаються відразу).</span><span class="sxs-lookup"><span data-stu-id="6260e-111">(for example, when several items are added at once).</span></span>

    - <span data-ttu-id="6260e-112">Робочі процеси не призначений для запуску в режимі реального часу, так що затримка — за дизайн поведінки.</span><span class="sxs-lookup"><span data-stu-id="6260e-112">Workflows are not designed to run real-time, so a delay is by-design behavior.</span></span>

   -  <span data-ttu-id="6260e-113">Якщо робочий процес комплекс розширюваний об'єктно розмітки мови (XMOL), компіляції може бути повільним.</span><span class="sxs-lookup"><span data-stu-id="6260e-113">If the Workflow is complex Extensible Object Markup Language (XMOL), compilation can be slow.</span></span> <span data-ttu-id="6260e-114">Перевірити [цю](https://support.microsoft.com/en-us/kb/3043697) статтю.</span><span class="sxs-lookup"><span data-stu-id="6260e-114">Check [this](https://support.microsoft.com/en-us/kb/3043697) article.</span></span>

    - <span data-ttu-id="6260e-115">Ви повинні спростити робочого процесу або редизайн його за допомогою Microsoft SharePoint робочий процес для 2013 тип платформи.</span><span class="sxs-lookup"><span data-stu-id="6260e-115">You should simplify the workflow or redesign it using the Microsoft SharePoint 2013 Workflow platform type.</span></span>

    - <span data-ttu-id="6260e-116">Якщо робочий процес історії розрісся розмір, ви можете очистити елементи або створити новий список журналу.</span><span class="sxs-lookup"><span data-stu-id="6260e-116">If your workflow history has grown large, you may want to purge the items or create a new history list.</span></span>

        <span data-ttu-id="6260e-117">Більш детальну інформацію: [Очистити історію робочого циклу](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span><span class="sxs-lookup"><span data-stu-id="6260e-117">More Information : [Purge Workflow History](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)</span></span>


## <a name="related-topics"></a><span data-ttu-id="6260e-118">Пов’язані теми</span><span class="sxs-lookup"><span data-stu-id="6260e-118">Related topics</span></span>
<span data-ttu-id="6260e-119">Хочете спробувати Microsoft потік в SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="6260e-119">Want to try Microsoft Flow in SharePoint Online?</span></span>
- [<span data-ttu-id="6260e-120">Створити потік</span><span class="sxs-lookup"><span data-stu-id="6260e-120">Create Flow</span></span>](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [<span data-ttu-id="6260e-121">SharePoint і потік</span><span class="sxs-lookup"><span data-stu-id="6260e-121">SharePoint and Flow</span></span>](https://flow.microsoft.com/blog/sharepoint-and-flow/) 



---
title: Не відображаються позначки чутливості
ms.author: pebaum
author: pebaum
manager: laurawi
ms.date: 04/21/2020
ms.audience: admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1778"
- "9000181"
ms.openlocfilehash: 6a64e001be115c8e5553a0d8c97b8cb815922c69
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 09/15/2020
ms.locfileid: "47801205"
---
# <a name="sensitivity-labels-not-appearing"></a><span data-ttu-id="4813a-102">Не відображаються позначки чутливості</span><span class="sxs-lookup"><span data-stu-id="4813a-102">Sensitivity labels not appearing</span></span>

<span data-ttu-id="4813a-103">Позначки чутливості дають змогу класифікувати та захищати ваш чутливий вміст.</span><span class="sxs-lookup"><span data-stu-id="4813a-103">Sensitivity labels allow you to classify and help protect your sensitive content.</span></span> <span data-ttu-id="4813a-104">Їх можна створити в центрі відповідності Microsoft 365, центрі безпеки Microsoft 365 або в центрі безпеки та конфіденційності Microsoft 365 & центр відповідності класифікації > Мітки чутливості.</span><span class="sxs-lookup"><span data-stu-id="4813a-104">They can be created in the Microsoft 365 compliance center, Microsoft 365 security center, or Microsoft 365 security & Compliance Center under Classification > Sensitivity labels.</span></span> <span data-ttu-id="4813a-105">Докладні відомості про цю функцію наведено в статті [Огляд міток чутливості](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels).</span><span class="sxs-lookup"><span data-stu-id="4813a-105">To learn more about this feature, see [Overview of sensitivity labels](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels).</span></span>

<span data-ttu-id="4813a-106">Якщо ви настроїли Мітки конфіденційності, але вони не відображаються в програмах Microsoft 365, установіть наведені нижче дії.</span><span class="sxs-lookup"><span data-stu-id="4813a-106">If you configured your sensitivity labels but they aren't appearing in the Microsoft 365 apps, check the following:</span></span>

- <span data-ttu-id="4813a-107">Переконайтеся, що підпис "чутливість" [опубліковано](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels#what-label-policies-can-do) для користувачів і груп, які потрібно виконати.</span><span class="sxs-lookup"><span data-stu-id="4813a-107">Confirm that the sensitivity label has been [published](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels#what-label-policies-can-do) to the users and groups that you want.</span></span>

- <span data-ttu-id="4813a-108">Переконайтеся, що користувач використовує програму, яка підтримує позначки чутливості, [у документі відображаються позначки чутливості](https://support.office.com/article/apply-sensitivity-labels-to-your-documents-and-email-within-office-2f96e7cd-d5a4-403b-8bd7-4cc636bae0f9?#bkmk_whereavailable).</span><span class="sxs-lookup"><span data-stu-id="4813a-108">Confirm that the user is using an app that supports sensitivity labels - see [sensitivity labels in your document](https://support.office.com/article/apply-sensitivity-labels-to-your-documents-and-email-within-office-2f96e7cd-d5a4-403b-8bd7-4cc636bae0f9?#bkmk_whereavailable).</span></span>

- <span data-ttu-id="4813a-109">Якщо ви [мігруєте Мітки захисту від Блакитної інформації](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels), ознайомтеся з наведеними [тут](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels#considerations-for-unified-labels)міркуваннями.</span><span class="sxs-lookup"><span data-stu-id="4813a-109">If you're [migrating Azure Information Protection labels](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels), be aware of the considerations listed [here](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels#considerations-for-unified-labels).</span></span>

- <span data-ttu-id="4813a-110">Підтримка захисту від втрати даних (DLP): наразі можна використовувати лише Мітки збереження, як умову в політиці DLP.</span><span class="sxs-lookup"><span data-stu-id="4813a-110">Data loss prevention (DLP) support: Currently, only retention labels can be used as a condition in DLP policies.</span></span>  <span data-ttu-id="4813a-111">Підтримка міток чутливості у політиці DLP недоступна, але ми працюємо над ним.</span><span class="sxs-lookup"><span data-stu-id="4813a-111">Support for sensitivity labels in a DLP policy is not available yet but we're working on it.</span></span>

- <span data-ttu-id="4813a-112">Якщо функцію шифрування ввімкнуто на етикетці чутливості, можна вибрати один із таких варіантів:</span><span class="sxs-lookup"><span data-stu-id="4813a-112">When encryption is enabled on a sensitivity label, you can choose either to:</span></span>
    - <span data-ttu-id="4813a-113">Призначити дозволи зараз</span><span class="sxs-lookup"><span data-stu-id="4813a-113">Assign permissions now</span></span>
    - <span data-ttu-id="4813a-114">Дозволити користувачам призначати дозволи</span><span class="sxs-lookup"><span data-stu-id="4813a-114">Let users assign permissions</span></span>


<span data-ttu-id="4813a-115">Докладні відомості про можливі проблеми наведено в статті [відомі проблеми з підписами чутливості](https://support.office.com/article/known-issues-with-sensitivity-labels-in-office-b169d687-2bbd-4e21-a440-7da1b2743edc).</span><span class="sxs-lookup"><span data-stu-id="4813a-115">For more information on possible issues, see [Known issues with sensitivity labels](https://support.office.com/article/known-issues-with-sensitivity-labels-in-office-b169d687-2bbd-4e21-a440-7da1b2743edc).</span></span>
---
title: Регулювання SharePoint Online
ms.author: pebaum
author: pebaum
ms.date: 9/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: b376d8ea-50c4-47f0-9720-50d80aa3f7f1
ms.custom:
- "9000149"
- "1662"
- "3491"
ms.openlocfilehash: 59104ef96c95de4e4bc7744825245bdafba97d7c
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/24/2020
ms.locfileid: "42931247"
---
# <a name="sharepoint-online-throttling"></a><span data-ttu-id="e4d75-102">Регулювання SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="e4d75-102">SharePoint Online Throttling</span></span>

<span data-ttu-id="e4d75-103">**Важливо**: багато SharePoint Online і OneDrive клієнтів, запустіть бізнес-критичних програм від служби, які працюють у фоновому режимі.</span><span class="sxs-lookup"><span data-stu-id="e4d75-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="e4d75-104">До них відносяться міграція вмісту, запобігання втрати даних (ЗВД) і рішення для резервного копіювання.</span><span class="sxs-lookup"><span data-stu-id="e4d75-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="e4d75-105">У ці безпрецедентні часи Ми вживаємо заходів, щоб гарантувати, що служби SharePoint Online та OneDrive залишаються дуже доступними та надійними для користувачів, які залежать від служби, ніж будь-коли в віддалених сценаріях роботи.</span><span class="sxs-lookup"><span data-stu-id="e4d75-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="e4d75-106">На підтримку цієї мети, ми реалізували жорсткі обмеження регулювання на фонових програм (міграція, ЗВД і резервне копіювання рішень) в будні дні вдень.</span><span class="sxs-lookup"><span data-stu-id="e4d75-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="e4d75-107">Ви повинні очікувати, що ці програми будуть досягати дуже обмежену пропускну здатність в ці часи.</span><span class="sxs-lookup"><span data-stu-id="e4d75-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="e4d75-108">Однак під час вечірніх та вихідних годин для регіону служба буде готова обробляти значно більший обсяг запитів від фонових програм.</span><span class="sxs-lookup"><span data-stu-id="e4d75-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="e4d75-109">**503 сервер зайнятий, помилка**</span><span class="sxs-lookup"><span data-stu-id="e4d75-109">**503 server is busy error**</span></span>

<span data-ttu-id="e4d75-110">Користувачі можуть отримувати 503 сервер зайнятий, помилка під час спроби перейти до SharePoint або OneDrive сайтів.</span><span class="sxs-lookup"><span data-stu-id="e4d75-110">Users may receive a 503 server is busy error when attempting to navigate to SharePoint or OneDrive sites.</span></span> 

<span data-ttu-id="e4d75-111">Ця помилка може бути викликана дроселювання у службі SharePoint.</span><span class="sxs-lookup"><span data-stu-id="e4d75-111">This error can be caused by throttling within the SharePoint service.</span></span> <span data-ttu-id="e4d75-112">SharePoint Online використовує дроселювання для підтримки оптимальної продуктивності та надійності служби SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="e4d75-112">SharePoint Online uses throttling to maintain optimal performance and reliability of the SharePoint Online service.</span></span> <span data-ttu-id="e4d75-113">Дроселювання обмежує кількість дій користувача або одночасних викликів (за сценарієм або кодом) для запобігання надмірного використання ресурсів.</span><span class="sxs-lookup"><span data-stu-id="e4d75-113">Throttling limits the number of user actions or concurrent calls (by script or code) to prevent overuse of resources.</span></span> 

<span data-ttu-id="e4d75-114">Для отримання додаткових відомостей про дроселювання можна [уникнути обмеження або блокування в SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span><span class="sxs-lookup"><span data-stu-id="e4d75-114">For more information on throttling see, [Avoid getting throttled or blocked in SharePoint Online](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online).</span></span>

<span data-ttu-id="e4d75-115">Якщо ви вважаєте, що ця помилка не пов'язана з дроселювання, ви можете перевірити, чи є активне обслуговування, що відбувається на вашому клієнті, перейшовши до [центру повідомлень](https://portal.office.com/adminportal/home#/MessageCenter).</span><span class="sxs-lookup"><span data-stu-id="e4d75-115">If you believe this error is unrelated to throttling, you can check if there is active maintenance occurring on your tenant by navigating to the [Message center](https://portal.office.com/adminportal/home#/MessageCenter).</span></span>

 <span data-ttu-id="e4d75-116">Нарешті, переконайтеся, що ви відвідаєте сторінку [служби охорони здоров'я](https://portal.office.com/adminportal/home#/servicehealth) , щоб перевірити наявність будь-яких рекомендації/інцидентів, які можуть трапитися.</span><span class="sxs-lookup"><span data-stu-id="e4d75-116">Finally, ensure you visit the [Service Health](https://portal.office.com/adminportal/home#/servicehealth) page to check for any advisories/incidents that may be occurring.</span></span>


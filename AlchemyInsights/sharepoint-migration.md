---
title: Перенесення параметрів у SharePoint Online
ms.author: pebaum
author: v-miegge
manager: v-cojank
ms.date: 11/04/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: c8c339c9-2e50-4daa-aa91-3eb5053e2bc6
ms.openlocfilehash: 830b39c51658cbc02f4be81acdfdf3b164a8df70
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932751"
---
# <a name="migrate-options-to-sharepoint-online"></a><span data-ttu-id="63246-102">Перенесення параметрів у SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="63246-102">Migrate options to SharePoint Online</span></span>

<span data-ttu-id="63246-103">**Важливо**: багато SharePoint Online і OneDrive клієнтів, запустіть бізнес-критичних програм від служби, які працюють у фоновому режимі.</span><span class="sxs-lookup"><span data-stu-id="63246-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="63246-104">До них відносяться міграція вмісту, запобігання втрати даних (ЗВД) і рішення для резервного копіювання.</span><span class="sxs-lookup"><span data-stu-id="63246-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="63246-105">У ці безпрецедентні часи Ми вживаємо заходів, щоб гарантувати, що служби SharePoint Online та OneDrive залишаються дуже доступними та надійними для користувачів, які залежать від служби, ніж будь-коли в віддалених сценаріях роботи.</span><span class="sxs-lookup"><span data-stu-id="63246-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="63246-106">На підтримку цієї мети, ми реалізували жорсткі обмеження регулювання на фонових програм (міграція, ЗВД і резервне копіювання рішень) в будні дні вдень.</span><span class="sxs-lookup"><span data-stu-id="63246-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="63246-107">Ви повинні очікувати, що ці програми будуть досягати дуже обмежену пропускну здатність в ці часи.</span><span class="sxs-lookup"><span data-stu-id="63246-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="63246-108">Однак під час вечірніх та вихідних годин для регіону служба буде готова обробляти значно більший обсяг запитів від фонових програм.</span><span class="sxs-lookup"><span data-stu-id="63246-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="63246-109">**Параметри міграції**</span><span class="sxs-lookup"><span data-stu-id="63246-109">**Migration options**</span></span>

<span data-ttu-id="63246-110">Існують різні варіанти для перенесення вмісту в SharePoint Online, залежно від розміру та кількості файлів, які потрібно перемістити, будь ласка, перегляньте список опцій, [розташованих тут](https://docs.microsoft.com/sharepointmigration/migrate-to-sharepoint-online).</span><span class="sxs-lookup"><span data-stu-id="63246-110">There are different options available to migrate content to SharePoint Online, depending on the size and quantity of files you need to move, please see a list of options [located here](https://docs.microsoft.com/sharepointmigration/migrate-to-sharepoint-online).</span></span>

<span data-ttu-id="63246-111">Для отримання додаткової інформації про зміст міграції, будь ласка, відвідайте посилання нижче.</span><span class="sxs-lookup"><span data-stu-id="63246-111">For more information on content migration, please visit the links below.</span></span>

- [<span data-ttu-id="63246-112">Засіб міграції SharePoint</span><span class="sxs-lookup"><span data-stu-id="63246-112">Sharepoint Migration Tool</span></span>](https://docs.microsoft.com/sharepointmigration/introducing-the-sharepoint-migration-tool)

- [<span data-ttu-id="63246-113">Початок роботи з менеджером міграції</span><span class="sxs-lookup"><span data-stu-id="63246-113">Get started with the Migration Manager</span></span>](https://docs.microsoft.com/sharepointmigration/mm-get-started)

- [<span data-ttu-id="63246-114">Швидкість міграції SharePoint Online та ODB</span><span class="sxs-lookup"><span data-stu-id="63246-114">Sharepoint Online and ODB Migration Speed</span></span>](https://docs.microsoft.com/sharepointmigration/sharepoint-online-and-onedrive-migration-speed)

- [<span data-ttu-id="63246-115">Уникайте отримання обмежено або заблоковано в SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="63246-115">Avoid getting throttled or blocked in SharePoint Online</span></span>](https://docs.microsoft.com/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online)

- [<span data-ttu-id="63246-116">Засіб оцінювання міграції SharePoint (SMAT)</span><span class="sxs-lookup"><span data-stu-id="63246-116">SharePoint Migration Assessment Tool (SMAT)</span></span>](https://www.microsoft.com/download/details.aspx?id=53598&amp;751be11f-ede8-5a0c-058c-2ee190a24fa6=True)

<span data-ttu-id="63246-117">**Примітка**: наразі засіб міграції SharePoint підтримує лише міграції з SharePoint 2010 та 2013.</span><span class="sxs-lookup"><span data-stu-id="63246-117">**Note**: Currently the SharePoint Migration tool only support migrations from SharePoint 2010  and 2013.</span></span> <span data-ttu-id="63246-118">У цей час не підтримуються версії 2016 або 2019.</span><span class="sxs-lookup"><span data-stu-id="63246-118">Version 2016 or 2019 are not supported at this time.</span></span>

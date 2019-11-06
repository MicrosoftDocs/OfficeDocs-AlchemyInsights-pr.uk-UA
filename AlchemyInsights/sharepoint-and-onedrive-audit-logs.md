---
title: Класичні звіти журналу аудиту SharePoint
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1372"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: be95034bea3c58a4fde96cfb0f9ba525e810758e
ms.sourcegitcommit: 24e8248b0f061a76af50bf566d7a13fc24d29d99
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 11/05/2019
ms.locfileid: "37992639"
---
# <a name="sharepoint-and-onedrive-audit-logs"></a><span data-ttu-id="be784-102">Журнали аудиту SharePoint і OneDrive</span><span class="sxs-lookup"><span data-stu-id="be784-102">SharePoint and OneDrive audit logs</span></span>

## <a name="sharepoint-classic-audit-logs"></a><span data-ttu-id="be784-103">Журнали для класичного аудиту SharePoint</span><span class="sxs-lookup"><span data-stu-id="be784-103">SharePoint classic Audit logs</span></span>

<span data-ttu-id="be784-104">"Спо Legacy аудиту" перенесено до єдиного журналу аудиту (АЛЬ).</span><span class="sxs-lookup"><span data-stu-id="be784-104">SPO legacy auditing was migrated to Unified Audit Log (UAL).</span></span> <span data-ttu-id="be784-105">Усі звіти про аудит на платформі «спо» тепер будуть проходити через АЛЬ, а застарілі аудиторські сигнали були перенесені в АЛЬ.</span><span class="sxs-lookup"><span data-stu-id="be784-105">All SPO legacy audit reports will now be powered through UAL, and the legacy audit signals have been migrated to UAL.</span></span>

<span data-ttu-id="be784-106">Ключові зміни:</span><span class="sxs-lookup"><span data-stu-id="be784-106">Key changes:</span></span>

* <span data-ttu-id="be784-107">Обрізка недоступна як можливість.</span><span class="sxs-lookup"><span data-stu-id="be784-107">Trimming is NOT available as a capability.</span></span>
* <span data-ttu-id="be784-108">Вибір конкретних подій для аудиту недоступний.</span><span class="sxs-lookup"><span data-stu-id="be784-108">Choosing specific events to audit is NOT available.</span></span> <span data-ttu-id="be784-109">Перегляньте [цей документ](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) , щоб отримати повний список відстежуваної події за промовчанням.</span><span class="sxs-lookup"><span data-stu-id="be784-109">Refer to [this document](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance) for a complete list of audited events available by default.</span></span>
* <span data-ttu-id="be784-110">Параметр **розташування** в розділі **Настроювані звіти** недоступний.</span><span class="sxs-lookup"><span data-stu-id="be784-110">The **Location** option under **Customized reports** is NOT available.</span></span>
* <span data-ttu-id="be784-111">**Відкриття або завантаження документів** , події параметр недоступний.</span><span class="sxs-lookup"><span data-stu-id="be784-111">The **Opening or downloading documents** events option is NOT available.</span></span>

[<span data-ttu-id="be784-112">Настроювання параметрів аудиту для колекції сайтів</span><span class="sxs-lookup"><span data-stu-id="be784-112">Configure Audit settings for a site collection</span></span>](https://support.office.com/article/Configure-audit-settings-for-a-site-collection-A9920C97-38C0-44F2-8BCB-4CF1E2AE22D2)

## <a name="sharepoint-and-onedrive-modern-unified-audit-logs-from-compliance"></a><span data-ttu-id="be784-113">Служби SharePoint і OneDrive сучасних Unified аудиту журнали відповідності</span><span class="sxs-lookup"><span data-stu-id="be784-113">SharePoint and OneDrive Modern Unified Audit logs from compliance</span></span>

* [<span data-ttu-id="be784-114">Увімкнення/вимкнення єдиного аудиту журналювання</span><span class="sxs-lookup"><span data-stu-id="be784-114">Turn on/off Unified Audit Logging</span></span>](https://docs.microsoft.com/office365/securitycompliance/turn-audit-log-search-on-or-off) 

<span data-ttu-id="be784-115">У SharePoint або OneDrive не потрібна додаткова конфігурація.</span><span class="sxs-lookup"><span data-stu-id="be784-115">No additional configuration is required within SharePoint or OneDrive.</span></span>

<span data-ttu-id="be784-116">Використання аудиту журналювання пошук для перевірки діяльності файлів (ів), папок (ів), користувачів (ів), дозволи:</span><span class="sxs-lookup"><span data-stu-id="be784-116">Use audit logging search to check activity of the file(s), folder(s), user(s), permissions:</span></span>

* [<span data-ttu-id="be784-117">Файл і сторінка діяльність</span><span class="sxs-lookup"><span data-stu-id="be784-117">File and page activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance)
* [<span data-ttu-id="be784-118">Папки діяльності</span><span class="sxs-lookup"><span data-stu-id="be784-118">Folder activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#folder-activities)
* [<span data-ttu-id="be784-119">Дії з надсилання й отримання доступу</span><span class="sxs-lookup"><span data-stu-id="be784-119">Sharing and access request activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#sharing-and-access-request-activities)
* [<span data-ttu-id="be784-120">Дії синхронізації</span><span class="sxs-lookup"><span data-stu-id="be784-120">Synchronization activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#synchronization-activities)
* [<span data-ttu-id="be784-121">Діяльність адміністрування сайту</span><span class="sxs-lookup"><span data-stu-id="be784-121">Site administration activities</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#site-administration-activities)

<span data-ttu-id="be784-122">Щоб отримати додаткові відомості про отримання цих подій, перегляньте статтю [Пошук журналу аудиту](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span><span class="sxs-lookup"><span data-stu-id="be784-122">For more information about how to retrieve these events, see [Search the audit log](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span></span>

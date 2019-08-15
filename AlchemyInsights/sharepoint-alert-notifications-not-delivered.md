---
title: Сповіщення не доставлено SharePoint
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 1/3/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "1655"
ms.openlocfilehash: e682a1b3dbd0d3a1c2e52be725dd2b57fc66109a
ms.sourcegitcommit: a2c866d2f3cdc1e18a33a5b2a4209340e83ca3c2
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 08/14/2019
ms.locfileid: "36404823"
---
# <a name="sharepoint-alert-notifications-not-delivered"></a><span data-ttu-id="191e8-102">Сповіщення не доставлено SharePoint</span><span class="sxs-lookup"><span data-stu-id="191e8-102">SharePoint alert notifications not delivered</span></span>

<span data-ttu-id="191e8-103">Будь ласка, перевірте папки НЕБАЖАНОЇ у вашій електронній пошті, а іноді оповіщення можуть туди.</span><span class="sxs-lookup"><span data-stu-id="191e8-103">Please check the JUNK folder in your email, as sometimes alerts might go there.</span></span>

<span data-ttu-id="191e8-104">Визначити, якщо **всі оповіщення не доставляються** або якщо **окремі оповіщення** від конкретного файлу або бібліотеки не доставляються.</span><span class="sxs-lookup"><span data-stu-id="191e8-104">Determine if **all alerts are not delivered** or if **an individual alert** from a specific file or library is not delivered.</span></span>

- <span data-ttu-id="191e8-105">**Індивідуальні оповіщення не доставляються**: якщо не доставляється окремих оповіщення від конкретного файлу або бібліотеки, можна спробувати його видалити і відтворити її.</span><span class="sxs-lookup"><span data-stu-id="191e8-105">**Individual alerts are not delivered**: If an individual alert from a specific file or library is not delivered, you can attempt to delete and recreate it.</span></span> <span data-ttu-id="191e8-106">Переглянути [керування, переглянути, або видалити оповіщення SharePoint](https://support.office.com/en-us/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2?ui=en-US&rs=en-US&ad=US#ID0EAADAAA=Online) відтворити оповіщення.</span><span class="sxs-lookup"><span data-stu-id="191e8-106">See [Manage, view, or delete SharePoint alerts](https://support.office.com/en-us/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2?ui=en-US&rs=en-US&ad=US#ID0EAADAAA=Online) to recreate the alert.</span></span>
- <span data-ttu-id="191e8-107">**Всі оповіщення не доставляються**: якщо всі оповіщення від кількох файлів або бібліотек не доставляються, відвідати [служба охорони здоров'я dashboard](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) перевірити наявність рекомендації/інцидентів, які можуть бути, що відбуваються з SharePoint або обміну.</span><span class="sxs-lookup"><span data-stu-id="191e8-107">**All alerts are not delivered**: If all alerts from multiple files or libraries are not delivered, visit the [Service Health dashboard](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) to check for any advisories/incidents that may be occurring with SharePoint or Exchange.</span></span> <span data-ttu-id="191e8-108">Це питання може бути з оповіщення про можливості SharePoint або затримки в повідомленнях електронної пошти через Exchange.</span><span class="sxs-lookup"><span data-stu-id="191e8-108">The issue could be with the SharePoint alert capability or delays in emails through Exchange.</span></span> <span data-ttu-id="191e8-109">Також буде важливо зазначити, чи інша ел. пошта доставляється, а якщо не, питання в тому, ймовірно, з Exchange затримки.</span><span class="sxs-lookup"><span data-stu-id="191e8-109">It will also be important to note whether other email is being delivered, and if not, the issue is likely with Exchange delays.</span></span>

<span data-ttu-id="191e8-110">Питання та відповіді на сповіщення:</span><span class="sxs-lookup"><span data-stu-id="191e8-110">FAQ on alerts:</span></span>

- <span data-ttu-id="191e8-111">Неможливо надіслати оповіщення групі розсилки, тільки безпеки і O365 групи, які підтримуються.</span><span class="sxs-lookup"><span data-stu-id="191e8-111">It is not possible to send alerts to Distribution Group, only Security and O365 groups are supported.</span></span>
- <span data-ttu-id="191e8-112">Не можна настроїти оповіщення електронної пошти шаблони; вам потрібно використовувати Microsoft ПОТОКУ або робочого циклу SharePoint Designer для досягнення тих.</span><span class="sxs-lookup"><span data-stu-id="191e8-112">You cannot customize alert email templates; you need to use Microsoft FLOW or SharePoint Designer Workflow to achieve those.</span></span>

<span data-ttu-id="191e8-113">Більш детальну інформацію:</span><span class="sxs-lookup"><span data-stu-id="191e8-113">More Information:</span></span>

- <span data-ttu-id="191e8-114">**Оповіщення про налаштування**: щоб отримати додаткові відомості щодо настроювання оповіщень, див. [створення оповіщення, щоб отримати повідомлення, коли файл або папку зміни в SharePoint](https://support.office.com/en-us/article/create-an-alert-to-get-notified-when-a-file-or-folder-changes-in-sharepoint-e5a79e7b-a146-46da-a9ef-d65409ba8918).</span><span class="sxs-lookup"><span data-stu-id="191e8-114">**Alert setup**: For more information about setting up alerts, see [Create an alert to get notified when a file or folder changes in SharePoint](https://support.office.com/en-us/article/create-an-alert-to-get-notified-when-a-file-or-folder-changes-in-sharepoint-e5a79e7b-a146-46da-a9ef-d65409ba8918).</span></span>
- <span data-ttu-id="191e8-115">**Виправлення неполадок оповіщення**: щоб отримати додаткові відомості про усунення неполадок із оповіщення, побачити [користувачі не отримувати сповіщення SharePoint Online](https://docs.microsoft.com/en-us/sharepoint/support/sites/no-alert-notifications).</span><span class="sxs-lookup"><span data-stu-id="191e8-115">**Troubleshoot alerts**: For more information about troubleshooting alerts, see [Users don't receive SharePoint Online alert notifications](https://docs.microsoft.com/en-us/sharepoint/support/sites/no-alert-notifications).</span></span>
- <span data-ttu-id="191e8-116">**Розширений O365 дотримання оповіщення політики**: щоб отримати додаткові відомості щодо настроювання такі сигнали, побачити [Оповіщення про політику дотримання](https://docs.microsoft.com/en-us/office365/securitycompliance/alert-policies).</span><span class="sxs-lookup"><span data-stu-id="191e8-116">**Advanced O365 Compliance Alert Policies**: For more information about setting up these alerts, see [Compliance Alert Policies](https://docs.microsoft.com/en-us/office365/securitycompliance/alert-policies).</span></span>
- <span data-ttu-id="191e8-117">**OneDrive журнали аудиту і SharePoint**: Докладніше про те, як отримати ці події, див. [Пошук журналу аудиту](https://docs.microsoft.com/en-us/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span><span class="sxs-lookup"><span data-stu-id="191e8-117">**SharePoint and OneDrive Audit Logs**: For more information about how to retrieve these events, see [Search the audit log](https://docs.microsoft.com/en-us/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).</span></span>
- <span data-ttu-id="191e8-118">**Сповіщення про надіслані розширений загроза захист**: Див [АТФ для SharePoint і OneDrive](https://docs.microsoft.com/en-us/office365/securitycompliance/atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="191e8-118">**Alerts sent by Advanced Threat Protection**: See [ATP for SharePoint and OneDrive](https://docs.microsoft.com/en-us/office365/securitycompliance/atp-for-spo-odb-and-teams).</span></span>
- <span data-ttu-id="191e8-119">**Сповіщення про надіслані запобігання втрати даних політик**: перегляд [оповіщень електронної пошти для DLP політик](https://docs.microsoft.com/en-us/office365/securitycompliance/use-notifications-and-policy-tips).</span><span class="sxs-lookup"><span data-stu-id="191e8-119">**Alerts sent by Data Loss Prevention polices**: See [Email notifications for DLP policies](https://docs.microsoft.com/en-us/office365/securitycompliance/use-notifications-and-policy-tips).</span></span>

## <a name="related-topics"></a><span data-ttu-id="191e8-120">Суміжні теми</span><span class="sxs-lookup"><span data-stu-id="191e8-120">Related Topics</span></span>

<span data-ttu-id="191e8-121">Хочете спробувати Microsoft потік в SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="191e8-121">Want to try Microsoft Flow in SharePoint Online?</span></span>

- [<span data-ttu-id="191e8-122">Створити потік</span><span class="sxs-lookup"><span data-stu-id="191e8-122">Create Flow</span></span>](https://support.office.com/en-us/article/create-a-flow-for-a-list-or-library-in-sharepoint-online-or-onedrive-for-business-a9c3e03b-0654-46af-a254-20252e580d01)

- [<span data-ttu-id="191e8-123">SharePoint і потік</span><span class="sxs-lookup"><span data-stu-id="191e8-123">SharePoint and Flow</span></span>](https://flow.microsoft.com/en-us/blog/sharepoint-and-flow/)

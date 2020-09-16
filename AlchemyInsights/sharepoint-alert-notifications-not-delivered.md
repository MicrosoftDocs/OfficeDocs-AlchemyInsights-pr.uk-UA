---
title: Оповіщення сповіщень SharePoint не доставлено
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "1655"
ms.openlocfilehash: f4002dc865fb7a03b07a9256709b947d6d774cb0
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 09/14/2020
ms.locfileid: "47751264"
---
# <a name="sharepoint-alert-notifications-not-delivered"></a><span data-ttu-id="17ba4-102">Оповіщення сповіщень SharePoint не доставлено</span><span class="sxs-lookup"><span data-stu-id="17ba4-102">SharePoint alert notifications not delivered</span></span>

<span data-ttu-id="17ba4-103">Перевірте папку "НЕБАЖАНА пошта" в електронному листі, оскільки іноді оповіщення можуть перейти туди.</span><span class="sxs-lookup"><span data-stu-id="17ba4-103">Please check the JUNK folder in your email, as sometimes alerts might go there.</span></span>

<span data-ttu-id="17ba4-104">Визначити, чи не доставлено **всі оповіщення** , або якщо не доставляється **окреме оповіщення** з певного файлу або бібліотеки.</span><span class="sxs-lookup"><span data-stu-id="17ba4-104">Determine if **all alerts are not delivered** or if **an individual alert** from a specific file or library is not delivered.</span></span>

- <span data-ttu-id="17ba4-105">**Окремі оповіщення не доставляються**: якщо не доставлено окреме оповіщення з певного файлу або бібліотеки, ви можете спробувати видалити та відтворити його повторно.</span><span class="sxs-lookup"><span data-stu-id="17ba4-105">**Individual alerts are not delivered**: If an individual alert from a specific file or library is not delivered, you can attempt to delete and recreate it.</span></span> <span data-ttu-id="17ba4-106">У статті [керування, перегляд і видалення оповіщень SharePoint](https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) для повторного створення оповіщення.</span><span class="sxs-lookup"><span data-stu-id="17ba4-106">See [Manage, view, or delete SharePoint alerts](https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) to recreate the alert.</span></span>
- <span data-ttu-id="17ba4-107">**Усі оповіщення не доставляються**: якщо не доставлено всі оповіщення з кількох файлів або бібліотек, перейдіть на [приладну дошку справність служби](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) , щоб перевірити всі рекомендації та інциденти, що можуть виникнути в службі SharePoint або Exchange.</span><span class="sxs-lookup"><span data-stu-id="17ba4-107">**All alerts are not delivered**: If all alerts from multiple files or libraries are not delivered, visit the [Service Health dashboard](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) to check for any advisories/incidents that may be occurring with SharePoint or Exchange.</span></span> <span data-ttu-id="17ba4-108">Ця проблема може бути з функцією оповіщення служби SharePoint або затримками в повідомленнях електронної пошти за допомогою Exchange.</span><span class="sxs-lookup"><span data-stu-id="17ba4-108">The issue could be with the SharePoint alert capability or delays in emails through Exchange.</span></span> <span data-ttu-id="17ba4-109">Також слід пам'ятати про те, чи доставлятимуться інші повідомлення електронної пошти, а якщо це можливо, проблема з затримкою Exchange.</span><span class="sxs-lookup"><span data-stu-id="17ba4-109">It will also be important to note whether other email is being delivered, and if not, the issue is likely with Exchange delays.</span></span>

<span data-ttu-id="17ba4-110">Запитання й відповіді про оповіщення:</span><span class="sxs-lookup"><span data-stu-id="17ba4-110">FAQ on alerts:</span></span>

- <span data-ttu-id="17ba4-111">Не можна передавати оповіщення до групи розсилки, підтримуються лише групи безпеки та O365.</span><span class="sxs-lookup"><span data-stu-id="17ba4-111">It is not possible to send alerts to Distribution Group, only Security and O365 groups are supported.</span></span>
- <span data-ttu-id="17ba4-112">Не можна настроювати шаблони сповіщень електронної пошти; щоб досягти цих потреб, потрібно скористатися робочим циклом Microsoft FLOW або конструктора SharePoint Designer.</span><span class="sxs-lookup"><span data-stu-id="17ba4-112">You cannot customize alert email templates; you need to use Microsoft FLOW or SharePoint Designer Workflow to achieve those.</span></span>

## <a name="related-topics"></a><span data-ttu-id="17ba4-113">Пов'язані теми</span><span class="sxs-lookup"><span data-stu-id="17ba4-113">Related Topics</span></span>

<span data-ttu-id="17ba4-114">Хочете спробувати Microsoft Flow у службі SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="17ba4-114">Want to try Microsoft Flow in SharePoint Online?</span></span>

- [<span data-ttu-id="17ba4-115">Створення потоку</span><span class="sxs-lookup"><span data-stu-id="17ba4-115">Create Flow</span></span>](https://support.office.com/article/a9c3e03b-0654-46af-a254-20252e580d01)

- [<span data-ttu-id="17ba4-116">SharePoint і передавання</span><span class="sxs-lookup"><span data-stu-id="17ba4-116">SharePoint and Flow</span></span>](https://flow.microsoft.com//blog/sharepoint-and-flow/)

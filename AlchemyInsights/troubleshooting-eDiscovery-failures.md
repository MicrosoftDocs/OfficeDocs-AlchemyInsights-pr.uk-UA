---
title: 1490 – усунення несправностей – eDiscovery – помилки
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1490"
- "3200003"
ms.assetid: ''
ms.openlocfilehash: ff28f96d64ec14980e9a47b630246b394faf4610
ms.sourcegitcommit: fbe6925797cab0b38172386f1b059dc122e452a4
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 09/25/2020
ms.locfileid: "48277843"
---
# <a name="troubleshoot-content-search-errors"></a><span data-ttu-id="1a024-102">Виправлення помилок пошуку вмісту</span><span class="sxs-lookup"><span data-stu-id="1a024-102">Troubleshoot Content Search errors</span></span>

<span data-ttu-id="1a024-103">Під час експорту результатів пошуку виникають проблеми з пошуком вмісту або їх збої?</span><span class="sxs-lookup"><span data-stu-id="1a024-103">Are you experiencing problems with Content Search or getting failures when you export search results?</span></span>

<span data-ttu-id="1a024-104">Наприклад, під час запуску пошуків відображається таке:</span><span class="sxs-lookup"><span data-stu-id="1a024-104">For example, are you receiving the following when running searches?</span></span>

- <span data-ttu-id="1a024-105">Помилки CS008 або CS012</span><span class="sxs-lookup"><span data-stu-id="1a024-105">CS008 or CS012 errors</span></span>

- <span data-ttu-id="1a024-106">Помилки на сервері/тайм-аут</span><span class="sxs-lookup"><span data-stu-id="1a024-106">Server busy/timeout errors</span></span>

- <span data-ttu-id="1a024-107">Сталася помилка програми</span><span class="sxs-lookup"><span data-stu-id="1a024-107">Application error occurred</span></span>

<span data-ttu-id="1a024-108">Або під час пошуку або експортування результатів із великої кількості поштових скриньок (понад 100 000 поштових скриньок) ви одержуєте помилки експорту?</span><span class="sxs-lookup"><span data-stu-id="1a024-108">Or when searching or exporting results from a large number of mailboxes (over 100,000 mailboxes), are you getting export errors?</span></span>

<span data-ttu-id="1a024-109">Для цих типів помилок повторіть пошук розташувань вмісту, які не вдалося виконати.</span><span class="sxs-lookup"><span data-stu-id="1a024-109">For these types of errors, retry the search for the content locations that have failed.</span></span> <span data-ttu-id="1a024-110">Перегляньте  [цю статтю](https://docs.microsoft.com/microsoft-365/compliance/retry-failed-content-search) , щоб отримати докладніші відомості.</span><span class="sxs-lookup"><span data-stu-id="1a024-110">See  [this article](https://docs.microsoft.com/microsoft-365/compliance/retry-failed-content-search) for more information.</span></span>

<span data-ttu-id="1a024-111">Якщо ви експортуєте понад 100K поштові скриньки, вам доведеться використовувати наведені нижче PowerShell, щоб завантажити результати експорту:  [Експорт результатів із понад 100K поштових скриньок](https://docs.microsoft.com/microsoft-365/compliance/export-search-results?view=o365-worldwide%23exporting-results-from-more-than-100000-mailboxes).</span><span class="sxs-lookup"><span data-stu-id="1a024-111">If you are exporting more than 100K mailboxes, you will need to use the following Powershell to download the Export results:  [Exporting results from more than 100K mailboxes](https://docs.microsoft.com/microsoft-365/compliance/export-search-results?view=o365-worldwide%23exporting-results-from-more-than-100000-mailboxes).</span></span>

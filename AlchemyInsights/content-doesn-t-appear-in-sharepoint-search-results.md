---
title: Вміст не відображається в результатах пошуку SharePoint
ms.author: tlarsen
author: tklarsen
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "750"
- "5300017"
ms.assetid: 693db84f-2737-4c21-b027-4ab3d121b4a8
ms.openlocfilehash: a21e0047b41390f740f9e13d31cba32b13990151
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/22/2020
ms.locfileid: "43705682"
---
# <a name="content-doesnt-appear-in-sharepoint-search-results"></a><span data-ttu-id="0bac6-102">Вміст не відображається в результатах пошуку SharePoint</span><span class="sxs-lookup"><span data-stu-id="0bac6-102">Content doesn't appear in SharePoint search results</span></span>

<span data-ttu-id="0bac6-103">Виконайте ці кроки з виправлення неполадок, коли очікуваний вміст не відображається в результатах пошуку:</span><span class="sxs-lookup"><span data-stu-id="0bac6-103">Follow these troubleshooting steps when expected content doesn't appear in search results:</span></span>
  
1. <span data-ttu-id="0bac6-104">Переконайтеся, що на **сайті** , який містить очікуваний вміст налаштовано на дозволити вміст з'являтися в результатах пошуку.</span><span class="sxs-lookup"><span data-stu-id="0bac6-104">Check that the **site** that contains the expected content is set to allow content to appear in search results.</span></span> <span data-ttu-id="0bac6-105">Дотримуйтеся вказівок у [показі вмісту на сайті в результатах пошуку](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-on-a-site-in-search-results).</span><span class="sxs-lookup"><span data-stu-id="0bac6-105">Follow the steps in [Show content on a site in search results](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-on-a-site-in-search-results).</span></span>

2. <span data-ttu-id="0bac6-106">Переконайтеся, що **список** або **бібліотеку** , що містить очікуваний вміст, налаштовано на дозвіл на відображення вмісту в результатах пошуку.</span><span class="sxs-lookup"><span data-stu-id="0bac6-106">Check that the **list** or **library** that contains the expected content is set to allow content to appear in search results.</span></span> <span data-ttu-id="0bac6-107">Дотримуйтеся вказівок у [списку Показати вміст із списків або бібліотек у результатах пошуку](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-from-lists-or-libraries-in-search-results).</span><span class="sxs-lookup"><span data-stu-id="0bac6-107">Follow the steps in [Show content from lists or libraries in search results](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-from-lists-or-libraries-in-search-results).</span></span>

3. <span data-ttu-id="0bac6-108">Переконайтеся, що сторінка, документ або Настроювана Розмітка сторінки публікується як **Основна версія.**</span><span class="sxs-lookup"><span data-stu-id="0bac6-108">Verify that the page, document, or custom page layout is published as a **Major version.**</span></span> <span data-ttu-id="0bac6-109">Дотримуйтесь крок 3 в [пошуку не повертає всі результати в SharePoint Online](https://go.microsoft.com/fwlink/?linkid=874525).</span><span class="sxs-lookup"><span data-stu-id="0bac6-109">Follow step 3 in [Search doesn't return all results in SharePoint Online](https://go.microsoft.com/fwlink/?linkid=874525).</span></span>

4. <span data-ttu-id="0bac6-110">Переконайтеся, що користувач має **дозволи** на перегляд вмісту.</span><span class="sxs-lookup"><span data-stu-id="0bac6-110">Verify that the user has **permissions** to view the content.</span></span> <span data-ttu-id="0bac6-111">Виконайте дії, описані в [розумінні рівнів дозволів у SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="0bac6-111">Follow the steps in [Understanding permission levels in SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span></span>
    
5. <span data-ttu-id="0bac6-112">Якщо схему пошуку змінено, додавши нову керовану властивість, відредагувавши керовану властивість або видаливши керовану властивість, потрібно буде виконати запит на обхід і повторне індексування.</span><span class="sxs-lookup"><span data-stu-id="0bac6-112">If the search schema has been changed by adding a new managed property, by editing a managed property, or by removing a managed property then requesting a crawl and re-index will be required.</span></span> <span data-ttu-id="0bac6-113">**Повторно індексувати** вміст, виконавши дії, зазначені в [ручному запиті на сканування та повторну індексацію сайту, бібліотеки або списку](https://docs.microsoft.com/sharepoint/crawl-site-content).</span><span class="sxs-lookup"><span data-stu-id="0bac6-113">**Re-index** the content by following the steps in [Manually request crawling and re-indexing of a site, a library or a list](https://docs.microsoft.com/sharepoint/crawl-site-content).</span></span> <span data-ttu-id="0bac6-114">Це може зайняти деякий час, зачекайте 24 години, перш ніж знову перевірити результати.</span><span class="sxs-lookup"><span data-stu-id="0bac6-114">This might take a while, wait 24 hours before checking the results again.</span></span>

<span data-ttu-id="0bac6-115">Докладніші відомості наведено в розділі [Увімкнення вмісту на сайті для пошуку](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span><span class="sxs-lookup"><span data-stu-id="0bac6-115">For more information, see [Enable content on a site to be searchable](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span></span> 
  

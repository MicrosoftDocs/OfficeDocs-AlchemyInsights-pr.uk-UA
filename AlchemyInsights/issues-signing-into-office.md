---
title: Проблеми з входом у програми Microsoft 365
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000571"
- "2574"
ms.openlocfilehash: 02841a1b4e92eec94fc6409941d91618f02518c1
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/15/2021
ms.locfileid: "51836624"
---
# <a name="issues-signing-into-microsoft-365-apps"></a><span data-ttu-id="34535-102">Проблеми із входом у програми Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="34535-102">Issues signing into Microsoft 365 Apps</span></span>

<span data-ttu-id="34535-103">Щоб вирішити проблеми із входом у програми Microsoft 365, спробуйте наведені нижче параметри на відповідному комп'ютері.</span><span class="sxs-lookup"><span data-stu-id="34535-103">To fix sign-in issues with Microsoft 365 apps, try the following options on the affected machine:</span></span>  

- <span data-ttu-id="34535-104">Відомості про вирішення [поширених проблем](https://docs.microsoft.com/office365/troubleshoot/administration/disabling-adal-wam-not-recommended#recommendations-on-resolving-common-sign-in-issues) із входом у Windows див. в цій сторінці.</span><span class="sxs-lookup"><span data-stu-id="34535-104">For Windows, see [Recommendations on resolving common sign-in issues](https://docs.microsoft.com/office365/troubleshoot/administration/disabling-adal-wam-not-recommended#recommendations-on-resolving-common-sign-in-issues)</span></span>
- <span data-ttu-id="34535-105">Відомості для комп'ютерів Mac див. в статтях Не вдається ввійти в програму  [Office 2016 для Mac.](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail)</span><span class="sxs-lookup"><span data-stu-id="34535-105">For Mac, see  [Can't sign in to an Office 2016 for Mac app](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail)</span></span>

<span data-ttu-id="34535-106">**Порада.** На комп’ютерах із Windows ми можемо діагностувати та автоматично усунути кілька поширених проблем із входом у систему Office.</span><span class="sxs-lookup"><span data-stu-id="34535-106">**Tip** On Windows machines, we can diagnose and automatically fix several common Office sign-in issues for you.</span></span> <span data-ttu-id="34535-107">Завантажте та запустіть  **[Помічник із підтримки й відновлення від Microsoft](https://aka.ms/SaRA-OfficeSignInScenario)**, щоб скористатися нашим автоматизованим інструментом.</span><span class="sxs-lookup"><span data-stu-id="34535-107">Download and run the  **[Microsoft Support and Recovery Assistant](https://aka.ms/SaRA-OfficeSignInScenario)** to use our automated tool.</span></span>

<span data-ttu-id="34535-108">**Примітка.** Не рекомендовано вимикати сучасну автентифікацію (ADAL) або керування веб-обліковими записами (WAM) для вирішення проблем із входом або **активацією.**</span><span class="sxs-lookup"><span data-stu-id="34535-108">**Note:** Disabling Modern Authentication (ADAL) or Web Account Management (WAM) for fixing sign-in or activation issues  **is not recommended**.</span></span> <span data-ttu-id="34535-109">Якщо під час підключення до Microsoft 365 за допомогою пакета Office 2013 виникають помилки, активуйте сучасну автентифікацію [для](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication)  клієнта Office.</span><span class="sxs-lookup"><span data-stu-id="34535-109">If the errors occur while connecting to Microsoft 365 using Office 2013, ensure that you [enable modern authentication](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication)  for Office client.</span></span>

<span data-ttu-id="34535-110">Конкретні дії з виправлення неполадок див. в перенесеннях:</span><span class="sxs-lookup"><span data-stu-id="34535-110">For specific troubleshooting actions, see:</span></span>

[<span data-ttu-id="34535-111">Проблеми з входом після оновлення пакета Office 2016 до збірки 16.0.7967 у Windows 10</span><span class="sxs-lookup"><span data-stu-id="34535-111">Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10</span></span>](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016)  

[<span data-ttu-id="34535-112">Не вдається ввійти у свій обліковий запис, видаливши організацію, як-от Office 365, Azure або Intune.</span><span class="sxs-lookup"><span data-stu-id="34535-112">You can't sign in to your organizational account such as Office 365, Azure, or Intune</span></span>](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-365-azure-intune)

[<span data-ttu-id="34535-113">Виправлення неполадок із програмами, не пов'язаними з браузерами, які не можуть увійти в Office 365, Azure або Intune</span><span class="sxs-lookup"><span data-stu-id="34535-113">How to troubleshoot non-browser apps that can't sign in to Office 365, Azure, or Intune</span></span>](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1?ui=en-US&rs=en-US&ad=US)

[<span data-ttu-id="34535-114">Неодноразово запитувати облікові дані в Office</span><span class="sxs-lookup"><span data-stu-id="34535-114">Repeatedly prompted for credentials in Office</span></span>](https://docs.microsoft.com/office365/troubleshoot/authentication/access-denied-when-connect-to-office-365)
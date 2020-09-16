---
title: Обмеження доступу в SharePoint або OneDrive
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: cc6f93ba8ae3a030f83da5eca2d28dcf38f0f8f7
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 09/15/2020
ms.locfileid: "47800917"
---
# <a name="irm-protection-to-sharepoint-files"></a><span data-ttu-id="35ad7-102">Захист IRM до файлів SharePoint</span><span class="sxs-lookup"><span data-stu-id="35ad7-102">IRM Protection to SharePoint files</span></span>


<span data-ttu-id="35ad7-103">У службі SharePoint Online захист IRM застосовується до файлів на рівні списку та бібліотеки.</span><span class="sxs-lookup"><span data-stu-id="35ad7-103">Within SharePoint Online, IRM protection is applied to files at the list and library level.</span></span> <span data-ttu-id="35ad7-104">Перш ніж організація може використовувати захист IRM, спочатку потрібно настроїти керування правами.</span><span class="sxs-lookup"><span data-stu-id="35ad7-104">Before your organization can use IRM protection, you must first set up Rights Management.</span></span> <span data-ttu-id="35ad7-105">Служба IRM покладається на службу керування "Лазурний захист" від «Azure» захисту інформації для шифрування та призначення обмежень використання.</span><span class="sxs-lookup"><span data-stu-id="35ad7-105">IRM relies on the Azure Rights Management service from Azure Information Protection to encrypt and assign usage restrictions.</span></span> <span data-ttu-id="35ad7-106">Деякі передплати на Microsoft 365 містять "блакитне керування правами", але не всі.</span><span class="sxs-lookup"><span data-stu-id="35ad7-106">Some Microsoft 365 subscriptions include Azure Rights Management, but not all.</span></span> 

<span data-ttu-id="35ad7-107">Докладніше про це див. в статтях:</span><span class="sxs-lookup"><span data-stu-id="35ad7-107">To learn more, see:</span></span>

- <span data-ttu-id="35ad7-108">[Керування застосунками та службами Office за Лазурний](https://docs.microsoft.com/azure/information-protection/understand-explore/office-apps-services-support)час.</span><span class="sxs-lookup"><span data-stu-id="35ad7-108">[How Office applications and services support Azure Rights Management](https://docs.microsoft.com/azure/information-protection/understand-explore/office-apps-services-support).</span></span>

- <span data-ttu-id="35ad7-109">[Настроювання керування правами доступу до інформації (IRM) у центрі адміністрування SharePoint](https://docs.microsoft.com/microsoft-365/compliance/set-up-irm-in-sp-admin-center).</span><span class="sxs-lookup"><span data-stu-id="35ad7-109">[Set up Information Rights Management (IRM) in SharePoint admin center](https://docs.microsoft.com/microsoft-365/compliance/set-up-irm-in-sp-admin-center).</span></span>

- <span data-ttu-id="35ad7-110">[Засіб IRM – Увімкнення бібліотек і списків документів SharePoint](https://docs.microsoft.com/microsoft-365/compliance/set-up-irm-in-sp-admin-center#irm-enable-sharepoint-document-libraries-and-lists).</span><span class="sxs-lookup"><span data-stu-id="35ad7-110">[IRM-enable SharePoint document libraries and lists](https://docs.microsoft.com/microsoft-365/compliance/set-up-irm-in-sp-admin-center#irm-enable-sharepoint-document-libraries-and-lists).</span></span>

- <span data-ttu-id="35ad7-111">[Керування правами доступу до інформації в Office](https://support.office.com/Article/Information-Rights-Management-in-Office-c7a70797-6b1e-493f-acf7-92a39b85e30c).</span><span class="sxs-lookup"><span data-stu-id="35ad7-111">[Information Rights Management in Office](https://support.office.com/Article/Information-Rights-Management-in-Office-c7a70797-6b1e-493f-acf7-92a39b85e30c).</span></span>

- <span data-ttu-id="35ad7-112">[Керування правами доступу до інформації в службі Exchange Online](https://docs.microsoft.com/microsoft-365/compliance/information-rights-management-in-exchange-online).</span><span class="sxs-lookup"><span data-stu-id="35ad7-112">[Information Rights Management in Exchange Online](https://docs.microsoft.com/microsoft-365/compliance/information-rights-management-in-exchange-online).</span></span>



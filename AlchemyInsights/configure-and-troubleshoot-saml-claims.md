---
title: Настроювання та усунення несправностей із вимогами SAML
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 01/17/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "7799"
- "9004356"
ms.openlocfilehash: 306d2f451856a66f06447e3acd73e065da71cd64
ms.sourcegitcommit: 6d02eb533fd74199af6b20f714b3720991da2c4a
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 01/18/2021
ms.locfileid: "49901294"
---
# <a name="configure-and-troubleshoot-saml-claims"></a><span data-ttu-id="337ec-102">Настроювання та усунення несправностей із вимогами SAML</span><span class="sxs-lookup"><span data-stu-id="337ec-102">Configure and troubleshoot SAML claims</span></span>

<span data-ttu-id="337ec-103">Щоб налаштувати та усунути вимоги SAML, виконайте наведені нижче дії.</span><span class="sxs-lookup"><span data-stu-id="337ec-103">To configure and troubleshoot SAML claims:</span></span>

1. <span data-ttu-id="337ec-104">Виконайте вказівки, описані в [цій статті](https://docs.microsoft.com/azure/active-directory/develop/active-directory-enterprise-app-role-management) , щоб настроїти твердження про роль, що видається в ПОЛІ "самл" для корпоративних програм.</span><span class="sxs-lookup"><span data-stu-id="337ec-104">Follow the steps outlined in [this article](https://docs.microsoft.com/azure/active-directory/develop/active-directory-enterprise-app-role-management) to configure the role claim issued in the SAML token for enterprise applications.</span></span>
2. <span data-ttu-id="337ec-105">Виконайте кроки, описані в [цій статті](https://docs.microsoft.com/azure/active-directory/develop/active-directory-saml-claims-customization) , щоб настроїти претензії, видані в маркер SAML для корпоративних програм.</span><span class="sxs-lookup"><span data-stu-id="337ec-105">Follow the steps in [this article](https://docs.microsoft.com/azure/active-directory/develop/active-directory-saml-claims-customization) to customize claims issued in the SAML token for enterprise applications.</span></span>
3. <span data-ttu-id="337ec-106">Виконайте кроки, описані в [цій статті](https://docs.microsoft.com/azure/active-directory/develop/active-directory-claims-mapping) , щоб настроїти претензії, що викидаються в маркери для певної програми в клієнті.</span><span class="sxs-lookup"><span data-stu-id="337ec-106">Follow the steps in [this article](https://docs.microsoft.com/azure/active-directory/develop/active-directory-claims-mapping) to customize claims emitted in tokens for a specific app in a tenant.</span></span>
4. <span data-ttu-id="337ec-107">Прочитайте [цю статтю](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-for-claims-aware-applications) , щоб дізнатися, як працювати з застосунками-обізнаними програмами в проксі-застосунку.</span><span class="sxs-lookup"><span data-stu-id="337ec-107">Read [this article](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-for-claims-aware-applications) to understand working with claims-aware apps in Application Proxy.</span></span>
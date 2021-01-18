---
title: Синхронізація служби доменів
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 01/15/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003245"
- "7922"
- "7921"
ms.openlocfilehash: b35d3a402bc08a27a818209385c5666b901fa524
ms.sourcegitcommit: 83fe2a8d060794fdf58445b469b30a3294b7a9b6
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 01/15/2021
ms.locfileid: "49885559"
---
# <a name="domain-service-synchronization"></a><span data-ttu-id="82b14-102">Синхронізація служби доменів</span><span class="sxs-lookup"><span data-stu-id="82b14-102">Domain service synchronization</span></span>

<span data-ttu-id="82b14-103">Об'єкти та облікові дані в керованих доменах служб домену Azure Active Directory (Azure AD DS) можна створювати локально в домені або синхронізуватися з клієнта Azure Active Directory (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="82b14-103">Objects and credentials in an Azure Active Directory Domain Services (Azure AD DS) managed domain can either be created locally within the domain, or synchronized from an Azure Active Directory (Azure AD) tenant.</span></span> <span data-ttu-id="82b14-104">Коли ви вперше розгортаєте Azure AD DS, автоматичне односторонне синхронізації настроєно та розпочато для реплікації об'єктів із Лазурого AD.</span><span class="sxs-lookup"><span data-stu-id="82b14-104">When you first deploy Azure AD DS, an automatic one-way synchronization is configured and initiated to replicate the objects from Azure AD.</span></span> <span data-ttu-id="82b14-105">Ця односторонна синхронізація продовжує виконуватися у фоновому режимі, щоб зберегти в полі "Лазурний" домен з будь-якими змінами, які мають будь-які зміни від лазурових ОБ'ЯВ.</span><span class="sxs-lookup"><span data-stu-id="82b14-105">This one-way synchronization continues to run in the background to keep the Azure AD DS managed domain up-to-date with any changes from Azure AD.</span></span> <span data-ttu-id="82b14-106">Немає синхронізації з Azure AD DS назад до лазурових ОБ'ЯВ.</span><span class="sxs-lookup"><span data-stu-id="82b14-106">No synchronization occurs from Azure AD DS back to Azure AD.</span></span>

<span data-ttu-id="82b14-107">Докладні відомості про синхронізацію служби domain Active Directory наведено в статті [синхронізація служби доменів](https://docs.microsoft.com/azure/active-directory-domain-services/synchronization).</span><span class="sxs-lookup"><span data-stu-id="82b14-107">For more details on Azure Active Directory domain service synchronization, see [Domain Service Synchronization](https://docs.microsoft.com/azure/active-directory-domain-services/synchronization).</span></span> 

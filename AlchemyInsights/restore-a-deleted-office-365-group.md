---
title: Відновлення видаленої групи Microsoft 365
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "98"
- "1200024"
ms.assetid: bc0396ea-c426-4d1d-bb89-ced602d06fb6
ms.openlocfilehash: 6f640093cd099f20d3a95eede5c141ad74838b0b
ms.sourcegitcommit: 7b2e5078dd65f11af6650e692a7ea48e91f544e0
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/02/2021
ms.locfileid: "51505731"
---
# <a name="restore-a-deleted-microsoft-365-group"></a><span data-ttu-id="0cfe7-102">Відновлення видаленої групи Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="0cfe7-102">Restore a deleted Microsoft 365 group</span></span>

<span data-ttu-id="0cfe7-103">Видалену групу Microsoft 365 або Microsoft Teams можна відновити протягом 30 днів із видалення.</span><span class="sxs-lookup"><span data-stu-id="0cfe7-103">You can restore a deleted Microsoft 365 group or Microsoft Teams within 30 days from the deletion.</span></span>

1. <span data-ttu-id="0cfe7-104">Щоб увійти в Центр адміністрування Microsoft 365 і перелічити видалені групи та команди, перейдіть у Центр адміністрування [Microsoft 365.](https://aka.ms/RestoreDeletedGroup)</span><span class="sxs-lookup"><span data-stu-id="0cfe7-104">To login to Microsoft 365 admin center and list the deleted groups and teams, go to the [Microsoft 365 admin center](https://aka.ms/RestoreDeletedGroup).</span></span>

    <span data-ttu-id="0cfe7-105">**Примітка.** Увійдіть під обліковим записом, призначеним адміністратору-власнику або групі.</span><span class="sxs-lookup"><span data-stu-id="0cfe7-105">**Note:** Log in using the account that is assigned to either the tenant administrator or the groups admin role.</span></span>

1. <span data-ttu-id="0cfe7-106">Виберіть видалену групу Microsoft 365 або Teams, які потрібно відновити, і натисніть **кнопку Відновити групу**.</span><span class="sxs-lookup"><span data-stu-id="0cfe7-106">Select the deleted Microsoft 365 group/Teams to be restored and click **restore group**.</span></span>

    <span data-ttu-id="0cfe7-107">Якщо через конфліктну SMTP-адресу не вдається відновити групу, скористайтеся наведеною нижче командою, щоб знайти об'єкт, який призведе до конфлікту, і видаліть SMTP-адресу:</span><span class="sxs-lookup"><span data-stu-id="0cfe7-107">If the group can't be restored because of a conflicting SMTP address, use following command to find the object that’s causing conflict and remove the SMTP address:</span></span>

    `Get-Recipient -Filter "EmailAddresses -eq '<conflictingsmtpaddress>'"`

    <span data-ttu-id="0cfe7-108">**Примітка.** У деяких випадках відновлення групи та всіх її даних може тривати до 24 годин.</span><span class="sxs-lookup"><span data-stu-id="0cfe7-108">**Note:** In some cases, it might take as long as 24 hours for the group and all of its data to be restored.</span></span>

    <span data-ttu-id="0cfe7-109">Докладні відомості або про те, як відновити групи за допомогою PowerShell, див. в статті Відновлення видаленої групи [Microsoft 365.](https://go.microsoft.com/fwlink/?linkid=867802)</span><span class="sxs-lookup"><span data-stu-id="0cfe7-109">For more info, or to learn how to restore groups using PowerShell, see [Restore a deleted Microsoft 365 group](https://go.microsoft.com/fwlink/?linkid=867802).</span></span>
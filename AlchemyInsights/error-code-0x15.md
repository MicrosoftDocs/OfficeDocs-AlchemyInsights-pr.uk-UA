---
title: Код помилки 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: У разі появи повідомлення про помилку під час активації Office 2013 віддалений робочий стіл служб (РДС) розгортання, розглянути питання про включення ADAL шляхом редагування реєстру.
ms.openlocfilehash: 6d4076ecb5c6ee3c3cf4c4610ad4aa29ab477d8a
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/23/2019
ms.locfileid: "32402760"
---
<span data-ttu-id="bf33e-103">У разі появи повідомлення про помилку під час активації Office 2013 віддалений робочий стіл служб (РДС) розгортання, розглянути питання про включення ADAL шляхом редагування реєстру.</span><span class="sxs-lookup"><span data-stu-id="bf33e-103">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span> 
  
|<span data-ttu-id="bf33e-104">**Ключ реєстру**</span><span class="sxs-lookup"><span data-stu-id="bf33e-104">**Registry key**</span></span>|<span data-ttu-id="bf33e-105">**Тип**</span><span class="sxs-lookup"><span data-stu-id="bf33e-105">**Type**</span></span>|<span data-ttu-id="bf33e-106">**Значення**</span><span class="sxs-lookup"><span data-stu-id="bf33e-106">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="bf33e-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="bf33e-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="bf33e-108">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="bf33e-108">REG_DWORD</span></span>  <br/> |<span data-ttu-id="bf33e-109">1</span><span class="sxs-lookup"><span data-stu-id="bf33e-109">1</span></span>  <br/> |
   
<span data-ttu-id="bf33e-110">Докладніше перегляньте [Увімкнути сучасних автентикації Office 2013 на пристроях Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="bf33e-110">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="bf33e-111">АДАЛІЯ типово увімкнено у Office 365 ProPlus і Office 2016.</span><span class="sxs-lookup"><span data-stu-id="bf33e-111">ADAL is enabled by default in Office 365 ProPlus and Office 2016.</span></span> <span data-ttu-id="bf33e-112">> віддалений робочий стіл служб (РДС) була названа служб терміналів.</span><span class="sxs-lookup"><span data-stu-id="bf33e-112">>  Remote Desktop Services (RDS) was previously named Terminal Services.</span></span> 
  


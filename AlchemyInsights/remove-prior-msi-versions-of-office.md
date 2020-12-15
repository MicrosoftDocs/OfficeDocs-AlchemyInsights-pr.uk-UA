---
title: Видалення попередньої версії пакета Office MSI
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 12/15/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003886"
- "6940"
ms.openlocfilehash: 26ab610cb204149536bd23c830a1b8558892a7c0
ms.sourcegitcommit: c033720921cb9a06b9560eedef4f1935e69a846b
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 12/15/2020
ms.locfileid: "49680780"
---
# <a name="remove-prior-msi-versions-of-office"></a><span data-ttu-id="f7d80-102">Видалення попередньої версії пакета Office MSI</span><span class="sxs-lookup"><span data-stu-id="f7d80-102">Remove prior MSI versions of Office</span></span>

<span data-ttu-id="f7d80-103">Перш ніж інсталювати пакет Office 365 ProPlus, я рекомендую видалити попередні версії пакета Office Installer (MSI).</span><span class="sxs-lookup"><span data-stu-id="f7d80-103">I recommend removing prior Windows Installer (MSI) versions of Office before installing Office 365 ProPlus.</span></span> <span data-ttu-id="f7d80-104">Ось як це зробити:</span><span class="sxs-lookup"><span data-stu-id="f7d80-104">Here's how to do this:</span></span>

1. <span data-ttu-id="f7d80-105">Якщо ви використовували MSI для інсталяції пакета Office, можна видалити пакет Office за допомогою засобу розгортання Office (ODT).</span><span class="sxs-lookup"><span data-stu-id="f7d80-105">If you used MSI to install Office, you can use the Office Deployment Tool (ODT) to uninstall Office.</span></span> <span data-ttu-id="f7d80-106">Ви можете використовувати елемент RemoveMSI у файлі **configuration.xml** .</span><span class="sxs-lookup"><span data-stu-id="f7d80-106">You can use the RemoveMSI element in your **configuration.xml** file.</span></span>
1. <span data-ttu-id="f7d80-107">Виконайте вказівки в цій статті: [центр відповідності системи безпеки Office 365 &.](https://go.microsoft.com/fwlink/p/?linkid=2077143)</span><span class="sxs-lookup"><span data-stu-id="f7d80-107">Follow the instruction in this article: [Office 365 Security & Compliance Center.](https://go.microsoft.com/fwlink/p/?linkid=2077143)</span></span>
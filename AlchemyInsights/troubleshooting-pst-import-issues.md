---
title: Виправлення неполадок під час імпорту PST
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1800027"
- "1225"
ms.openlocfilehash: 5065b9895954371e4298c98e8aadb67ba8f140fd
ms.sourcegitcommit: c977687a7dd03288a9ba396cf2a48ea384d72634
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/27/2021
ms.locfileid: "52059836"
---
# <a name="troubleshooting-pst-import-issues"></a><span data-ttu-id="27ce8-102">Виправлення неполадок під час імпорту PST</span><span class="sxs-lookup"><span data-stu-id="27ce8-102">Troubleshooting PST import issues</span></span>

- <span data-ttu-id="27ce8-103">Відомості про те, як імпортувати дані самого клієнта Outlook, див. в статті Вирішення проблем з імпортом [PST-файлу Outlook.](https://support.office.com/article/Fix-problems-importing-an-Outlook-pst-file-2d2e50dc-5c36-4ab2-ab50-f1be733b3d6e)</span><span class="sxs-lookup"><span data-stu-id="27ce8-103">If you are importing within the Outlook client itself, see [Fix problems importing an Outlook .pst file](https://support.office.com/article/Fix-problems-importing-an-Outlook-pst-file-2d2e50dc-5c36-4ab2-ab50-f1be733b3d6e).</span></span>

- <span data-ttu-id="27ce8-104">Якщо служба імпорту застрягає, зверніть увагу, що розмір кожного файлу PST, який передається до сховища Azure, не має перевищує 20 ГБ.</span><span class="sxs-lookup"><span data-stu-id="27ce8-104">If you are using Import Service and it's stuck, note that each PST file that you upload to the Azure Storage location should be no larger than 20GB.</span></span> <span data-ttu-id="27ce8-105">Файли PST, розмір які перевищує 20 ГБ, можуть вплинути на продуктивність імпорту PST-файлів.</span><span class="sxs-lookup"><span data-stu-id="27ce8-105">PST files larger than 20GB may impact the performance of the PST import process.</span></span> <span data-ttu-id="27ce8-106">Докладні відомості про виправлення неполадок, пов'язаних із завданнями, що застрягли, див. в статі Проблеми, які [впливають на завдання імпорту PST.](https://docs.microsoft.com/office365/troubleshoot/pst-import-service/issues-with-pst-import-job)</span><span class="sxs-lookup"><span data-stu-id="27ce8-106">For more information troubleshooting stuck jobs, see [Issues that affect PST import jobs](https://docs.microsoft.com/office365/troubleshoot/pst-import-service/issues-with-pst-import-job).</span></span>

- <span data-ttu-id="27ce8-107">Щоб перевірити стан певного завдання імпорту, скористайтеся [get-MailboxImportRequest -batchname.](https://docs.microsoft.com/powershell/module/exchange/mailboxes/get-mailboximportrequest)</span><span class="sxs-lookup"><span data-stu-id="27ce8-107">If you want to verify the status of a specific Import job, use [Get-MailboxImportRequest -batchname](https://docs.microsoft.com/powershell/module/exchange/mailboxes/get-mailboximportrequest).</span></span>

- <span data-ttu-id="27ce8-108">Докладні відомості про службу імпорту див. в огляді [імпорту PST-файлів організації.](https://docs.microsoft.com/microsoft-365/compliance/importing-pst-files-to-office-365?view=o365-worldwide)</span><span class="sxs-lookup"><span data-stu-id="27ce8-108">For full details on the import service, see [Overview of importing your organization's PST files](https://docs.microsoft.com/microsoft-365/compliance/importing-pst-files-to-office-365?view=o365-worldwide).</span></span>

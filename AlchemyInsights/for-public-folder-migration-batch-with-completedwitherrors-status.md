---
title: Для спільної папки міграції пакета з Повзвєпомилками стан
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3532"
ms.openlocfilehash: 4243cdf0170fed1eadac6560d2a04e1a861c63e5
ms.sourcegitcommit: 9aaa61d717e0fd475d2e9f0507c42aa40d073b5f
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 02/15/2020
ms.locfileid: "42043629"
---
# <a name="for-public-folder-migration-batch-with-completedwitherrors-status"></a><span data-ttu-id="bae7c-102">Для спільної папки міграції пакета з Повзвєпомилками стан</span><span class="sxs-lookup"><span data-stu-id="bae7c-102">For Public folder migration batch with CompletedWithErrors status</span></span>

<span data-ttu-id="bae7c-103">Виконайте такі дії для завершення пакета, пропускаючи великі/погані елементи:</span><span class="sxs-lookup"><span data-stu-id="bae7c-103">Use the following steps to complete the batch, skipping the large/bad items:</span></span> 
1. <span data-ttu-id="bae7c-104">Затвердити пропущені елементи пакета міграції:</span><span class="sxs-lookup"><span data-stu-id="bae7c-104">Approve the skipped items on migration batch:</span></span>

    <span data-ttu-id="bae7c-105">Набір-Мізаціїпакетна \<назва>-відповідні елементи</span><span class="sxs-lookup"><span data-stu-id="bae7c-105">Set-MigrationBatch \<batchname> -ApproveSkippedItems</span></span> 
2. <span data-ttu-id="bae7c-106">Використайте наведену нижче команду, щоб затвердити пропущені елементи на запити міграції, які "синхронізовано", але не завершено:</span><span class="sxs-lookup"><span data-stu-id="bae7c-106">Use the following command to approve the skipped items on migration requests that are “Synced” but not completed:</span></span>

    <span data-ttu-id="bae7c-107">$pf = Get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics-Включаєпорт; Для кожного ($i в $pf) {Якщо ($i. LargeItemsEncountered-gt 0-або $i. BadItemsEncountered-gt 0) {Set-PublicFolderMailboxMigrationRequest $i. Ідентифікація. ідентифікатор _ елемента ([Дата й час]:: UtcNow)}}</span><span class="sxs-lookup"><span data-stu-id="bae7c-107">$pf=Get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics -IncludeReport; ForEach ($i in $pf) {if ($i.LargeItemsEncountered -gt 0 -or $i.BadItemsEncountered -gt 0) {Set-PublicFolderMailboxMigrationRequest $i.Identity.IdentifyingGuid -SkippedItemApprovalTime $([DateTime]::UtcNow)}}</span></span>
3. <span data-ttu-id="bae7c-108">Пакет міграції та запити повинні поновлювати та завершити через кілька хвилин.</span><span class="sxs-lookup"><span data-stu-id="bae7c-108">The migration batch and requests should resume and complete in a few minutes.</span></span>


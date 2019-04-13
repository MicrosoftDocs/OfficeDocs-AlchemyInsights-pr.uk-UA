---
title: 902 (помилки синхронізації через дублювання об'єктів)
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 5/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 902
ms.assetid: 9d9277a5-c825-4512-8d54-7138b2ee0c40
ms.openlocfilehash: ce7eeb07cfde16e6d6856a9369c042dcf4f05b63
ms.sourcegitcommit: 1a4b8fa9e38a95ca811085af516edb81caf2018c
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/13/2019
ms.locfileid: "31859125"
---
# <a name="sync-errors-due-to-duplicate-objects"></a><span data-ttu-id="8014a-102">Помилки синхронізації через дублікати об'єктів</span><span class="sxs-lookup"><span data-stu-id="8014a-102">Sync errors due to duplicate objects</span></span>

<span data-ttu-id="8014a-103">Ви можете отримати одне з таких повідомлень про помилку, після завершення синхронізації каталогів:</span><span class="sxs-lookup"><span data-stu-id="8014a-103">You might receive one of the following error messages when directory synchronization finishes:</span></span>

- <span data-ttu-id="8014a-104">Не вдалося оновити цей об'єкт Microsoft Online Services, тому що такі атрибути, пов'язані з цим об'єктом є значення, які вже можуть бути пов'язані з іншого об'єкта в поточному каталозі.</span><span class="sxs-lookup"><span data-stu-id="8014a-104">Unable to update this object in Microsoft Online Services because the following attributes associated with this object have values that may already be associated with another object in your local directory.</span></span>

- <span data-ttu-id="8014a-105">Синхронізовані об'єкта з однаковою адресою проксі уже існує у вашому каталозі Microsoft Online Services.</span><span class="sxs-lookup"><span data-stu-id="8014a-105">A synchronized object with the same proxy address already exists in your Microsoft Online Services directory.</span></span>

- <span data-ttu-id="8014a-106">Не вдалося оновити цей об'єкт, тому що такі атрибути, пов'язаними з об'єктом є значення, які вже можуть бути пов'язані з іншого об'єкта в місцевих каталог послуг: UserPrincipalName.</span><span class="sxs-lookup"><span data-stu-id="8014a-106">Unable to update this object because the following attributes associated with this object have values that may already be associated with another object in your local directory services: UserPrincipalName.</span></span>

<span data-ttu-id="8014a-107">Щоб виявити й усунути проблему, завантажте та запустіть [IdFix DirSync помилка виправляти інструмент](https://www.microsoft.com/download/details.aspx?id=36832).</span><span class="sxs-lookup"><span data-stu-id="8014a-107">To identify and fix the issue, download and run the [IdFix DirSync Error Remediation Tool](https://www.microsoft.com/download/details.aspx?id=36832).</span></span>

<span data-ttu-id="8014a-108">Докладніше перегляньте [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span><span class="sxs-lookup"><span data-stu-id="8014a-108">For more information, see [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span></span>

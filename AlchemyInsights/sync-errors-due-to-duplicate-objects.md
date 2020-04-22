---
title: 902 (помилки синхронізації через повторювані об'єкти)
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 902
ms.assetid: 9d9277a5-c825-4512-8d54-7138b2ee0c40
ms.openlocfilehash: 6ea833e0c4aebe72bc5c02e3dc10c1edc4136dcc
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/22/2020
ms.locfileid: "43767162"
---
# <a name="sync-errors-due-to-duplicate-objects"></a><span data-ttu-id="fa897-102">Помилки синхронізації через повторювані об'єкти</span><span class="sxs-lookup"><span data-stu-id="fa897-102">Sync errors due to duplicate objects</span></span>

<span data-ttu-id="fa897-103">Може з'явитися одне з таких повідомлень про помилку під час синхронізації каталогів, що закінчується в Microsoft 365:</span><span class="sxs-lookup"><span data-stu-id="fa897-103">You might receive one of the following error messages when directory synchronization finishes in Microsoft 365:</span></span>

- <span data-ttu-id="fa897-104">Не вдалося оновити цей об'єкт у службах Microsoft Online, оскільки такі атрибути, пов'язані з цим об'єктом, мають значення, які можуть бути вже пов'язані з іншим об'єктом у локальному каталозі.</span><span class="sxs-lookup"><span data-stu-id="fa897-104">Unable to update this object in Microsoft Online Services because the following attributes associated with this object have values that may already be associated with another object in your local directory.</span></span>

- <span data-ttu-id="fa897-105">Синхронізований об'єкт з однаковою проксі-адресою вже існує у вашому каталозі служб Microsoft Online Services.</span><span class="sxs-lookup"><span data-stu-id="fa897-105">A synchronized object with the same proxy address already exists in your Microsoft Online Services directory.</span></span>

- <span data-ttu-id="fa897-106">Не вдалося оновити цей об'єкт, оскільки такі атрибути, пов'язані з цим об'єктом, мають значення, які можуть бути вже пов'язані з іншим об'єктом у службах локальних каталогів: ім'я користувача.</span><span class="sxs-lookup"><span data-stu-id="fa897-106">Unable to update this object because the following attributes associated with this object have values that may already be associated with another object in your local directory services: UserPrincipalName.</span></span>

<span data-ttu-id="fa897-107">Щоб визначити та вирішити цю проблему, завантажте та запустіть [засіб виправлення помилок IdFix DirSync](https://www.microsoft.com/download/details.aspx?id=36832).</span><span class="sxs-lookup"><span data-stu-id="fa897-107">To identify and fix the issue, download and run the [IdFix DirSync Error Remediation Tool](https://www.microsoft.com/download/details.aspx?id=36832).</span></span>

<span data-ttu-id="fa897-108">Для отримання додаткових відомостей див. [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span><span class="sxs-lookup"><span data-stu-id="fa897-108">For more information, see [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span></span>

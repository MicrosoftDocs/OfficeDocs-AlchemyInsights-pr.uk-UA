---
title: Призначення ролі журналу аудиту в центрі відповідності системи безпеки Office 365 &
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/21/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "7363"
- "9000722"
ms.openlocfilehash: 0eb470b6c17def5517db2f866ef40898b36662ed
ms.sourcegitcommit: c202c0df2d141e63f4f7eb13a56efbfc2f57348f
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/05/2021
ms.locfileid: "50527557"
---
# <a name="assign-an-audit-log-role-in-the-office-365-security--compliance-center"></a><span data-ttu-id="7579d-102">Призначення ролі журналу аудиту в центрі відповідності системи безпеки Office 365 &</span><span class="sxs-lookup"><span data-stu-id="7579d-102">Assign an Audit Log role in the Office 365 Security & Compliance Center</span></span>

<span data-ttu-id="7579d-103">Щоб виконати пошук у журналі аудиту Office 365, адміністратор має призначати роль **журналів аудиту лише для перегляду** або роль **журналів аудиту** в службі Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="7579d-103">To search the Office 365 audit log, an administrator must be assigned the **View-Only Audit Logs** role or the **Audit Logs** role in Exchange Online.</span></span> <span data-ttu-id="7579d-104">Ці ролі призначено для керування відповідністю і групами ролей керування організацією за замовчуванням.</span><span class="sxs-lookup"><span data-stu-id="7579d-104">These roles are assigned to the Compliance Management and Organization Management role groups by default.</span></span> <span data-ttu-id="7579d-105">Глобальні адміністратори в Office 365 і Microsoft 365 автоматично додаються як учасники групи ролей керування організацією.</span><span class="sxs-lookup"><span data-stu-id="7579d-105">Global administrators in Office 365 and Microsoft 365 are automatically added as members of the Organization Management role group.</span></span>

<span data-ttu-id="7579d-106">Щоб дозволити користувачу виконувати пошук за мінімальним рівнем привілеїв, створіть настроювану рольову групу в службі Exchange Online, **додайте роль** журналів аудиту, що стосується **лише подання** , а потім додайте користувача як учасника нової рольової групи.</span><span class="sxs-lookup"><span data-stu-id="7579d-106">To enable a user to search with the minimum level of privileges, create a custom role group in Exchange Online, add the **View-Only Audit Logs** role or **Audit Logs** role, and then add the user as a member of the new role group.</span></span>

<span data-ttu-id="7579d-107">Докладні відомості наведено в статті [Керування рольовими групами в службі Exchange Online](https://docs.microsoft.com/Exchange/permissions-exo/role-groups) і [Пошук у журналі аудиту в центрі відповідності безпеки &](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance).</span><span class="sxs-lookup"><span data-stu-id="7579d-107">For more information, see [Manage role groups in Exchange Online](https://docs.microsoft.com/Exchange/permissions-exo/role-groups) and [Search the audit log in the Security & Compliance Center](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance).</span></span>
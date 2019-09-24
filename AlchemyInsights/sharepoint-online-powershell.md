---
title: SharePoint Online PowerShell
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 9/18/19
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000266"
- "1867"
ms.openlocfilehash: 00ec337ce34da9d3c3fba0a71602c3078a556552
ms.sourcegitcommit: 6b102e079a7d30298105fd811a67efb707d6d5bf
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 09/23/2019
ms.locfileid: "37123019"
---
# <a name="sharepoint-online-powershell"></a><span data-ttu-id="bb329-102">SharePoint Online PowerShell</span><span class="sxs-lookup"><span data-stu-id="bb329-102">Sharepoint Online PowerShell</span></span>

<span data-ttu-id="bb329-103">Робота з PowerShell або скриптами в SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="bb329-103">Working with PowerShell or Scripts within Sharepoint Online?</span></span> <span data-ttu-id="bb329-104">Відвідайте посилання нижче для отримання додаткової інформації.</span><span class="sxs-lookup"><span data-stu-id="bb329-104">Visit the links below for more information.</span></span>
- [<span data-ttu-id="bb329-105">Початок роботи з SharePoint онлайнова Оболонка керування</span><span class="sxs-lookup"><span data-stu-id="bb329-105">Getting started with SharePoint Online Management Shell</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps)
- [<span data-ttu-id="bb329-106">Підключення до спо PowerShell з багатофакторної аутентифікації (МЗС)</span><span class="sxs-lookup"><span data-stu-id="bb329-106">Connect to SPO PowerShell with multifactor authentication (MFA)</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps#to-connect-with-multifactor-authentication-mfa)
- <span data-ttu-id="bb329-107">[SharePoint шаблони та практики (ПНП)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) містить бібліотеку PowerShell команд, що дозволяє виконувати складні дії з управління спо.</span><span class="sxs-lookup"><span data-stu-id="bb329-107">[SharePoint Patterns and Practices (PnP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) contains a library of PowerShell commands that allows you to perform complex management actions towards SPO.</span></span>

> [!NOTE]
> - <span data-ttu-id="bb329-108">Якщо у вас виникли проблеми з підключенням до оболонки керування спо, переконайтеся, що ви оновили до останньої версії і спробуйте [повторно імпортувати модуль](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) за допомогою *"Імпорт-модуль Microsoft. Online. SharePoint. PowerShell".*</span><span class="sxs-lookup"><span data-stu-id="bb329-108">If you are having issues connecting with the SPO management shell, make sure that you have updated to the latest version and try to [re-import the module](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) using *“Import-Module Microsoft.Online.SharePoint.PowerShell”.*</span></span>
> - <span data-ttu-id="bb329-109">Якщо ви намагаєтеся запустити клієнтський сценарій об'єктної моделі, вам потрібно буде мати [SharePoint Online клієнтські КОМПОНЕНТИ SDK](https://www.microsoft.com/download/details.aspx?id=42038) , інстальованих на локальному комп'ютері.</span><span class="sxs-lookup"><span data-stu-id="bb329-109">If you are attempting to run client-side object model scripts, you will need to have the [Sharepoint Online Client Components SDK](https://www.microsoft.com/download/details.aspx?id=42038) installed on your local machine.</span></span>
> - <span data-ttu-id="bb329-110">Якщо у вас виникли проблеми з запуском сценаріїв з PowerShell, ви можете розглянути запуск PowerShell як адміністратор і змінити [політику виконання](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).</span><span class="sxs-lookup"><span data-stu-id="bb329-110">If you are having issues running scripts from PowerShell, you may want to consider running PowerShell as an Administrator and changing the [Execution Policy](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).</span></span>
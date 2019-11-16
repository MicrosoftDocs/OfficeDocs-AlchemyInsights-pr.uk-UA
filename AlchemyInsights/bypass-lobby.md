---
title: Обійти лобі
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2673"
- "9000740"
ms.openlocfilehash: bf8be9ffe2bfa45ed2cf149c1c4fa118b40e816d
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 11/15/2019
ms.locfileid: "37768461"
---
# <a name="control-lobby-settings-and-level-of-participation"></a><span data-ttu-id="04c70-102">Контроль параметрів лобі та рівень участі</span><span class="sxs-lookup"><span data-stu-id="04c70-102">Control lobby settings and level of participation</span></span>

<span data-ttu-id="04c70-103">Якщо ви хочете дозволити всім, зокрема, комутованих, зовнішніх і анонімних користувачів, щоб обійти фойє у Microsoft teams, ви можете використовувати PowerShell, щоб зробити це.</span><span class="sxs-lookup"><span data-stu-id="04c70-103">If you'd like to allow everyone, including Dial-in, external, and anonymous users to bypass the lobby in Microsoft Teams, you can use PowerShell to do it.</span></span> <span data-ttu-id="04c70-104">Нижче наведено приклад змінення політики глобального наради для вашої організації.</span><span class="sxs-lookup"><span data-stu-id="04c70-104">Here's an example of modifying the global meeting policy for your organization:</span></span>

`Set-CsTeamsMeetingPolicy -Identity Global -AutoAdmittedUsers "Everyone" -AllowPSTNUsersToBypassLobby $True`

<span data-ttu-id="04c70-105">Цю команду в даний час вимагає використання Skype для бізнесу PowerShell модуль.</span><span class="sxs-lookup"><span data-stu-id="04c70-105">This cmdlet currently requires the use of Skype for Business PowerShell module.</span></span> <span data-ttu-id="04c70-106">Щоб отримати параметри для використання цього командлета, перевірте [керування політиками за допомогою PowerShell](https://docs.microsoft.com/en-us/microsoftteams/teams-powershell-overview#managing-policies-via-powershell).</span><span class="sxs-lookup"><span data-stu-id="04c70-106">To get setup to use this cmdlet, check out [Managing policies via PowerShell](https://docs.microsoft.com/en-us/microsoftteams/teams-powershell-overview#managing-policies-via-powershell).</span></span>

<span data-ttu-id="04c70-107">Ви можете створити нову політику, яку потрібно буде застосувати до користувачів.</span><span class="sxs-lookup"><span data-stu-id="04c70-107">You can set up a new policy, which you'll then need to apply it to users.</span></span> <span data-ttu-id="04c70-108">Якщо ви змінюєте глобальну політику, вона автоматично застосовуватиметься до користувачів.</span><span class="sxs-lookup"><span data-stu-id="04c70-108">If you modify the Global policy it'll automatically apply to users.</span></span> <span data-ttu-id="04c70-109">Для будь-яких змін в політиці необхідно почекати принаймні 4 години і до 24 годин, щоб політика набрали сили.</span><span class="sxs-lookup"><span data-stu-id="04c70-109">For any policy change you need to wait at least 4 hours and up to 24 hours for the policies to take effect.</span></span>

<span data-ttu-id="04c70-110">Обов'язково перегляньте документацію нижче, перш ніж вносити ці зміни, щоб точно зрозуміти, що це дозволяє.</span><span class="sxs-lookup"><span data-stu-id="04c70-110">Be sure to review the documentation below before making these changes to understand exactly what this allows.</span></span>

## <a name="understanding-teams-meeting-lobby-policy-controls"></a><span data-ttu-id="04c70-111">Знайомство з командами переговорних елементів керування політикою</span><span class="sxs-lookup"><span data-stu-id="04c70-111">Understanding Teams meeting lobby policy controls</span></span>

- <span data-ttu-id="04c70-112">[Автоматично визнати](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) , що люди в політиці для Організатора, що контролює, чи є люди приєднатися до наради безпосередньо або чекати у фойє, поки вони не будуть допущені автентифікованим користувачем.</span><span class="sxs-lookup"><span data-stu-id="04c70-112">[Automatically admit people](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#automatically-admit-people) is a per-organizer policy that controls whether people join a meeting directly or wait in the lobby until they are admitted by an authenticated user.</span></span>

- <span data-ttu-id="04c70-113">[Дозволити анонімним людям розпочати нараду](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) – це політика Організатора, яка керує тим, чи можуть користувачі анонімних користувачів, ВКЛЮЧНО з B2B та федеративними користувачами, приєднатися до наради користувача без автентифікованого користувача з організації.</span><span class="sxs-lookup"><span data-stu-id="04c70-113">[Allow anonymous people to start a meeting](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-anonymous-people-to-start-a-meeting) is a per-organizer policy that controls whether anonymous people, including B2B and federated users, can join the user's meeting without an authenticated user from the organization in attendance.</span></span>

- <span data-ttu-id="04c70-114">[Дозволити комутованого користувачів, щоб обійти фойє](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**скоро**) є для Організатора політики, яка контролює, чи люди, які підключаються по телефону приєднатися до наради безпосередньо або чекати в холі, незалежно від того, **автоматично визнати, люди** налаштування.</span><span class="sxs-lookup"><span data-stu-id="04c70-114">[Allow dial-in users to bypass the lobby](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams#allow-dial-in-users-to-bypass-the-lobby-coming-soon) (**coming soon**) is a per-organizer policy that controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the **Automatically admit people** setting.</span></span>

- <span data-ttu-id="04c70-115">[Дозволити організаторам змінювати параметри фойє](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**скоро**)-це політика Організатора, яка керує тим, чи може Організатор наради перевизначити параметри фойє, які встановлюються адміністратором у **автоматичному режимі, допускають** користувачів і **дозволяють користувачам телефонувати до фойє** під час планування нової наради.</span><span class="sxs-lookup"><span data-stu-id="04c70-115">[Allow organizers to override lobby settings](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams#allow-organizers-to-override-lobby-settings-coming-soon) (**coming soon**) is a per-organizer policy that controls whether the meeting organizer can override the lobby settings that an admin set in **Automatically admit people** and **Allow dial-in users to bypass the lobby** when they schedule a new meeting.</span></span>

<span data-ttu-id="04c70-116">**Примітка:** Для повного огляду політики зборів Microsoft teams прочитайте [команди керування політикою нарад](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) .</span><span class="sxs-lookup"><span data-stu-id="04c70-116">**Note:** Read [Manage meeting policies in Teams](https://docs.microsoft.com/en-us/microsoftteams/meeting-policies-in-teams) for a complete overview of Microsoft Teams meeting policies.</span></span>

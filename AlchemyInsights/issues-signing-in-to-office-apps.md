---
title: Проблеми з входом у програми Microsoft 365
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000571"
- "2560"
ms.openlocfilehash: e4f2fea5c2f368ae240614ee1f7bc729338dd75d
ms.sourcegitcommit: f28dafa0f727870038f72bc904da926daf4ec07b
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 06/05/2020
ms.locfileid: "44579958"
---
# <a name="fixing-the-microsoft-365-apps-sorry-another-account-from-your-organization-is-already-signed-in-message"></a><span data-ttu-id="4c647-102">Виправлення Microsoft 365 Apps "Вибачте, інший обліковий запис з вашої організації вже ввійшли в" повідомлення</span><span class="sxs-lookup"><span data-stu-id="4c647-102">Fixing the Microsoft 365 apps "Sorry, another account from your organization is already signed in" message</span></span>

<span data-ttu-id="4c647-103">Щоб виправити цю помилку, спробуйте виконати наведені нижче дії.</span><span class="sxs-lookup"><span data-stu-id="4c647-103">To fix this error, try the following:</span></span>

- <span data-ttu-id="4c647-104">Видалити всі робочі облікові записи, крім відповідного облікового запису, за допомогою настройок Windows > **доступ до роботи або школи**.</span><span class="sxs-lookup"><span data-stu-id="4c647-104">Remove all work accounts, except the affected account, using Windows Settings > **Access work or school**.</span></span>
- <span data-ttu-id="4c647-105">[Очистіть облікові дані Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) за допомогою диспетчера облікових даних Windows.</span><span class="sxs-lookup"><span data-stu-id="4c647-105">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="4c647-106">**Примітка:** Шлях до реєстру для Office 2016 змінено на 16,0.</span><span class="sxs-lookup"><span data-stu-id="4c647-106">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="4c647-107">(Напр.: \ програмне забезпеченя \mice\)</span><span class="sxs-lookup"><span data-stu-id="4c647-107">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>
- <span data-ttu-id="4c647-108">Відкрийте програму Office **, виберіть**  >  **обліковий запис**для  >  **входу**. Ввійдіть за допомогою облікового запису користувача з дійсною ліцензією.</span><span class="sxs-lookup"><span data-stu-id="4c647-108">Open an Office app, choose **File** > **Account** > **Sign Out**. Then sign in using a user account with a valid license.</span></span> <span data-ttu-id="4c647-109">Докладні відомості див. в статті [Облікові записи в Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span><span class="sxs-lookup"><span data-stu-id="4c647-109">For detailed information, see [Accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span></span>
- <span data-ttu-id="4c647-110">Для Mac див. статтю [Не вдається ввійти в програму Office 2016 для Mac](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).</span><span class="sxs-lookup"><span data-stu-id="4c647-110">For Mac, see [Can't sign in to an Office 2016 for Mac app](https://docs.microsoft.com/office365/troubleshoot/authentication/sign-in-to-office-2016-for-mac-fail).</span></span>

<span data-ttu-id="4c647-111">Для отримання додаткових відомостей див. ["Вибачте, інший обліковий запис з вашої організації вже ввійшли на цьому комп'ютері" в Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in).</span><span class="sxs-lookup"><span data-stu-id="4c647-111">For more information, see ["Sorry, another account from your organization is already signed in on this computer" in Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in).</span></span>
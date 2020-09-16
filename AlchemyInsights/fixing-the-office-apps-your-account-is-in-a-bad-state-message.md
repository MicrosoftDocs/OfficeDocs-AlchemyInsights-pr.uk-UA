---
title: Виправлення програм Microsoft 365, які обліковий запис має поганий стан повідомлення
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2558"
- "9000571"
ms.openlocfilehash: ec529291ec9406eba9dc2b0f2cc7a93c77fa3456
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 09/14/2020
ms.locfileid: "47744566"
---
# <a name="fixing-the-microsoft-365-apps-your-account-is-in-a-bad-state-error"></a><span data-ttu-id="b1e53-102">Помилка фіксації програм Microsoft 365 "ваш обліковий запис перебуває в поганій державі"</span><span class="sxs-lookup"><span data-stu-id="b1e53-102">Fixing the Microsoft 365 apps "Your account is in a bad state" error</span></span>

<span data-ttu-id="b1e53-103">Щоб виправити цю помилку, виконайте наведені нижче дії на ураженого комп'ютера.</span><span class="sxs-lookup"><span data-stu-id="b1e53-103">To fix this error, try the following options on the affected computer:</span></span>

- <span data-ttu-id="b1e53-104">Відкрийте програму Office, виберіть пункт **File**  >  **обліковий запис**файлу, щоб  >  **вийти з усіх облікових записів**.</span><span class="sxs-lookup"><span data-stu-id="b1e53-104">Open an Office app, select **File** > **Account** > **Sign Out of all accounts**.</span></span> <span data-ttu-id="b1e53-105">Увійдіть знову, використовуючи обліковий запис користувача з дійсною ліцензією.</span><span class="sxs-lookup"><span data-stu-id="b1e53-105">Sign in again using a user account with a valid license.</span></span> <span data-ttu-id="b1e53-106">Докладні відомості див. в статті [Облікові записи в Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span><span class="sxs-lookup"><span data-stu-id="b1e53-106">For detailed information, see [Accounts in Office](https://support.office.com/article/accounts-in-office-628ea040-f265-49de-b986-be09c3ebf8a9).</span></span>
- <span data-ttu-id="b1e53-107">[Очищення облікових даних Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) за допомогою диспетчера облікових даних Windows.</span><span class="sxs-lookup"><span data-stu-id="b1e53-107">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br>
  <span data-ttu-id="b1e53-108">**Примітка.** Шляхи реєстру для Office 2016 змінилися на 16,0.</span><span class="sxs-lookup"><span data-stu-id="b1e53-108">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="b1e53-109">Наприклад, \Software\Microsoft\Office\16.0\Common\Identity</span><span class="sxs-lookup"><span data-stu-id="b1e53-109">For example, \Software\Microsoft\Office\16.0\Common\Identity</span></span>\
- <span data-ttu-id="b1e53-110">Якщо помилка виникає під час підключення до Office 365 за допомогою служби Office 2013, [Увімкніть сучасну автентифікацію](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication) для клієнта Office.</span><span class="sxs-lookup"><span data-stu-id="b1e53-110">If the error occurs while connecting to Office 365 using Office 2013, [enable modern authentication](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication) for the Office client.</span></span>

<span data-ttu-id="b1e53-111">Щоб отримати докладні відомості, Дізнайтеся, [як усунути неполадки, які не є браузерами, які не можуть входити в Microsoft 365, Azure або InTune](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1).</span><span class="sxs-lookup"><span data-stu-id="b1e53-111">For more information, see [How to troubleshoot non-browser apps that can't sign in to Microsoft  365, Azure, or Intune](https://support.office.com/article/how-to-troubleshoot-non-browser-apps-that-can-t-sign-in-to-office-365-azure-or-intune-3ba1b268-66f6-462c-b0e5-070f5c2603c1).</span></span>


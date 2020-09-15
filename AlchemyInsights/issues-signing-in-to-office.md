---
title: Проблеми з входом в програми Microsoft 365
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
- "9000571"
- "2556"
ms.openlocfilehash: 3c016b198ad43f35c8149dde71c28a2f7fc3bd38
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 09/14/2020
ms.locfileid: "47695308"
---
# <a name="blank-sign-in-screen-in-microsoft-365-apps"></a><span data-ttu-id="893d1-102">Пустий екран входу в програмах Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="893d1-102">Blank sign-in screen in Microsoft 365 apps</span></span>

<span data-ttu-id="893d1-103">Щоб вирішити цю проблему, виконайте наведені нижче дії.</span><span class="sxs-lookup"><span data-stu-id="893d1-103">To fix this issue, try the following:</span></span>
- <span data-ttu-id="893d1-104">Інсталюйте найновіші оновлення для [Windows](https://support.microsoft.com/help/4027667/windows-10-update) і [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span><span class="sxs-lookup"><span data-stu-id="893d1-104">Install the latest updates for [Windows](https://support.microsoft.com/help/4027667/windows-10-update) and [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span></span>
- <span data-ttu-id="893d1-105">Скидання параметрів браузера Internet Explorer: **Перехід до параметрів**  >  **Internet Options**  >  **Advanced**  >  браузера Internet**Explorer** (Зверніть увагу, що ви втратите додаткові параметри), а потім спробуйте ввійти в Office ще раз.</span><span class="sxs-lookup"><span data-stu-id="893d1-105">Reset Internet Explorer options: Go to **Tools** > **Internet Options** > **Advanced** > **Reset Internet Explorer Settings** (note that you will lose custom settings), and then try signing in to Office again.</span></span>
- <span data-ttu-id="893d1-106">Вимкнення засобу захисту від захисника Windows (WDAG) або будь-якого аналогічного брандмауера або антивірусної програми:</span><span class="sxs-lookup"><span data-stu-id="893d1-106">Disable the Windows Defender Application Guard (WDAG) or any similar firewall or anti-virus program:</span></span>
    1. <span data-ttu-id="893d1-107">На панелі керування виберіть пункт **програми**, а потім – **Увімкнути або вимкнути функції Windows**.</span><span class="sxs-lookup"><span data-stu-id="893d1-107">In Control Panel, go to **Programs**, and then choose **Turn Windows features on or off**.</span></span>
    2. <span data-ttu-id="893d1-108">Якщо ввімкнуто засіб захисту від захисника Windows, виконайте його вимкнення.</span><span class="sxs-lookup"><span data-stu-id="893d1-108">If Windows Defender Application Guard is enabled, try disabling it.</span></span><br/>
    <span data-ttu-id="893d1-109">**Примітка.** Можливо, знадобиться перезавантажити комп'ютер.</span><span class="sxs-lookup"><span data-stu-id="893d1-109">**Note:** You may need to restart the computer.</span></span>
- <span data-ttu-id="893d1-110">Переконайтеся, що компонент Plug-in служби Microsoft. AAD. брокерсько [AAD WAM](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-1) не блокує будь-яку програму або брандмауер/антивірусна програма.</span><span class="sxs-lookup"><span data-stu-id="893d1-110">Ensure that the Microsoft.AAD.BrokerPlugin [AAD WAM plug-in](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-1) is not being blocked by any application or firewall/anti-virus program.</span></span>
- <span data-ttu-id="893d1-111">[Очищення облікових даних Office](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) за допомогою диспетчера облікових даних Windows.</span><span class="sxs-lookup"><span data-stu-id="893d1-111">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="893d1-112">**Примітка.** Шляхи реєстру для Office 2016 змінилися на 16,0.</span><span class="sxs-lookup"><span data-stu-id="893d1-112">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="893d1-113">(Приклад: \Software\microsoft\office\16.0\coment\identity\)</span><span class="sxs-lookup"><span data-stu-id="893d1-113">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>

<span data-ttu-id="893d1-114">Щоб отримати докладніші відомості, ознайомтеся з [проблемами підключення під час входу в Office 2016 збірці 16.0.7967 у Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span><span class="sxs-lookup"><span data-stu-id="893d1-114">For more information, see [Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span></span>
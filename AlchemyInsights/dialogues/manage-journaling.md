---
title: Керування журнальної
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004299"
- "7677"
ms.openlocfilehash: 2fcd0f386d2da8cad19fcc9872482bb75fe00dd2
ms.sourcegitcommit: c202c0df2d141e63f4f7eb13a56efbfc2f57348f
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/05/2021
ms.locfileid: "50527461"
---
# <a name="manage-journaling"></a><span data-ttu-id="de437-102">Керування журнальної</span><span class="sxs-lookup"><span data-stu-id="de437-102">Manage journaling</span></span>

<span data-ttu-id="de437-103">Журналювання може допомогти вашій організації відповідати на юридичні, нормативні та організаційні вимоги щодо відповідності, записавши вхідні та вихідні повідомлення електронної пошти.</span><span class="sxs-lookup"><span data-stu-id="de437-103">Journaling can help your organization respond to legal, regulatory, and organizational compliance requirements by recording inbound and outbound email communications.</span></span> <span data-ttu-id="de437-104">Зверніть увагу:</span><span class="sxs-lookup"><span data-stu-id="de437-104">Keep in mind:</span></span>

* <span data-ttu-id="de437-105">Перш ніж керувати журнальної функцією, потрібно мати дозволи на керування [організацією](https://go.microsoft.com/fwlink/?linkid=2115259) та [керування записами](https://go.microsoft.com/fwlink/?linkid=2115469) .</span><span class="sxs-lookup"><span data-stu-id="de437-105">You need to have [Organization Management](https://go.microsoft.com/fwlink/?linkid=2115259) and [Records Management](https://go.microsoft.com/fwlink/?linkid=2115469) permissions before you can manage journaling.</span></span>
* <span data-ttu-id="de437-106">Потрібно мати поштову скриньку журналу та (опціонально) настроєну поштову скриньку журналювання.</span><span class="sxs-lookup"><span data-stu-id="de437-106">You need to have a journal mailbox and (optionally) an alternate journaling mailbox configured.</span></span> <span data-ttu-id="de437-107">Докладні відомості наведено в статті [Настроювання журналювання у службі Exchange Online](https://go.microsoft.com/fwlink/?linkid=2115260).</span><span class="sxs-lookup"><span data-stu-id="de437-107">To learn more, see [Configure Journaling in Exchange Online](https://go.microsoft.com/fwlink/?linkid=2115260).</span></span>
* <span data-ttu-id="de437-108">У службі Exchange Online є обмеження кількості правил, які можна створити в журналі.</span><span class="sxs-lookup"><span data-stu-id="de437-108">In Exchange Online, there's a limit to the number of journal rules that you can create.</span></span> <span data-ttu-id="de437-109">Щоб отримати докладні відомості, ознайомтеся з [правилами "журнал", "транспорт" і "Вхідні"](https://go.microsoft.com/fwlink/?linkid=2115261).</span><span class="sxs-lookup"><span data-stu-id="de437-109">For details, see [Journal, transport, and inbox rule limits](https://go.microsoft.com/fwlink/?linkid=2115261).</span></span>
* <span data-ttu-id="de437-110">Служба Exchange Online не підтримує доставку звітів журналів до поштової скриньки Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="de437-110">Exchange Online doesn't support delivering journal reports to an Exchange Online mailbox.</span></span> <span data-ttu-id="de437-111">Ви повинні вказати адресу електронної пошти локальної системи архівування або службу архівування третьої сторони як поштову скриньку журналювання.</span><span class="sxs-lookup"><span data-stu-id="de437-111">You must specify the email address of an on-premises archiving system or a third-party archiving service as the journaling mailbox.</span></span>

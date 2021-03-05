---
title: Перевірка адрес для пересилання в поштових скриньках
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 17/02/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9002486"
- "7524"
ms.openlocfilehash: 1b0a6c8fe368196f2d1f9811aea895c2c024b2e6
ms.sourcegitcommit: 251e2e82571fb3bb1fbe3dbf7bfca30e004b3373
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/05/2021
ms.locfileid: "50483928"
---
# <a name="check-for-forwarding-addresses-on-mailboxes"></a><span data-ttu-id="d3b02-102">Перевірка адрес для пересилання в поштових скриньках</span><span class="sxs-lookup"><span data-stu-id="d3b02-102">Check for forwarding addresses on mailboxes</span></span>

<span data-ttu-id="d3b02-103">Іноді хакерам пересилаються повідомлення електронної пошти для користувачів, тому спочатку ми перевіряємо адреси для пересилання та правила в поштовій скриньці.</span><span class="sxs-lookup"><span data-stu-id="d3b02-103">Sometimes hackers forward users' email messages to themselves, so first we'll check for forwarding addresses and rules on the mailbox.</span></span> <span data-ttu-id="d3b02-104">Після цього ми перевіримо журнали аудиту.</span><span class="sxs-lookup"><span data-stu-id="d3b02-104">Then we'll check the audit logs.</span></span> <span data-ttu-id="d3b02-105">Ось як можна перевірити, чи є адреси для пересилання.</span><span class="sxs-lookup"><span data-stu-id="d3b02-105">Here's how to check for forwarding addresses:</span></span>

1. <span data-ttu-id="d3b02-106">Виберіть **користувачів**  >  **активні користувачі**.</span><span class="sxs-lookup"><span data-stu-id="d3b02-106">Select **Users** > **Active users**.</span></span>
1. <span data-ttu-id="d3b02-107">Виберіть користувача, обліковий запис якого було скомпрометовано.</span><span class="sxs-lookup"><span data-stu-id="d3b02-107">Select the user whose account has been compromised.</span></span>
1. <span data-ttu-id="d3b02-108">У меню, що Відкриється, розгорніть розділ **Параметри пошти**, а потім натисніть кнопку **редагувати** для **пересилання електронної пошти**.</span><span class="sxs-lookup"><span data-stu-id="d3b02-108">In the flyout that appears, expand **Mail Settings**, and then click **Edit** for **Email forwarding**.</span></span>
1. <span data-ttu-id="d3b02-109">Видаліть усі адреси для пересилання, які не розпізнаються.</span><span class="sxs-lookup"><span data-stu-id="d3b02-109">Remove any forwarding addresses you don't recognize.</span></span>
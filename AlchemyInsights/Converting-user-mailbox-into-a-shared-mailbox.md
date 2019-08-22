---
title: Перетворення поштової скриньки користувача на спільну поштову скриньку?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
ROBOTS: NOINDEX, NOFOLLOW
description: ''
ms.openlocfilehash: ab34b8939b95b29bedb797f640dd744bc783adef
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 08/22/2019
ms.locfileid: "36496456"
---
# <a name="convert-a-user-mail-box-into-a-shared-mailbox"></a><span data-ttu-id="ad410-102">Перетворення спільної поштової скриньки користувача поштова скринька</span><span class="sxs-lookup"><span data-stu-id="ad410-102">Convert a user mail box into a shared mailbox</span></span>

<span data-ttu-id="ad410-103">Можна тільки перетворювати поштової скриньки користувача для спільної поштової скриньки, якщо користувач має ліцензію Exchange.</span><span class="sxs-lookup"><span data-stu-id="ad410-103">You can only convert a user mailbox to a shared mailbox if the user has an Exchange license.</span></span> <span data-ttu-id="ad410-104">Після того, як поштової скриньки перетворюється, він буде продовжувати відображатися у списку активних користувачів, оскільки цей список включає в себе спільні поштові скриньки.</span><span class="sxs-lookup"><span data-stu-id="ad410-104">After the mailbox is converted, it will continue to show up in the active users list because that list includes shared mailboxes.</span></span> <span data-ttu-id="ad410-105">Однак, перетвореного поштової скриньки також з'являться у списку спільної поштової скриньки.</span><span class="sxs-lookup"><span data-stu-id="ad410-105">However, the converted mailbox will also show up in the shared mailbox list.</span></span> 
  
<span data-ttu-id="ad410-106">Якщо ви спробуєте перетворити поштової скриньки у консолі адміністратора Exchange і перетворення здійснено неуспішно, очистьте кеш веб-переглядача та файли cookie і повторіть спробу.</span><span class="sxs-lookup"><span data-stu-id="ad410-106">If you try to convert a mailbox in the Exchange Admin Console and the conversion fails, clear your browser cache and cookies and try again.</span></span> <span data-ttu-id="ad410-107">Якщо він все ще працює, спробуйте перетворити поштової скриньки Exchange Management Shell, запустивши таку команду:</span><span class="sxs-lookup"><span data-stu-id="ad410-107">If it still isn't working, try converting the mailbox in the Exchange Management Shell by running the following command:</span></span>
  
```
Set-Mailbox -Type Shared
```

<span data-ttu-id="ad410-108">Більш поштової скриньки перетворення детальна інформація доступна в [перетворити користувача поштову скриньку для спільної поштової скриньки](https://docs.microsoft.com/office365/admin/email/convert-user-mailbox-to-shared-mailbox).</span><span class="sxs-lookup"><span data-stu-id="ad410-108">More mailbox conversion information is available in [Convert a user mailbox to a shared mailbox](https://docs.microsoft.com/office365/admin/email/convert-user-mailbox-to-shared-mailbox).</span></span>
  

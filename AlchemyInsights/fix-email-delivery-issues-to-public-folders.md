---
title: Вирішення проблем із доставкою електронної пошти до спільних папок із підтримкою пошти
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1956"
- "3500007"
ms.assetid: ''
ms.openlocfilehash: e261fe60843555fa45927b0a6b36e1ccf79fb028
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/22/2020
ms.locfileid: "43716373"
---
# <a name="fix-email-delivery-issues-to-mail-enabled-public-folders"></a><span data-ttu-id="b2df1-102">Вирішення проблем із доставкою електронної пошти до спільних папок із підтримкою пошти</span><span class="sxs-lookup"><span data-stu-id="b2df1-102">Fix email delivery issues to mail-enabled public folders</span></span>

<span data-ttu-id="b2df1-103">Якщо зовнішні відправники не можуть надсилати повідомлення до спільних папок із підтримкою пошти, а відправники отримують помилку: не вдалося **знайти (550 5.4.1)**, переконайтеся, що домен електронної пошти для спільної папки настроєно як внутрішній домен ретрансляції замість основного домену:</span><span class="sxs-lookup"><span data-stu-id="b2df1-103">If external senders can't send messages to your mail-enabled public folders, and the senders receive the error: **couldn't be found (550 5.4.1)**, verify the email domain for the public folder is configured as an internal relay domain instead of an authoritative domain:</span></span>

1. <span data-ttu-id="b2df1-104">Відкрийте [Центр адміністрування для Exchange](https://docs.microsoft.com/Exchange/exchange-admin-center).</span><span class="sxs-lookup"><span data-stu-id="b2df1-104">Open the [Exchange admin center (EAC)](https://docs.microsoft.com/Exchange/exchange-admin-center).</span></span>

2. <span data-ttu-id="b2df1-105">Перейдіть до **пошти** \> **допустимі домени**, виберіть допустимий домен і натисніть кнопку **змінити**.</span><span class="sxs-lookup"><span data-stu-id="b2df1-105">Go to **Mail flow** \> **Accepted domains**, select the accepted domain, and then click **Edit**.</span></span>

3. <span data-ttu-id="b2df1-106">На сторінці властивостей, що відкриється, якщо тип домену встановлено **авторитетне**, змініть значення на **внутрішній ретранслятор** і натисніть кнопку **зберегти**.</span><span class="sxs-lookup"><span data-stu-id="b2df1-106">In the properties page that opens, if the domain type is set to **Authoritative**, change the value to **Internal relay** and then click **Save**.</span></span>

<span data-ttu-id="b2df1-107">Якщо зовнішні відправники отримують помилку, у **вас немає дозволу (550 5.7.13)**, виконайте таку команду в [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) , щоб переглянути дозволи для анонімних користувачів у спільних папок:</span><span class="sxs-lookup"><span data-stu-id="b2df1-107">If external senders receive the error **you don't have permission (550 5.7.13)**, run the following command in [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) to see the permissions for anonymous users in the public folder:</span></span>

<span data-ttu-id="b2df1-108">`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous`Наприклад, `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.</span><span class="sxs-lookup"><span data-stu-id="b2df1-108">`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous` For example, `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.</span></span>

<span data-ttu-id="b2df1-109">Щоб дозволити зовнішнім користувачам надсилати повідомлення електронної пошти до цієї спільної папки, додайте права доступу до CreateItems, щоб користувач анонімний.</span><span class="sxs-lookup"><span data-stu-id="b2df1-109">To allow external users to send email to this public folder, add the CreateItems access right to the user Anonymous.</span></span> <span data-ttu-id="b2df1-110">Наприклад, `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.</span><span class="sxs-lookup"><span data-stu-id="b2df1-110">For example, `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.</span></span>

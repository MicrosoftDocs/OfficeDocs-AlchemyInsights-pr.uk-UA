---
title: Помилка надсилання повідомлень електронної пошти, заблокованих SpamHaus
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "255"
- "3100003"
ms.assetid: fa98ab4a-92eb-45e9-8d57-ad10fb123042
ms.openlocfilehash: 8b5ac1df0b6a07a475345235a8b4b555d6881147
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/15/2021
ms.locfileid: "51813745"
---
# <a name="error-sending-email-client-host-blocked-using-spamhaus"></a><span data-ttu-id="d94a9-102">Помилка надсилання електронної пошти: хост клієнта заблоковано за допомогою Spamhaus</span><span class="sxs-lookup"><span data-stu-id="d94a9-102">Error sending email: Client host blocked using Spamhaus</span></span>

<span data-ttu-id="d94a9-103">IP-адреса, яка надіслали повідомлення, міститься в списку заблокованих відправників [Spamhaus.](https://go.microsoft.com/fwlink/p/?linkid=123245)</span><span class="sxs-lookup"><span data-stu-id="d94a9-103">The IP address that sent the message is on a block list owned by [Spamhaus](https://go.microsoft.com/fwlink/p/?linkid=123245).</span></span> <span data-ttu-id="d94a9-104">Причини блокування Spamhaus – це зламовані облікові записи, комп'ютери, на яких використовується злам, спільний доступ до загальнодоступної IP-адреси та політики інтернет-провайдера.</span><span class="sxs-lookup"><span data-stu-id="d94a9-104">Reasons for being blocked by Spamhaus include compromised accounts, compromised machines sharing a public IP address, and Internet Service Provider (ISP) policies.</span></span> <span data-ttu-id="d94a9-105">Можливі виправлення:</span><span class="sxs-lookup"><span data-stu-id="d94a9-105">Possible fixes are:</span></span>
  
- <span data-ttu-id="d94a9-106">Для заблокованих вхідних повідомлень, для яких ви керуєте вихідним сервером електронної пошти, потрібно визначити причину та видалити блок із веб-сайту Spamhaus.</span><span class="sxs-lookup"><span data-stu-id="d94a9-106">For blocked inbound messages where you control the source email server, you need to determine the cause and remove the block from the Spamhaus website.</span></span>

- <span data-ttu-id="d94a9-107">Якщо блокуються вхідні повідомлення, у яких вихідна IP-адреса належить іншій особі, власник адреси має видалити блок із веб-сайту Spamhaus.</span><span class="sxs-lookup"><span data-stu-id="d94a9-107">For blocked inbound messages where the source IP address belongs to someone else, the address owner needs to remove the block from the Spamhaus website.</span></span> <span data-ttu-id="d94a9-108">Якщо IP-адресу включено до списку заблокованих політик, власник може призначити іншу статичну IP-адресу або вилучити з неї іншу.</span><span class="sxs-lookup"><span data-stu-id="d94a9-108">If the IP address is on the Policy Block List (PBL), the owner can assign a different static IP address or remove the address from the PBL.</span></span>

- <span data-ttu-id="d94a9-109">Якщо блокуються вихідні повідомлення з вашого домену, підключеного до корпорації Майкрософт, ця помилка може з'явитися, якщо повідомлення маршрутизуються через сторожню службу.</span><span class="sxs-lookup"><span data-stu-id="d94a9-109">For blocked outbound messages from your domain connected to Microsoft, you can receive this error if the messages are routed through a 3rd party service.</span></span> <span data-ttu-id="d94a9-110">Власника заблокованої IP-адреси можна знайти за допомогою засобу пошуку WHOIS.</span><span class="sxs-lookup"><span data-stu-id="d94a9-110">You can use a WHOIS lookup tool to find the blocked IP address owner.</span></span>

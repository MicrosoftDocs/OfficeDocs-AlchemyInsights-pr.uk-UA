---
title: Мікрозатримки та дроселювання в Exchange Online PowerShell
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3500011"
- "5106"
ms.openlocfilehash: 7ab4e7f18b7b8edf08098af8fe9674f66b1b81f4
ms.sourcegitcommit: fbaa2ce2cfb4d56d8c4cf2fa2d95489bdfcb7ff0
ms.translationtype: HT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/30/2020
ms.locfileid: "43948026"
---
# <a name="micro-delays-or-throttling-in-exchange-online-powershell"></a><span data-ttu-id="f2cfc-102">Мікрозатримки та дроселювання в Exchange Online PowerShell</span><span class="sxs-lookup"><span data-stu-id="f2cfc-102">Micro delays or throttling in Exchange Online PowerShell</span></span>

<span data-ttu-id="f2cfc-103">Під час запуску сценаріїв і командлетів в Exchange Online можуть виникати затримки або відображатися попередження "Застосовано мікрозатримку".</span><span class="sxs-lookup"><span data-stu-id="f2cfc-103">You might see "Micro delay applied" warnings or delays when you run scripts and cmdlets in Exchange Online.</span></span> <span data-ttu-id="f2cfc-104">Ось дві поради щодо цього:</span><span class="sxs-lookup"><span data-stu-id="f2cfc-104">Here are two suggestions related to this:</span></span>

- <span data-ttu-id="f2cfc-105">Можливо, слід спробувати [модуль Exchange Online v2 PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps), що включає командлети, засновані на REST API та значно продуктивніші.</span><span class="sxs-lookup"><span data-stu-id="f2cfc-105">You might want to try using the [Exchange Online v2 PowerShell module](https://docs.microsoft.com/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps), which includes CMDlets that are based on REST API and are significantly more performant.</span></span> <span data-ttu-id="f2cfc-106">Це рішення може чудово підійти для багатьох командлетів Get-, що часто використовуються.</span><span class="sxs-lookup"><span data-stu-id="f2cfc-106">This might be a great solution for a lot of Get- CMDlets that are frequently used.</span></span>
- <span data-ttu-id="f2cfc-107">Якщо вам потрібно використовувати командлети, яких ще немає модуля v2, ознайомтеся зі статтею [Виконання командлетів PowerShell для великих кількостей користувачів в Office 365](https://techcommunity.microsoft.com/t5/exchange-team-blog/updated-running-powershell-cmdlets-for-large-numbers-of-users-in/ba-p/1000628#), у якій обговорюються способи обходу очікуваних обмежень дроселювання PowerShell в Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="f2cfc-107">If you need to use CMDlets that are not covered in the v2 module yet, please see [Running PowerShell cmdlets for large numbers of users in Office 365](https://techcommunity.microsoft.com/t5/exchange-team-blog/updated-running-powershell-cmdlets-for-large-numbers-of-users-in/ba-p/1000628#), which talks about how to get around expected PowerShell throttling limits in Exchange Online.</span></span>

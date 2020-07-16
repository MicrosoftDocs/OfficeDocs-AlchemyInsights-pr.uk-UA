---
title: Відомості про посвідчення в Yammer
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/15/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "6039"
- "9003111"
ms.openlocfilehash: 2c4c2c836d18d2ab45e2368e778c793277b18aa0
ms.sourcegitcommit: b677b85395b7244b2bf2b753468b696b4cf27c8d
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 07/16/2020
ms.locfileid: "45148423"
---
# <a name="about-identity-in-yammer"></a><span data-ttu-id="2f5f2-102">Відомості про посвідчення в Yammer</span><span class="sxs-lookup"><span data-stu-id="2f5f2-102">About identity in Yammer</span></span>

<span data-ttu-id="2f5f2-103">Рекомендується, щоб всі мережі, виконайте такі дії, щоб уникнути проблеми, пов'язані з посвідчення:</span><span class="sxs-lookup"><span data-stu-id="2f5f2-103">It is recommended that all networks take the following steps to avoid identity-related issues:</span></span>

1. <span data-ttu-id="2f5f2-104">Виконання Office 365 посвідчення після підготовки Microsoft 365 облікових записів для користувачів у Azure AD, щоб переконатися, що всі користувачі ввійти за допомогою їх основний обліковий запис Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="2f5f2-104">Enforce Office 365 identity after provisioning Microsoft 365 accounts for users in Azure AD to ensure that all users sign in by using their primary Microsoft 365 account.</span></span> <span data-ttu-id="2f5f2-105">Для отримання додаткових відомостей див. [застосування Office 365 посвідчення для користувачів Yammer](https://docs.microsoft.com/yammer/configure-your-yammer-network/enforce-office-365-identity).</span><span class="sxs-lookup"><span data-stu-id="2f5f2-105">For more info, see [Enforce Office 365 identity for Yammer users](https://docs.microsoft.com/yammer/configure-your-yammer-network/enforce-office-365-identity).</span></span>
2. <span data-ttu-id="2f5f2-106">Консолідація кількох мереж Yammer.</span><span class="sxs-lookup"><span data-stu-id="2f5f2-106">Consolidate multiple Yammer networks.</span></span> <span data-ttu-id="2f5f2-107">Успадковані конфігурації Yammer дозволяють кільком мережам Yammer для підключення до одного клієнта.</span><span class="sxs-lookup"><span data-stu-id="2f5f2-107">Legacy Yammer configurations permit multiple Yammer networks to be connected to one tenant.</span></span> <span data-ttu-id="2f5f2-108">Для отримання додаткових відомостей див. у [мережі міграція-консолідація кількох мереж Yammer](https://docs.microsoft.com/yammer/configure-your-yammer-network/consolidate-multiple-yammer-networks).</span><span class="sxs-lookup"><span data-stu-id="2f5f2-108">For more info, see [Network migration - Consolidate multiple Yammer networks](https://docs.microsoft.com/yammer/configure-your-yammer-network/consolidate-multiple-yammer-networks).</span></span>
3. <span data-ttu-id="2f5f2-109">Крім того, забезпечити ліцензування Yammer для блокування користувачів з Yammer, якщо вони не мають ліцензії.</span><span class="sxs-lookup"><span data-stu-id="2f5f2-109">Optionally, enforce licensing for Yammer to block users from Yammer if they don't have a license.</span></span> <span data-ttu-id="2f5f2-110">Для отримання додаткових відомостей див. [керування ліцензіями користувача Yammer в Office 365](https://docs.microsoft.com/yammer/manage-yammer-users/manage-yammer-licenses-in-office-365).</span><span class="sxs-lookup"><span data-stu-id="2f5f2-110">For more info, see [Manage Yammer user licenses in Office 365](https://docs.microsoft.com/yammer/manage-yammer-users/manage-yammer-licenses-in-office-365).</span></span>
4. <span data-ttu-id="2f5f2-111">Нарешті, аудит список користувачів для старіших мереж Yammer та призупинення попередніх версій користувачів.</span><span class="sxs-lookup"><span data-stu-id="2f5f2-111">Finally, audit the user list for older Yammer networks and suspend legacy users.</span></span> <span data-ttu-id="2f5f2-112">Рекомендується призупинити (деактивувати) користувачів, а не видаляти їх, тому що видалення є незворотнім.</span><span class="sxs-lookup"><span data-stu-id="2f5f2-112">It is recommended that you suspend (deactivate) users instead of deleting them, because deletion is irreversible.</span></span> <span data-ttu-id="2f5f2-113">Щоб отримати додаткові відомості див. [аудит користувачів Yammer в мережах, підключених до Office 365](https://docs.microsoft.com/yammer/manage-yammer-users/audit-users-connected-to-office-365) і [видалення користувачів](https://docs.microsoft.com/yammer/manage-yammer-users/add-block-or-remove-users#remove-users).</span><span class="sxs-lookup"><span data-stu-id="2f5f2-113">For more info, see [Audit Yammer users in networks connected to Office 365](https://docs.microsoft.com/yammer/manage-yammer-users/audit-users-connected-to-office-365) and [Remove users](https://docs.microsoft.com/yammer/manage-yammer-users/add-block-or-remove-users#remove-users).</span></span>

<span data-ttu-id="2f5f2-114">Настроївши Yammer за допомогою цих дій, ви також будете готові налаштувати мережу Yammer для власного режиму для Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="2f5f2-114">By configuring Yammer using these steps, you'll also be ready to configure your Yammer network for Native Mode for Microsoft 365.</span></span> <span data-ttu-id="2f5f2-115">Для отримання додаткових відомостей див. [Настроювання мережі Yammer для власного режиму для Microsoft 365](https://docs.microsoft.com/yammer/configure-your-yammer-network/native-mode).</span><span class="sxs-lookup"><span data-stu-id="2f5f2-115">For more info, see [Configure your Yammer network for Native Mode for Microsoft 365](https://docs.microsoft.com/yammer/configure-your-yammer-network/native-mode).</span></span>
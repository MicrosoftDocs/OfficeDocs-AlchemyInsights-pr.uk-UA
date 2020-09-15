---
title: Блокування в Блокоїавтентифікації
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
- "3154"
- "9001194"
ms.openlocfilehash: baf3ee808cce1e4da362dd0841c0138d7d9268d1
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 09/14/2020
ms.locfileid: "47685619"
---
# <a name="blocking-legacy-authentication"></a><span data-ttu-id="b99a8-102">Блокування успадкованої автентифікації</span><span class="sxs-lookup"><span data-stu-id="b99a8-102">Blocking legacy authentication</span></span>

<span data-ttu-id="b99a8-103">Успадковане автентифікація – це термін, який посилається на запит автентифікації, досягнутий:</span><span class="sxs-lookup"><span data-stu-id="b99a8-103">Legacy authentication is a term that refers to an authentication request made by:</span></span>

- <span data-ttu-id="b99a8-104">Попередні клієнти Office, які не використовують сучасну автентифікацію (наприклад, клієнт Office 2010).</span><span class="sxs-lookup"><span data-stu-id="b99a8-104">Older Office clients that do not use modern authentication (for example, Office 2010 client).</span></span>

- <span data-ttu-id="b99a8-105">Будь-який клієнт, який використовує застарілі поштові протоколи, як-от IMAP/SMTP/POP3.</span><span class="sxs-lookup"><span data-stu-id="b99a8-105">Any client that uses legacy mail protocols such as IMAP/SMTP/POP3.</span></span>

<span data-ttu-id="b99a8-106">Докладні відомості про блокування успадкованої автентифікації та ввімкнення сучасної автентифікації наведено в статті [блокування успадкованої автентифікації](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-conditional-access-block-legacy-authentication).</span><span class="sxs-lookup"><span data-stu-id="b99a8-106">For more information on blocking legacy authentication and enabling modern authentication, refer to [Blocking legacy authentication](https://docs.microsoft.com/azure/active-directory/conditional-access/concept-conditional-access-block-legacy-authentication).</span></span>

<span data-ttu-id="b99a8-107">Стандартні параметри безпеки в "Блакитний" ("Лазурний") полегшують безпеку та захист вашої організації.</span><span class="sxs-lookup"><span data-stu-id="b99a8-107">Security defaults in Azure Active Directory (Azure AD) make it easier to be secure and help protect your organization.</span></span> <span data-ttu-id="b99a8-108">За замовчуванням в безпеці містяться налаштовані параметри безпеки для поширених атак.</span><span class="sxs-lookup"><span data-stu-id="b99a8-108">Security defaults contain preconfigured security settings for common attacks.</span></span>
<span data-ttu-id="b99a8-109">Додаткові відомості про стандартні параметри безпеки наведено в статті [що таке за замовчуванням безпеки?](https://docs.microsoft.com/azure/active-directory/fundamentals/concept-fundamentals-security-defaults).</span><span class="sxs-lookup"><span data-stu-id="b99a8-109">For more information about security defaults, refer to [What are security defaults?](https://docs.microsoft.com/azure/active-directory/fundamentals/concept-fundamentals-security-defaults).</span></span> 

<span data-ttu-id="b99a8-110">**Примітка**. Якщо ваш клієнт був створений або після 22 жовтня 2019, можливо, ви відчуваєте нову поведінку безпечного за замовчуванням, і вже ввімкнуто використання стандартних параметрів безпеки в клієнті.</span><span class="sxs-lookup"><span data-stu-id="b99a8-110">**Note**:  If your tenant was created on or after October 22nd, 2019, it's possible you are experiencing the new secure-by-default behavior and already have security defaults enabled in your tenant.</span></span>  <span data-ttu-id="b99a8-111">Щоб захистити всіх наших користувачів, за замовчуванням для всіх нових орендарів створюється відповідний рівень безпеки.</span><span class="sxs-lookup"><span data-stu-id="b99a8-111">In an effort to protect all of our users, security defaults is being rolled out to all new tenants created.</span></span>

---
title: Робочий день для підготовки користувачів AD переходить до карантинної держави
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/19/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "8471"
- "9004687"
ms.openlocfilehash: 0fc519c8170de498c9bcb1fc41a76116bda48b1f
ms.sourcegitcommit: 379e132c4d21ecf703d5506484ec96a767fdda39
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/04/2021
ms.locfileid: "50482908"
---
# <a name="workday-to-ad-user-provisioning-goes-into-quarantine-state"></a><span data-ttu-id="0ecdd-102">Робочий день для підготовки користувачів AD переходить до карантинної держави</span><span class="sxs-lookup"><span data-stu-id="0ecdd-102">Workday to AD User Provisioning goes into quarantine state</span></span>

<span data-ttu-id="0ecdd-103">**Робочий день для підготовки користувачів AD переходить у карантин стан і немає користувачів, створених у службі AD**</span><span class="sxs-lookup"><span data-stu-id="0ecdd-103">**Workday to AD User Provisioning goes into quarantine state and no users are created in AD**</span></span>

<span data-ttu-id="0ecdd-104">Робочий день для завдання підготовки користувачів у службі AD увійшов до карантину держави, а в журналах аудиту відображається подія про помилки експорту з помилкою повідомлення про помилку **: OperationsError-SvcErr: сталася помилка операції. Не настроєно чудове посилання для служби каталогів. Тому служба каталогів не може видати переходи на об'єкти поза цим лісом**.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-104">The Workday to AD User Provisioning job has gone into quarantine state and the audit logs show export failure events with the error message **Error: OperationsError-SvcErr: An operation error occurred. No superior reference has been configured for the directory service. The directory service is therefore unable to issue referrals to objects outside this forest**.</span></span> <span data-ttu-id="0ecdd-105">Ця помилка зазвичай з'являється, якщо контейнер Active Directory не задано належним чином або якщо є проблеми з зіставленням виразів, які використовуються для функції **Paredimisationname**.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-105">This error usually shows up if the Active Directory Container OU is not set correctly or if there are issues with the Expression Mapping used for **parentDistinguishedName**.</span></span>

<span data-ttu-id="0ecdd-106">Установіть прапорець у полі за замовчуванням для **нових користувачів** , щоб створити друкарські помилки.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-106">Check the Default OU for **New Users** parameter for typos.</span></span> <span data-ttu-id="0ecdd-107">Переконайтеся, що в оголошенні вже є вказана у вашій мережі.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-107">Ensure that the specified OU already exists in your AD.</span></span> <span data-ttu-id="0ecdd-108">Якщо ви використовуєте **ім'я** paralрозрізнення у зіставленнях атрибутів, переконайтеся, що воно завжди обчислюється відомим контейнером в домені AD.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-108">If you are using **parentDistinguishedName** in the attribute mapping, ensure that it always evaluates to a known container within the AD domain.</span></span> <span data-ttu-id="0ecdd-109">Перевірте подію експорту в журналах аудиту, щоб переглянути згенерований значення.</span><span class="sxs-lookup"><span data-stu-id="0ecdd-109">Check the Export event in the audit logs to see the generated value.</span></span>

<span data-ttu-id="0ecdd-110">Докладні відомості про настроювання робочого дня для автоматизованого підготовки наведено в статті [навчальний посібник: Настроювання робочого дня для автоматичного підготовки користувача](https://docs.microsoft.com/azure/active-directory/saas-apps/workday-inbound-tutorial).</span><span class="sxs-lookup"><span data-stu-id="0ecdd-110">For more details on configuring workday for automated provisioning, see [Tutorial: Configure Workday for automatic user provisioning](https://docs.microsoft.com/azure/active-directory/saas-apps/workday-inbound-tutorial).</span></span>


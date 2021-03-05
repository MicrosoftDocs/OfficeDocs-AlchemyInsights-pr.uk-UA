---
title: Проблема з атрибутом "атрибут" і "Фільтр"
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
- "8470"
- "9004687"
ms.openlocfilehash: 78df24c0d8a670d678e26879cf81476f1ae9b92d
ms.sourcegitcommit: 379e132c4d21ecf703d5506484ec96a767fdda39
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/04/2021
ms.locfileid: "50482926"
---
# <a name="problem-with-attribute-and-scoping-filter"></a><span data-ttu-id="a7fcc-102">Проблема з атрибутом "атрибут" і "Фільтр"</span><span class="sxs-lookup"><span data-stu-id="a7fcc-102">Problem with attribute and scoping filter</span></span>

<span data-ttu-id="a7fcc-103">**Проблема з конфліктуючими значеннями UPN**</span><span class="sxs-lookup"><span data-stu-id="a7fcc-103">**Issue with conflicting UPN values**</span></span>

<span data-ttu-id="a7fcc-104">Робочий день для підготовки користувачів до робочого дня для підготовки користувачів AD відображає повідомлення про помилку **HybridSynchronizationActiveDirectoryUserPrincipalNameNotUnique**.</span><span class="sxs-lookup"><span data-stu-id="a7fcc-104">The Workday to AD User Provisioning Workday to AD User Provisioning shows error message **HybridSynchronizationActiveDirectoryUserPrincipalNameNotUnique**.</span></span> <span data-ttu-id="a7fcc-105">Не вдалося виконати операцію, оскільки значення, яке надається для додавання або змінення, не є унікальним у всьому лісі.</span><span class="sxs-lookup"><span data-stu-id="a7fcc-105">The operation failed because UPN value provided for addition/modification is not unique forest-wide.</span></span> <span data-ttu-id="a7fcc-106">Відомості про помилку: **CONSTRAINT_ATT_TYPE-userPrincipalName**.</span><span class="sxs-lookup"><span data-stu-id="a7fcc-106">Error Details: **CONSTRAINT_ATT_TYPE - userPrincipalName**.</span></span>

<span data-ttu-id="a7fcc-107">Значення **userPrincipalName** , яке потрібно встановити в полі "робочий день", під час створення облікового ЗАПИСУ користувача AD вже існує в ЦІЛЬОВОМУ домені AD.</span><span class="sxs-lookup"><span data-stu-id="a7fcc-107">The **userPrincipalName** value that Workday connector is trying to set when creating the AD user account already exists in the target AD domain.</span></span> <span data-ttu-id="a7fcc-108">Це означає, що будь-який користувач, який уже існує, і відповідний ІДЕНТИФІКАТОР не вдалося перевірити для користувача або (2) правило створення помилки, створене конфліктуючим значенням.</span><span class="sxs-lookup"><span data-stu-id="a7fcc-108">This implies that either (1) the user already exists and the matching ID check failed for the user or (2) the UPN generation rule generated a conflicting value.</span></span>

<span data-ttu-id="a7fcc-109">Нижче наведено інструкції з вирішення цієї проблеми.</span><span class="sxs-lookup"><span data-stu-id="a7fcc-109">Here are the suggested resolution steps:</span></span>

<span data-ttu-id="a7fcc-110">Якщо користувач уже існує, а відповідний ІДЕНТИФІКАТОР не виконав посилання на обліковий запис "робочий день" до облікового запису Active Directory, перевірте, чи відповідає атрибут ID (зазвичай **employeeID**) в обох будні та в оголошенні.</span><span class="sxs-lookup"><span data-stu-id="a7fcc-110">If the user already exists and the matching ID check failed to link the Workday account to Active Directory account, then check if the matching ID attribute (typically **employeeID**) in both Workday and AD have an exact match.</span></span> <span data-ttu-id="a7fcc-111">Якщо у вас немає відповідності, це проблема з даними, яку потрібно виправити.</span><span class="sxs-lookup"><span data-stu-id="a7fcc-111">If they don't have a match, it is a data issue that needs to be fixed.</span></span> <span data-ttu-id="a7fcc-112">Наприклад, якщо EmployeeID у будні дні – 001052, а в ОГОЛОШЕННІ – 1052, то обробник підготовки не вдасться пов'язати два облікові записи та спробує створити користувача, який уже існує.</span><span class="sxs-lookup"><span data-stu-id="a7fcc-112">For example, if the EmployeeID in Workday is 001052 and in AD it is 1052, then the provisioning engine will fail to link the two accounts and will try to create a user that already exists.</span></span> <span data-ttu-id="a7fcc-113">Рішення в цьому випадку полягає в тому, щоб змінити значення **EmployeeID** у AD, щоб включити початкові нулі, щоб зробити його 001052.</span><span class="sxs-lookup"><span data-stu-id="a7fcc-113">The solution in this case is to change the **EmployeeID** value in AD to include the leading zeros to make it 001052.</span></span>
<span data-ttu-id="a7fcc-114">Якщо вираз створення UPN не створює унікальне значення, спробуйте використати функцію "недублювання" **SelectUniqueValue** , щоб створити унікальне значення щоразу.</span><span class="sxs-lookup"><span data-stu-id="a7fcc-114">If the UPN-generating expression is not generating a unique value, consider using the de-duplication function **SelectUniqueValue** to generate a unique value each time.</span></span>

<span data-ttu-id="a7fcc-115">**Робочий день для підготовки користувачів AD не встановлює значення атрибута Manager для облікового запису користувача AD**</span><span class="sxs-lookup"><span data-stu-id="a7fcc-115">**Workday to AD User Provisioning does not set manager attribute value for AD user account**</span></span>

<span data-ttu-id="a7fcc-116">Робочий день для завдання підготовки користувача оголошення не встановлює значення атрибута **диспетчера** для облікових записів користувачів AD.</span><span class="sxs-lookup"><span data-stu-id="a7fcc-116">The Workday to AD User Provisioning job is not setting the **manager** attribute value for AD user accounts.</span></span> <span data-ttu-id="a7fcc-117">Під час цього поведінки виникає два можливі сценарії:</span><span class="sxs-lookup"><span data-stu-id="a7fcc-117">There are two possible scenarios when this behavior is seen:</span></span>

1. <span data-ttu-id="a7fcc-118">Керівник в будні дні не може бути вирішене відповідним обліковим записом користувача AD, оскільки Диспетчер не перебуває в області.</span><span class="sxs-lookup"><span data-stu-id="a7fcc-118">The manager in Workday cannot be resolved to a corresponding AD User account because the manager is not in scope.</span></span>
2. <span data-ttu-id="a7fcc-119">У випадку з **кількома ДОМЕНАМИ рекламних доменів** керівник в будні дні не відображається в тому самому домені, що й користувач.</span><span class="sxs-lookup"><span data-stu-id="a7fcc-119">In a **multiple AD domains** scenario, the manager in Workday is not present in the same domain as the user.</span></span>

<span data-ttu-id="a7fcc-120">Щоб вирішити цю проблему, виконайте наведені нижче дії.</span><span class="sxs-lookup"><span data-stu-id="a7fcc-120">Try these steps to resolve the issue:</span></span>

1. <span data-ttu-id="a7fcc-121">Якщо ви визначили фільтри для фільтрів, спочатку перевірте, чи відповідає Диспетчер, і що вона задовольняє речення scooping.</span><span class="sxs-lookup"><span data-stu-id="a7fcc-121">If you have defined scoping filters, first check if the manager is in scope and that it satisfies the scoping clause.</span></span> <span data-ttu-id="a7fcc-122">Якщо керівник не задовольняє фільтр scooping, змініть фільтр таким чином, що керівник також перебуває в межах операції підготовки.</span><span class="sxs-lookup"><span data-stu-id="a7fcc-122">If the manager does not satisfy the scoping filter, change the filter so that the manager is also in scope of the provisioning operation.</span></span>
2. <span data-ttu-id="a7fcc-123">Якщо у вас кілька доменів із ОГОЛОШЕННЯМИ, то сполучна лінія має відомі обмеження нездатністю для вирішення посилань на керування доменами.</span><span class="sxs-lookup"><span data-stu-id="a7fcc-123">If you have multiple AD domains, then the connector has a known limitation of inability to resolve cross-domain manager references.</span></span>

<span data-ttu-id="a7fcc-124">Докладні відомості про настроювання робочого дня для автоматизованого підготовки наведено в статті [навчальний посібник: Настроювання робочого дня для автоматичного підготовки користувача](https://docs.microsoft.com/azure/active-directory/saas-apps/workday-inbound-tutorial).</span><span class="sxs-lookup"><span data-stu-id="a7fcc-124">For more details on configuring workday for automated provisioning, see [Tutorial: Configure Workday for automatic user provisioning](https://docs.microsoft.com/azure/active-directory/saas-apps/workday-inbound-tutorial).</span></span>














---
title: DLP не працює належним чином
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1241"
- "3200001"
ms.assetid: f6fcf5ad-55a1-4f25-af27-1f7c1ce06409
ms.openlocfilehash: 0f07e64c95675a4f6a0aeb6df110fe4e6a21d72f
ms.sourcegitcommit: 0eb4f9bde53395b5fd4b5cd4ffc56ca96db91298
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/10/2021
ms.locfileid: "50707831"
---
# <a name="dlp-not-working-as-expected"></a><span data-ttu-id="96bca-102">DLP не працює належним чином</span><span class="sxs-lookup"><span data-stu-id="96bca-102">DLP not working as expected</span></span>

<span data-ttu-id="96bca-103">**Важливо**: у ці безпрецедентні часи ми докладаємо всіх зусиль до того, щоб служби SharePoint Online і OneDrive були завжди доступні. Докладні відомості надано у статті [Тимчасові коригування функцій SharePoint Online](https://aka.ms/ODSPAdjustments).</span><span class="sxs-lookup"><span data-stu-id="96bca-103">**Important**: During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available – Please visit [SharePoint Online Temporary Feature Adjustments](https://aka.ms/ODSPAdjustments) for more information.</span></span>

 <span data-ttu-id="96bca-104">**Налаштування DLP**</span><span class="sxs-lookup"><span data-stu-id="96bca-104">**Setting up DLP**</span></span>

<span data-ttu-id="96bca-105">У вас виникли проблеми з **запобіганням втрати даних (DLP)** у службі Office 365, які не працюють належним чином?</span><span class="sxs-lookup"><span data-stu-id="96bca-105">Are you having problems with **Data Loss Prevention (DLP)** in Office 365 not working as expected?</span></span> <span data-ttu-id="96bca-106">Якщо так, переконайтеся, що **політику DLP** настроєно правильно, і дані, що містяться в **політиці DLP** , шукають, коли її буде оцінено.</span><span class="sxs-lookup"><span data-stu-id="96bca-106">If so, make sure that your **DLP policy** is set up correctly, and that your data contains what the **DLP policy** is looking for when it is being evaluated.</span></span>
  
<span data-ttu-id="96bca-107">Політики DLP дають змогу виявляти та захищати конфіденційну інформацію в організації.</span><span class="sxs-lookup"><span data-stu-id="96bca-107">DLP policies allows you to identify and protect sensitive information in your organization.</span></span> <span data-ttu-id="96bca-108">Щоб налаштувати політики DLP, скористайтеся інформацією [тут](https://docs.microsoft.com/microsoft-365/compliance/create-a-dlp-policy-from-a-template).</span><span class="sxs-lookup"><span data-stu-id="96bca-108">To setup DLP policies, use the information [here](https://docs.microsoft.com/microsoft-365/compliance/create-a-dlp-policy-from-a-template).</span></span>
  
 <span data-ttu-id="96bca-109">**Що таке політики DLP, які шукають**</span><span class="sxs-lookup"><span data-stu-id="96bca-109">**What DLP policies look for**</span></span>
  
<span data-ttu-id="96bca-110">Під час використання **вбудованих типів даних** у центрах безпеки та відповідності, політики DLP шукають певні структури та елементи під час виявлення цих чутливих типів.</span><span class="sxs-lookup"><span data-stu-id="96bca-110">When using the **built-in sensitive information types** in the Security and Compliance centers, DLP policies look for specific patterns and elements when detecting these sensitive types.</span></span>
  
- <span data-ttu-id="96bca-111">**Вбудовані типи конфіденційної інформації**</span><span class="sxs-lookup"><span data-stu-id="96bca-111">**Built-in Sensitive Information Types**</span></span>

    <span data-ttu-id="96bca-112">Щоб отримати відомості про вбудовані типи, а також про те, що таке політика DLP, під час виявлення чутливим типом, ознайомтеся з відомостями про [типи чутливих даних](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions).</span><span class="sxs-lookup"><span data-stu-id="96bca-112">For information on the built-in Sensitive types and what a DLP policy looks for when detecting the Sensitive type, see: [What the sensitive information types look for](https://docs.microsoft.com/microsoft-365/compliance/sensitive-information-type-entity-definitions).</span></span>

- <span data-ttu-id="96bca-113">**Спеціальні типи конфіденційної інформації**</span><span class="sxs-lookup"><span data-stu-id="96bca-113">**Custom Sensitive Information Types**</span></span>

    <span data-ttu-id="96bca-114">Якщо ви намагаєтеся створити спеціальні конфіденційні типи даних, скористайтеся наведенною нижче статтею, щоб отримати відомості про те, як створити настроюваний чутливий тип: [створити настроюваний тип конфіденційної інформації](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="96bca-114">If you are trying to create custom sensitive information types, use the following article for information on how to create a custom sensitive type: [Create a custom sensitive information type](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type).</span></span>

<span data-ttu-id="96bca-115">**Перевірка політики DLP**</span><span class="sxs-lookup"><span data-stu-id="96bca-115">**Test a DLP policy**</span></span>

<span data-ttu-id="96bca-116">Щоб перевірити дані з вбудованим або настроюваним типом конфіденційної інформації, скористайтеся параметром **тип тесту** в розділі **класифікації**  >  **конфіденційних відомостей про типи** даних.</span><span class="sxs-lookup"><span data-stu-id="96bca-116">To test your data with a built-in or custom sensitive information type, use the **Test type** option under **Classifications** > **Sensitive info types**.</span></span> <span data-ttu-id="96bca-117">Докладні відомості наведено в статті [перевірка користувацьких чутливих типів даних](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type#create-custom-sensitive-information-types-in-the-security--compliance-center).</span><span class="sxs-lookup"><span data-stu-id="96bca-117">For more information, see [Test custom sensitive information types](https://docs.microsoft.com/microsoft-365/compliance/create-a-custom-sensitive-information-type#create-custom-sensitive-information-types-in-the-security--compliance-center).</span></span>

 <span data-ttu-id="96bca-118">**Звіти**</span><span class="sxs-lookup"><span data-stu-id="96bca-118">**Reports**</span></span>
  
- <span data-ttu-id="96bca-119">Отримуйте чутливі дані про результати пошуку за допомогою [звітів DLP.](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies#dlp-reports)</span><span class="sxs-lookup"><span data-stu-id="96bca-119">Get sensitive data insights with [DLP Reports.](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies#dlp-reports)</span></span>

- <span data-ttu-id="96bca-120">Перегляньте докладні відомості про подію з [звітом про інцидент](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies#incident-reports).</span><span class="sxs-lookup"><span data-stu-id="96bca-120">See specific details of the event with an [Incident Report](https://docs.microsoft.com/microsoft-365/compliance/data-loss-prevention-policies#incident-reports).</span></span>

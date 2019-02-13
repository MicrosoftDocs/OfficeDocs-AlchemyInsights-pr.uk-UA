---
title: Відсутні робочого процесу не вдалося активувати
ms.author: kirks
author: Techwriter40
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: e46ae8c5-3d81-457e-8c77-f7c1cbe267c4
ms.openlocfilehash: ce088227a3206fa05b99331fdb022fbe4886203f
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 02/12/2019
ms.locfileid: "29917589"
---
# <a name="missing-workflow-failed-to-activate"></a><span data-ttu-id="233f7-102">Відсутні робочого процесу не вдалося активувати</span><span class="sxs-lookup"><span data-stu-id="233f7-102">Missing Workflow Failed to Activate</span></span>

<span data-ttu-id="233f7-103">В колекції сайтів Microsoft SharePoint глобально для повторного використання робочого процесу (наприклад, "затвердження - SharePoint 2010") не можна додати до списку або бібліотеки.</span><span class="sxs-lookup"><span data-stu-id="233f7-103">In a Microsoft SharePoint site collection, you can't add a globally reusable workflow (such as "Approval - SharePoint 2010") to a list or library.</span></span>
  
<span data-ttu-id="233f7-104">Щоб вирішити цю проблему, виконайте такі дії:</span><span class="sxs-lookup"><span data-stu-id="233f7-104">To resolve this issue, follow these steps:</span></span> 
  
1. <span data-ttu-id="233f7-105">Відкрити кореневий сайт колекції сайтів SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="233f7-105">Open the root website of the site collection in SharePoint Designer 2013.</span></span>
  
2. <span data-ttu-id="233f7-106">Під **Сайт об'єктів**виберіть пункт **робочі процеси**.</span><span class="sxs-lookup"><span data-stu-id="233f7-106">Under **Site Objects**, select **Workflows**.</span></span> 
  
3. <span data-ttu-id="233f7-107">У розділі **нової** стрічки **робочі процеси** виберіть **Багаторазового використання робочого процесу**.</span><span class="sxs-lookup"><span data-stu-id="233f7-107">In the **New** section of the **Workflows** ribbon, select **Reusable Workflow**.</span></span> 
  
4. <span data-ttu-id="233f7-p101">У формі, **Створення багаторазового використання робочого процесу** , введіть ім'я \* \* *Repair2010* \* \*. **Тип платформи**клацніть **Робочого циклу SharePoint 2010**і натисніть кнопку **ОК**.</span><span class="sxs-lookup"><span data-stu-id="233f7-p101">On the **Create Reusable Workflow** form, enter the name \*\* *Repair2010* \*\*. For **Platform Type**, click **SharePoint 2010 Workflow**, and then click **OK**.</span></span> 
  
1. <span data-ttu-id="233f7-110">У **зберегти** розділі стрічки **робочого процесу** виберіть пункт **опублікувати**.</span><span class="sxs-lookup"><span data-stu-id="233f7-110">In the **Save** section of the **Workflow** ribbon, select **Publish**.</span></span> 
  
2. <span data-ttu-id="233f7-p102">У розділі **керування** стрічки **робочий процес** виберіть **Опублікувати глобально**. У діалоговому вікні підтвердження, що з'явиться виберіть **ОК**.</span><span class="sxs-lookup"><span data-stu-id="233f7-p102">In the **Manage** section of the **Workflow** ribbon, select **Publish Globally**. In the confirmation dialog box that appears, select **OK**.</span></span> 
  
3. <span data-ttu-id="233f7-p103">У веб-переглядачі, знайдіть кореневий сайт колекції сайтів та отримувати доступ до **Параметрів сайту** \> **Функцій колекції сайтів**. Потім Увімкнути або вимкнути функцію **робочі процеси** :</span><span class="sxs-lookup"><span data-stu-id="233f7-p103">In a web browser, locate the root website of the site collection, and then access **Site Settings** \> **Site Collection Features**. Then, toggle the **Workflows** feature:</span></span> 
  
<span data-ttu-id="233f7-115">· Якщо функція *активоване* , натисніть кнопку **Вимкнути** та натисніть кнопку **активувати**.</span><span class="sxs-lookup"><span data-stu-id="233f7-115">· If the feature is  *Activated*  , click **Deactivate,** and then click **Activate**.</span></span> 
  
<span data-ttu-id="233f7-116">· Якщо функція *Deactivated* , натисніть кнопку **активувати**.</span><span class="sxs-lookup"><span data-stu-id="233f7-116">· If the feature is  *Deactivated*  , click **Activate**.</span></span> 
  
<span data-ttu-id="233f7-117">Для отримання додаткових відомостей зверніться до [статті](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="233f7-117">For more information please refer to the following [article](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span></span>
  


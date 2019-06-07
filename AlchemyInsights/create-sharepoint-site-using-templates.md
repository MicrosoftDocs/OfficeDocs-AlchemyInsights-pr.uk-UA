---
title: Створити сайт у SharePoint Online
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 84f2b70e-2b23-4039-8305-85783798feed
ms.openlocfilehash: a964751e52972875a8794ce311546f5816a36ca6
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 06/07/2019
ms.locfileid: "34753731"
---
# <a name="create-sharepoint-sites-using-templates"></a><span data-ttu-id="b1efd-102">Створення сайтів SharePoint за допомогою шаблонів</span><span class="sxs-lookup"><span data-stu-id="b1efd-102">Create SharePoint sites using templates</span></span>

<span data-ttu-id="b1efd-103">Шаблони сайтів SharePoint є готові визначень призначені навколо потреби конкретного бізнесу.</span><span class="sxs-lookup"><span data-stu-id="b1efd-103">SharePoint site templates are prebuilt definitions designed around a particular business need.</span></span> <span data-ttu-id="b1efd-104">Докладніше перегляньте статтю [використання шаблонів для створення різних видів сайтів SharePoint](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span><span class="sxs-lookup"><span data-stu-id="b1efd-104">For more information, see [Using templates to create different kinds of SharePoint sites](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span></span>

<span data-ttu-id="b1efd-105">Нижче наведено деякі поширені питання/рішення щодо збереження через сайт або список як шаблон у Sharepoint Online.</span><span class="sxs-lookup"><span data-stu-id="b1efd-105">Here are some common issues/solutions regarding Saving a Site or List as a template in Sharepoint Online.</span></span> 

<span data-ttu-id="b1efd-106">**Зберегти сайт/список шаблон кнопка не буде доступна або відсутні**</span><span class="sxs-lookup"><span data-stu-id="b1efd-106">**Save site/list template button is not available or missing**</span></span>

<span data-ttu-id="b1efd-107">Адміністратори повинні дозволити користувацький скрипт для ввімкнення функції шаблон.</span><span class="sxs-lookup"><span data-stu-id="b1efd-107">Administrators will need to Allow Custom Script to enable the template features.</span></span> <span data-ttu-id="b1efd-108">Докладно процедуру описано приклади і міркування див</span><span class="sxs-lookup"><span data-stu-id="b1efd-108">For detailed steps, examples and considerations see</span></span> 

- [<span data-ttu-id="b1efd-109">Дозволити або заборонити власний сценарій</span><span class="sxs-lookup"><span data-stu-id="b1efd-109">Allow or prevent custom script</span></span>](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)

- <span data-ttu-id="b1efd-110">Сайт зберегти як шаблон команда не підтримується і може викликати проблеми на сайтах, які використовують Видавничий інфраструктури SharePoint Server.</span><span class="sxs-lookup"><span data-stu-id="b1efd-110">The Save site as template command is not supported and can cause problems on sites that use the SharePoint Server Publishing Infrastructure.</span></span>

<span data-ttu-id="b1efd-111">Шаблон сайту неможливо створити або працює неправильно.</span><span class="sxs-lookup"><span data-stu-id="b1efd-111">The site template cannot be created or does not work correctly.</span></span>

<span data-ttu-id="b1efd-112">Шаблон може бути відсутня [функція](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) і не буде активувати.</span><span class="sxs-lookup"><span data-stu-id="b1efd-112">The template may be missing a [feature](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) and won't activate.</span></span> <span data-ttu-id="b1efd-113">Якщо функція недоступна для активації в поточній колекції сайтів, це неможливо використовувати шаблон сайту для створення сайту.</span><span class="sxs-lookup"><span data-stu-id="b1efd-113">If the feature is not available to activate in the current site collection, you cannot use the site template to create a site.</span></span>

- <span data-ttu-id="b1efd-114">Перевірте, якщо будь-які списки або бібліотеки перевищує [Ліміт граничне значення подання списку](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) з 5000 пунктів, як це може блокувати створення шаблон сайту.</span><span class="sxs-lookup"><span data-stu-id="b1efd-114">Check to see if any lists or libraries exceed the [List View Limit Threshold](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) of 5000 items as this can block creation of a site template.</span></span>

- <span data-ttu-id="b1efd-115">Можливо, сайт використовує забагато ресурсів і тому шаблон сайту перевищує обмеження в 50 МБ.</span><span class="sxs-lookup"><span data-stu-id="b1efd-115">The site may be using too many resources and therefore the site template exceeds the 50 MB limit.</span></span>


- <span data-ttu-id="b1efd-116">Є проблеми відображення даних зі списку, який використовує стовпець підстановки.</span><span class="sxs-lookup"><span data-stu-id="b1efd-116">There are problems displaying data from a list that uses a lookup column.</span></span> <span data-ttu-id="b1efd-117">Докладніше перегляньте [створеного шаблону списку не відображаються дані зі списку правильний підстановки в SharePoint Online](https://support.office.com/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a).</span><span class="sxs-lookup"><span data-stu-id="b1efd-117">For more information, see [Template-generated list doesn't display data from the correct lookup list in SharePoint Online](https://support.office.com/article/template-generated-list-doesn-t-display-correct-data-for-a-column-in-sharepoint-online-20430b62-e40c-4f6f-8889-aa24e80d605a).</span></span>

<span data-ttu-id="b1efd-118">Для більш докладної інформації про загальні проблеми і рішення будь ласка, перевірте [створення і використання шаблонів сайтів](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span><span class="sxs-lookup"><span data-stu-id="b1efd-118">For more detailed information on common problems and solutions, please check [Create and use site templates](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span></span>




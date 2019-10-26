---
title: Інсталяція Office на сервері терміналів-ліцензовано
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "917"
- "2000020"
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 51d1a66fdf9774bbe58bfdbe89317bc93834be09
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 10/25/2019
ms.locfileid: "37205430"
---
# <a name="installing-office-on-a-terminal-server"></a><span data-ttu-id="6eb51-102">Інсталяція Office на сервері терміналів</span><span class="sxs-lookup"><span data-stu-id="6eb51-102">Installing Office on a Terminal Server</span></span>

<span data-ttu-id="6eb51-103">Для розгортання Office 365 ProPlus на сервері Windows за допомогою служб віддалених робочих столів (RDS), раніше іменований служби терміналів:</span><span class="sxs-lookup"><span data-stu-id="6eb51-103">For deploying Office 365 ProPlus on a Windows Server using Remote Desktop Services (RDS), formerly named Terminal Services:</span></span>
  
- <span data-ttu-id="6eb51-104">Потрібно мати Office 365 план, який включає в себе Office 365 ProPlus, наприклад Office 365 Enterprise E3 або Enterprise E5.</span><span class="sxs-lookup"><span data-stu-id="6eb51-104">You must have an Office 365 plan that includes Office 365 ProPlus, such as Office 365 Enterprise E3 or Enterprise E5.</span></span> <span data-ttu-id="6eb51-105">Офіс 365 бізнес і офіс 365 бізнес преміум плани не включають в себе офіс 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="6eb51-105">The Office 365 Business and Office 365 Business Premium plans do not include Office 365 ProPlus.</span></span>

- <span data-ttu-id="6eb51-106">Потрібно ввімкнути [активацію спільної комп'ютера](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="6eb51-106">You need to enable [shared computer activation](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span></span>

<span data-ttu-id="6eb51-107">Якщо потрібно інсталювати Office 365 ProPlus на RDS з центру адміністрування Microsoft 365, ***який використовує параметри інсталяції за промовчанням***, виконайте такі дії.</span><span class="sxs-lookup"><span data-stu-id="6eb51-107">If you want to install Office 365 ProPlus on RDS from the Microsoft 365 admin center, ***which uses default installation settings***, use the following steps.</span></span>

> [!TIP]
> <span data-ttu-id="6eb51-108">Ви також можете завантажити та запустити [помічник з підтримки Microsoft і відновлення](https://aka.ms/SaRA_OfficeSCA_M365Portal) , щоб інсталювати Office 365 proplus у режим активації на спільному комп'ютері.</span><span class="sxs-lookup"><span data-stu-id="6eb51-108">You can also download and run the [Microsoft Support and Recovery Assistant](https://aka.ms/SaRA_OfficeSCA_M365Portal) to install Office 365 ProPlus in shared computer activation mode.</span></span>
  
1. <span data-ttu-id="6eb51-109">Перевірте, який план Office 365 у вас є.</span><span class="sxs-lookup"><span data-stu-id="6eb51-109">Check what Office 365 plan you have.</span></span> [<span data-ttu-id="6eb51-110">Дізнайтеся, як</span><span class="sxs-lookup"><span data-stu-id="6eb51-110">Learn how</span></span>](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)

2. <span data-ttu-id="6eb51-111">У разі потреби переключіться на інший план Office 365.</span><span class="sxs-lookup"><span data-stu-id="6eb51-111">If necessary, switch to a different Office 365 plan.</span></span> [<span data-ttu-id="6eb51-112">Дізнайтеся, як</span><span class="sxs-lookup"><span data-stu-id="6eb51-112">Learn how</span></span>](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)

3. <span data-ttu-id="6eb51-113">Якщо Office вже інстальовано на сервері RDS, використовуючи будь-які інші плани Office 365, видаліть його.</span><span class="sxs-lookup"><span data-stu-id="6eb51-113">If Office is already installed on the RDS server using any other Office 365 plans, uninstall it.</span></span> <span data-ttu-id="6eb51-114">Наприклад, перейшовши на панель \> керування, видаліть програму.</span><span class="sxs-lookup"><span data-stu-id="6eb51-114">For example, by going to Control Panel \> Uninstall a program.</span></span> <span data-ttu-id="6eb51-115">Якщо ви працюєте з проблемами, видаліть за допомогою [служби підтримки Microsoft і помічника з відновлення](https://aka.ms/SARA-OfficeUninstall-Alchemy) .</span><span class="sxs-lookup"><span data-stu-id="6eb51-115">Uninstall using [Microsoft Support and Recovery Assistant](https://aka.ms/SARA-OfficeUninstall-Alchemy) if you're running into issues.</span></span>

4. <span data-ttu-id="6eb51-116">На сервері RDS ввійдіть до центру адміністрування Microsoft 365 за допомогою облікового запису адміністратора та [інсталюйте Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span><span class="sxs-lookup"><span data-stu-id="6eb51-116">On the RDS server, sign in to the Microsoft 365 admin center with your administrator account and [install Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span></span>

5. <span data-ttu-id="6eb51-117">Після інсталяції Office ***не відкривайте або не входити в*** будь-які застосунки Office.</span><span class="sxs-lookup"><span data-stu-id="6eb51-117">After Office is installed, ***don't open or sign in*** to any Office applications.</span></span>

6. <span data-ttu-id="6eb51-118">На сервері RDS Увімкніть спільна Активація комп'ютера за допомогою редагування реєстру, виконавши такі дії:</span><span class="sxs-lookup"><span data-stu-id="6eb51-118">On the RDS server, enable shared computer activation by editing the registry by following these steps:</span></span>

1. <span data-ttu-id="6eb51-119">Клацніть правою кнопкою миші кнопку Windows у нижньому лівому куті екрана та виберіть пункт Виконати.</span><span class="sxs-lookup"><span data-stu-id="6eb51-119">Right-click the Windows button in the lower left-hand corner of your screen and select Run.</span></span> <span data-ttu-id="6eb51-120">У полі "Відкрити" введіть **Regedit**і виберіть "OK".</span><span class="sxs-lookup"><span data-stu-id="6eb51-120">In the Open box, type **regedit**, and then select OK.</span></span>

2. <span data-ttu-id="6eb51-121">Виберіть так, коли буде запропоновано дозволити редактору реєстру вносити зміни до пристрою.</span><span class="sxs-lookup"><span data-stu-id="6eb51-121">Select Yes when prompted to allow Registry Editor to make changes to your device.</span></span>

3. <span data-ttu-id="6eb51-122">У редакторі реєстру, додайте значення рядка **Sharedcomputer ліцензування** з настройки 1, під HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span><span class="sxs-lookup"><span data-stu-id="6eb51-122">In the Registry Editor, add a string value of **SharedComputerLicensing** with a setting of 1 under HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span></span>

7. <span data-ttu-id="6eb51-123">На сервері RDS ***ввійдіть як кінцевий користувач*** і [Переконайтеся, що активація спільного комп'ютера увімкнуто для Office 365 proplus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span><span class="sxs-lookup"><span data-stu-id="6eb51-123">On the RDS server, ***sign in as an end user*** and [verify that shared computer activation is enabled for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span></span>

<span data-ttu-id="6eb51-124">Щоб отримати додаткові відомості про попередні вимоги, інструкції з настроювання та вказівки щодо настроюваних інсталяцій за допомогою засобу розгортання Office, див. [розгортання Office 365 ProPlus за допомогою служб віддалених робочих столів](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span><span class="sxs-lookup"><span data-stu-id="6eb51-124">For more details on prerequisites, setup instructions and guidance on customized installations by using the Office Deployment Tool, please see [Deploy Office 365 ProPlus by using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span></span>
  
<span data-ttu-id="6eb51-125">Щоб виправити помилки, пов'язані з активацією спільних комп'ютерів, перегляньте [Виправлення неполадок, пов'язаних із активацією спільних комп'ютерів для Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="6eb51-125">To fix errors related to shared computer activation, please see [Troubleshoot issues with shared computer activation for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span></span>
  
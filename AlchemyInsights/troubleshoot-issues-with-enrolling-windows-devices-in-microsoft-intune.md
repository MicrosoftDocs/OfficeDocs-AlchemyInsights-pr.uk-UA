---
title: Усунення несправностей із зарахування пристроїв Windows у корпорації Майкрософт Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 20e9bd42-2db0-4dd7-b480-966571494dd9
ms.openlocfilehash: aa2262ed487ae4160f13490e92163a145e657862
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/23/2019
ms.locfileid: "32390664"
---
# <a name="troubleshoot-issues-with-enrolling-windows-devices-in-microsoft-intune"></a><span data-ttu-id="7aea5-102">Усунення несправностей із зарахування пристроїв Windows у корпорації Майкрософт Intune</span><span class="sxs-lookup"><span data-stu-id="7aea5-102">Troubleshoot issues with enrolling Windows devices in Microsoft Intune</span></span>

<span data-ttu-id="7aea5-103">Огляд ресурсів, перераховані нижче, щоб вирішити проблему, ваш тепер.</span><span class="sxs-lookup"><span data-stu-id="7aea5-103">Review the resources listed below to resolve your issue now.</span></span> 
  
<span data-ttu-id="7aea5-104">Деякі поширені повідомлення про помилки та резолюції кроки:</span><span class="sxs-lookup"><span data-stu-id="7aea5-104">Some common error messages and resolution steps:</span></span>
  
 <span data-ttu-id="7aea5-105">**Не вдалося інсталювати програмне забезпечення, 0x80cf4017:** Ваш обліковий запис сертифіката закінчився.</span><span class="sxs-lookup"><span data-stu-id="7aea5-105">**The software cannot be installed, 0x80cf4017:** Your account certificate has expired.</span></span> <span data-ttu-id="7aea5-106">Повторно завантажити пакет програмного забезпечення ПК клієнта в консолі адміністратора Intune.</span><span class="sxs-lookup"><span data-stu-id="7aea5-106">Re-download the PC Client software package in the Intune Admin Console.</span></span> <span data-ttu-id="7aea5-107">Огляд цієї документації для отримання додаткової інформації.</span><span class="sxs-lookup"><span data-stu-id="7aea5-107">Review this documentation for more information.</span></span> 
  
 <span data-ttu-id="7aea5-108">**Код помилки 0x801c0003:** Помилка може виникнути у таких випадках:</span><span class="sxs-lookup"><span data-stu-id="7aea5-108">**Error code 0x801c0003:** The error can occur in the following scenarios:</span></span> 
  
1. <span data-ttu-id="7aea5-109">Користувач має додаткові пристрої вступив ніж пристрою обмеження.</span><span class="sxs-lookup"><span data-stu-id="7aea5-109">The user has more devices enrolled than the device limit.</span></span> <span data-ttu-id="7aea5-110">Перегляньте ці документи до [зняття пристрою](https://docs.microsoft.com/intune/devices-wipe) або [Змінити обмеження на пристрій](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span><span class="sxs-lookup"><span data-stu-id="7aea5-110">Review these documents to [remove a device](https://docs.microsoft.com/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>
    
2. <span data-ttu-id="7aea5-111">"Користувачі можуть приєднатися до пристроїв блакитні об'яви" встановлено значення "немає".</span><span class="sxs-lookup"><span data-stu-id="7aea5-111">"Users may join devices to Azure AD" is set to "none".</span></span> <span data-ttu-id="7aea5-112">Встановіть його на всіх, або виберіть користувачів.</span><span class="sxs-lookup"><span data-stu-id="7aea5-112">Set it to all or select users.</span></span> <span data-ttu-id="7aea5-113">Огляд [цієї документації](https://docs.microsoft.com/azure/active-directory/device-management-azure-portal#configure-device-settings) для отримання додаткової інформації.</span><span class="sxs-lookup"><span data-stu-id="7aea5-113">Review [this documentation](https://docs.microsoft.com/azure/active-directory/device-management-azure-portal#configure-device-settings) for more information.</span></span> 
    
3. <span data-ttu-id="7aea5-114">Пристрою вже зареєстровано іншим користувачем.</span><span class="sxs-lookup"><span data-stu-id="7aea5-114">The device is already enrolled by another user.</span></span> <span data-ttu-id="7aea5-115">Якщо це так, видалити пристрій з Azure Intune консоль або вручну unenroll пристрій, перш ніж повторити спробу.</span><span class="sxs-lookup"><span data-stu-id="7aea5-115">If that's the case, remove the device from the Azure Intune console or manually unenroll the device before trying again.</span></span>
    
4. <span data-ttu-id="7aea5-116">Становить 10 Windows Home.</span><span class="sxs-lookup"><span data-stu-id="7aea5-116">The device is Windows 10 Home.</span></span> <span data-ttu-id="7aea5-117">Тільки Windows 10 Pro, освіти та рішенню щодо підприємства можуть приєднатися до Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="7aea5-117">Only Windows 10 Pro, Education and Enterprise SKUs can join Azure Active Directory.</span></span>
    
<span data-ttu-id="7aea5-118">Додаткові ресурси, щоб допомогти вирішити вашу проблему:</span><span class="sxs-lookup"><span data-stu-id="7aea5-118">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="7aea5-119">Використовувати [Intune виправлення неполадок портал](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) діагностувати та усунути поширені зарахування невдач.</span><span class="sxs-lookup"><span data-stu-id="7aea5-119">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="7aea5-120">Огляд [цей документ](https://docs.microsoft.com/intune/help-desk-operators) для більш докладної інформації.</span><span class="sxs-lookup"><span data-stu-id="7aea5-120">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span> 
    
2. <span data-ttu-id="7aea5-121">Перегляньте ці документи список поширених помилок, які заважають заявки на участь та постанов до кожного: [усунення несправностей керівництво](https://support.microsoft.com/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) та [усунення несправностей doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span><span class="sxs-lookup"><span data-stu-id="7aea5-121">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) and [Troubleshooting doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span></span>
    
<span data-ttu-id="7aea5-122">[Дізнайтеся, як записатися пристроїв Windows у корпорації Майкрософт Intune](https://docs.microsoft.com/intune/windows-enroll).</span><span class="sxs-lookup"><span data-stu-id="7aea5-122">[Learn how to enroll Windows devices in Microsoft Intune](https://docs.microsoft.com/intune/windows-enroll).</span></span>
  


---
title: ADFS Федерація сертифікат закінчується
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/8/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 26a7eebb-1424-4ddc-a123-af1cc94bc40f
ms.openlocfilehash: c608489be8497233d9d4f87ec53649026b823250
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 01/24/2019
ms.locfileid: "29496000"
---
# <a name="adfs-federation-certificate-expiring"></a><span data-ttu-id="bbd8b-102">ADFS Федерація сертифікат закінчується</span><span class="sxs-lookup"><span data-stu-id="bbd8b-102">ADFS Federation Certificate Expiring</span></span>

<span data-ttu-id="bbd8b-103">Щоб вирішити цю проблему, виконайте такі дії:</span><span class="sxs-lookup"><span data-stu-id="bbd8b-103">To resolve this issue, follow these steps:</span></span>
  
1. <span data-ttu-id="bbd8b-p101">Встановити на Microsoft Azure Active Directory модуль для Windows PowerShell на комп'ютер (якщо модуль не встановлений). Для цього, перейти до [керування блакитні оголошення за допомогою Windows PowerShell](https://aka.ms/aadposh).</span><span class="sxs-lookup"><span data-stu-id="bbd8b-p101">Install the Microsoft Azure Active Directory Module for Windows PowerShell on the computer (if the module isn't already installed). To do this, go to [Manage Azure AD using Windows PowerShell](https://aka.ms/aadposh).</span></span>
    
2. <span data-ttu-id="bbd8b-106">Виконайте дії, описані в на "сценарій 1: AD FS маркер підписання сертифіката минув" розділ [«Виникла проблема доступу до сайту» помилка з AD FS коли федеративного користувач входить до Office 365, Azure або Intune](https://support.microsoft.com/en-us/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span><span class="sxs-lookup"><span data-stu-id="bbd8b-106">Follow the steps in the "Scenario 1: The AD FS token-signing certificate expired" section of ["There was a problem accessing the site" error from AD FS when a federated user signs in to Office 365, Azure, or Intune](https://support.microsoft.com/en-us/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span></span>
    
3. <span data-ttu-id="bbd8b-107">Виконайте [як оновити або відновити параметри інтегрований домен у службі Office 365, Azure або Intune](https://support.microsoft.com/en-us/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span><span class="sxs-lookup"><span data-stu-id="bbd8b-107">Follow the steps in [How to update or repair the settings of a federated domain in Office 365, Azure, or Intune](https://support.microsoft.com/en-us/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span></span>
    
    <span data-ttu-id="bbd8b-108">Щоб дізнатися більше про поновлення Федерації сертифікати, побачити [Renew Федерації сертифікати для Office 365 і Azure Active Directory](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span><span class="sxs-lookup"><span data-stu-id="bbd8b-108">To learn more about renewing Federation certificates, see [Renew federation certificates for Office 365 and Azure Active Directory](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span></span>
    

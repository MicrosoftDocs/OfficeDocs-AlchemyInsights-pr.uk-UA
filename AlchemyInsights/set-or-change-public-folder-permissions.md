---
title: Установлення або змінення дозволів для спільної папки
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cffdf9bf-34ce-40f6-a69e-d02f17d9caef
ms.openlocfilehash: e419c72a890e68fc7b6d40d2b64406e42f9b0769
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/15/2021
ms.locfileid: "51789228"
---
# <a name="permissions-and-public-folders"></a>Дозволи та спільні папки

Дозволи для спільних папок можна змінити в Outlook, Центрі адміністрування Exchange (EAC) або PowerShell:
  
- Указівки з outlook [див. тут.](https://support.office.com/article/Set-or-change-permissions-for-a-public-folder-b2e0440c-7873-48ec-9ff2-b1a20b723005.aspx)
    
- Указівки для EAC [див.](https://technet.microsoft.com/library/jj651147%28v=exchg.150%29.aspx.aspx#Anchor_1) в цій статті. 
    
- Інструкції з використання [командлета Powershell](https://technet.microsoft.com/library/bb124743%28v=exchg.160%29.aspx.aspx) див. в Add-PublicFolderClientPermission цій статті. Якщо вам знадобляться інструкції, щоб підключитися до Exchange PowerShell, клацніть [тут](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx.aspx).
    
Якщо **зовнішні користувачі не** можуть надсилати електронні листи до спільної поштової папки, можливо, для неї бракує дозволів, необхідних для доставки зовнішньої електронної пошти. Це можна виправити, дотримуючись [указівок](https://technet.microsoft.com/library/aa997560%28v=exchg.150%29.aspx.aspx#Anchor_1)outlook, наведених тут, або PowerShell [тут.](https://support.microsoft.com/help/2984402/-5.7.1-smtp-550-5.7.1-resolver.rst.authrequired-nondelivery-report-when-external-users-try-to-send-mail-to-mail-enabled-public-folders-in-office-365.aspx)
  


---
title: Відновлення видаленої спільної папки
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3488"
ms.openlocfilehash: d5480389c3bf50cee9fe30f7ec8d8ff28ef694ca
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/15/2021
ms.locfileid: "51809460"
---
# <a name="restore-a-deleted-public-folder"></a>Відновлення видаленої спільної папки

**Щоб відновити видалені елементи зі спільної папки:**

- Див. [3. В Outlook 2016](https://aka.ms/pfrec)не можна відновити видалені елементи зі спільної папки, яка не надається електронною поштою.
 
**Щоб відновити видалену спільну папку (будь-якого типу):** 

- Виконайте таку команду EXO PowerShell:

    Синтаксис:

     `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse  | ?{$_.Name -eq "\<name_of_deleted_public_Folder"};Set-PublicFolder $pf.identity -Path \<path where the folder will be restored>`

    Приклад. Наведена нижче команда відновить вкладену доріжку1 і розмістить її в розділі \Parent1:

    `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ?{$_.Name -eq "Subfolder1"};Set-PublicFolder $pf.identity -Path \Parent1`

Докладні [відомості див. в папці](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder) Відновлення видаленої спільної папки.

---
title: Увімкнення Office 365 ЛОС для SharePoint, OneDrive та Microsoft Teams
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: dd367176f8d6f38f1f94ae6627229234f15c81ff
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 05/19/2021
ms.locfileid: "52543949"
---
# <a name="enable-microsoft-defender-for-office-365-for-sharepoint-online-onedrive-and-microsoft-teams"></a>Увімкнення Microsoft Defender для Office 365 для SharePoint Online, OneDrive і Microsoft Teams

1. Перейдіть до входу https://protection.office.com та ввійдіть.
2. Виберіть **Політика керування**  >    >  **загрозами Сейф вкладеннях.**
3. Установіть **прапорець Увімкнути Захисник для Office 365 для SharePoint, OneDrive і Microsoft Teams**, а потім натисніть кнопку **Зберегти**.
4. (Рекомендовано) Якщо ви глобальний адміністратор або адміністратор служби SharePoint Online, запустіть командлет [Set-SPOTenant](/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) із для параметра **DisallowInfectedFileDownload** значення *TRUE.*
5. (Рекомендовано) [Настроювання оповіщень](/microsoft-365/security/office-365-security/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) про виявлені файли.

> [!NOTE]
> Microsoft Defender для Office 365 не скануватиме кожен окремий файл у SharePoint Online, OneDrive або Microsoft Teams. Файли скануються асинхронно в процесі, який використовує події спільного доступу та гостьових дій, а також інтелектуальні евристичні сигнали та сигнали загроз для виявлення зловмисних файлів. Докладні [відомості див. в статті Office 365 Захисник Microsoft SharePoint, OneDrive і Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams).
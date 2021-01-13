---
title: Засіб діагностики служби для віртуального настільного комп'ютера Windows
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 12/14/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003893"
- "6947"
ms.openlocfilehash: c2e6f7fbcddc6721425840e87202a165cdb22664
ms.sourcegitcommit: 87bf574162e536003164ff9af50005c5a7dce601
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 12/14/2020
ms.locfileid: "49680236"
---
# <a name="service-diagnostics-tool-for-windows-virtual-desktop"></a>Засіб діагностики служби для віртуального настільного комп'ютера Windows

Віртуальна стільниця Windows (WVD) пропонує засіб діагностики, який дає змогу адміністраторам визначати помилки за допомогою одного інтерфейсу. Цей засіб реєструє дані, пов'язані з діагностикою, коли хтось використовує роль WVD. Кожен журнал містить відомості про роль WVD, яка бере участь у цій діяльності, повідомлення про помилки, які відображаються під час сеансу, а також відомості про клієнта та користувача. Для захоплення журналу дій, створеного діагностичним засобом, можна налаштувати Журнал активності. Ось як це зробити.

1. Створіть робочу область аналітики журналів з [лазуропорталом](https://go.microsoft.com/fwlink/?linkid=2129500) або [лазуровий PowerShell](https://go.microsoft.com/fwlink/?linkid=2129501).
1. [Підключіть комп'ютери з ОС Windows до Лазурого монітора](https://go.microsoft.com/fwlink/?linkid=2129913). Отримання ІДЕНТИФІКАТОРА робочої області та первинного ключа робочої області. Майстер настроювання має надати цю інформацію належним чином настроїти агент і переконатися, що він може спілкуватися з лазуровий монітор.
1. [Push-діагностика даних в робочій області](https://go.microsoft.com/fwlink/?linkid=2128284). Ви можете Push-дані діагностики з клієнта WVD для журналу аналітики для своєї робочої області.
1. [Виявлення та діагностика проблем](https://go.microsoft.com/fwlink/?linkid=2128338) , які є внутрішніми або зовнішніми відносно wvd.

Щоб дізнатися більше про те, як настроїти засіб діагностики служби для WVD, перегляньте статтю [використання журналу Analytics для функції діагностики](https://go.microsoft.com/fwlink/?linkid=2128084).
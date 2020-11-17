---
title: Запитання про те, як використовувати засіб розгортання Office (ODT)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: c5b055989014b464d3136895702c8ea40e8eb701
ms.sourcegitcommit: 35e2c122d8a838d98d1f0851c29b16282261580f
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 11/17/2020
ms.locfileid: "49086177"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a><span data-ttu-id="7eb38-102">Запитання про те, як використовувати засіб розгортання Office (ODT)</span><span class="sxs-lookup"><span data-stu-id="7eb38-102">Questions about how to use the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="7eb38-103">Завантажте засіб розгортання Office з [центру завантажень Microsoft](https://go.microsoft.com/fwlink/p/?LinkID=626065).</span><span class="sxs-lookup"><span data-stu-id="7eb38-103">Download the Office Deployment Tool from the [Microsoft Download Center](https://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>
  
<span data-ttu-id="7eb38-104">Після завантаження файлу запустіть виконуваний файл самовидобування, який містить виконуваний засіб розгортання Office (setupodt.exe), а також зразок файлу конфігурації (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="7eb38-104">After downloading the file, run the self-extracting executable file, which contains the Office Deployment Tool executable (setupodt.exe) and a sample configuration file (configuration.xml).</span></span>
  
 <span data-ttu-id="7eb38-105">**Щоб виключити або видалити програми Microsoft 365 для корпоративних продуктів із клієнтських комп'ютерів, виконайте такі дії:**</span><span class="sxs-lookup"><span data-stu-id="7eb38-105">**To exclude or remove Microsoft 365 Apps for enterprise products from client computers:**</span></span>
  
<span data-ttu-id="7eb38-106">Під час інсталяції програм Microsoft 365 для підприємств можна виключити певні продукти.</span><span class="sxs-lookup"><span data-stu-id="7eb38-106">When installing Microsoft 365 Apps for enterprise, you can exclude specific products.</span></span> <span data-ttu-id="7eb38-107">Щоб виконати ці дії, виконайте вказівки з інсталяції пакета Office у форматі ODT, але додайте елемент ExcludeApp у файлі конфігурації.</span><span class="sxs-lookup"><span data-stu-id="7eb38-107">To do so, follow the steps for installing Office with the ODT, but include the ExcludeApp element in your configuration file.</span></span> <span data-ttu-id="7eb38-108">Наприклад, цей файл конфігурації інсталює всі програми Microsoft 365 для підприємств, окрім видавця:</span><span class="sxs-lookup"><span data-stu-id="7eb38-108">For example, this configuration file installs all the Microsoft 365 Apps for enterprise products except Publisher:</span></span>
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[<span data-ttu-id="7eb38-109">Огляд засобу розгортання Office</span><span class="sxs-lookup"><span data-stu-id="7eb38-109">Overview of the Office Deployment Tool</span></span>](https://docs.microsoft.com/deployoffice/overview-office-deployment-tool)
  


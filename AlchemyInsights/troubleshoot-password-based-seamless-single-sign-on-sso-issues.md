---
title: Виправлення неполадок із надбудовами для єдиного входу на основі пароля (SSO)
ms.author: v-jmathew
author: v-jmathew
manager: scotv
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004357"
- "9374"
ms.openlocfilehash: 4a9163f199a505df9b2de4f02b7c37a5f5677022
ms.sourcegitcommit: 0eb4f9bde53395b5fd4b5cd4ffc56ca96db91298
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 03/10/2021
ms.locfileid: "50714891"
---
# <a name="troubleshoot-password-based-seamless-single-sign-on-sso-issues"></a><span data-ttu-id="33790-102">Виправлення неполадок із надбудовами для єдиного входу на основі пароля (SSO)</span><span class="sxs-lookup"><span data-stu-id="33790-102">Troubleshoot Password-based Seamless Single Sign-on (SSO) issues</span></span>

<span data-ttu-id="33790-103">Щоб дізнатися основи єдиного входу на основі пароля, ознайомтеся [з автентифікацією на основі пароля за допомогою служби Azure Active Directory](https://docs.microsoft.com/azure/active-directory/fundamentals/auth-password-based-sso).</span><span class="sxs-lookup"><span data-stu-id="33790-103">To learn the fundamentals of password-based SSO, see [Password-based authentication with Azure Active Directory](https://docs.microsoft.com/azure/active-directory/fundamentals/auth-password-based-sso).</span></span>

<span data-ttu-id="33790-104">**Настроювання єдиного входу на основі пароля**</span><span class="sxs-lookup"><span data-stu-id="33790-104">**Configure Password-based SSO**</span></span>

1. <span data-ttu-id="33790-105">[Настроювання єдиного входу на основі пароля](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-password-single-sign-on-non-gallery-applications) – у цій статті описано докладні відомості про параметр SSO на основі пароля.</span><span class="sxs-lookup"><span data-stu-id="33790-105">[Configure password-based single sign-on](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-password-single-sign-on-non-gallery-applications) - This article goes into more detail about the password-based SSO option.</span></span> <span data-ttu-id="33790-106">Якщо програма, яку потрібно додати, потребує настроюваної конфігурації, і вам потрібно використовувати службу єдиного входу на основі пароля, щоб ця стаття була для вас.</span><span class="sxs-lookup"><span data-stu-id="33790-106">If the application you're adding requires custom configuration and you need to use password-based SSO, then this article is for you.</span></span>
2. <span data-ttu-id="33790-107">[Настроїти єдиний вхід на основі пароля для програм для роботи з іншими програмами](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-single-sign-on-password-vaulting) – проксі-застосунок підтримує кілька режимів входу.</span><span class="sxs-lookup"><span data-stu-id="33790-107">[Configure password-based single sign on for on-prem apps](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-single-sign-on-password-vaulting) - Application Proxy supports several single sign-on modes.</span></span> <span data-ttu-id="33790-108">Вхід на основі пароля призначено для програм, які використовують комбінацію імені користувача та пароля для автентифікації.</span><span class="sxs-lookup"><span data-stu-id="33790-108">Password-based sign-on is intended for applications that use a username/password combination for authentication.</span></span> <span data-ttu-id="33790-109">Під час настроювання входу на основі пароля для програми користувачі мають входити в локальну програму.</span><span class="sxs-lookup"><span data-stu-id="33790-109">When you configure password-based sign-on for your application, your users have to sign in to the on-premises application once.</span></span> <span data-ttu-id="33790-110">Після цього Лазур Active Directory зберігає інформацію про вхід і автоматично надає його програмі, коли користувачі мають доступ до нього віддалено.</span><span class="sxs-lookup"><span data-stu-id="33790-110">After that, Azure Active Directory stores the sign-in information and automatically provides it to the application when your users access it remotely.</span></span>
    - <span data-ttu-id="33790-111">Ви вже маєте публікувати та перевіряти програму за допомогою проксі-сервера програми.</span><span class="sxs-lookup"><span data-stu-id="33790-111">You should already have published and tested your app with Application Proxy.</span></span> <span data-ttu-id="33790-112">Якщо ні, виконайте вказівки, описані в статті [публікування програм за допомогою проксі-сервера служби Azure AD](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-add-on-premises-application) , а потім Продовжіть КОНФІГУРАЦІЮ єдиного входу на основі пароля для програм для роботи з надбудовами.</span><span class="sxs-lookup"><span data-stu-id="33790-112">If not, follow the steps in [Publish applications using Azure AD Application Proxy](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-add-on-premises-application) then continue your configuration of password-based SSO for on-prem apps.</span></span>

<span data-ttu-id="33790-113">Щоб виправити виправлення ЄДИНОГО входу на основі пароля, перегляньте статтю [Виправлення неполадок із входом на основі пароля в Лазурне AD](https://docs.microsoft.com/azure/active-directory/manage-apps/troubleshoot-password-based-sso)</span><span class="sxs-lookup"><span data-stu-id="33790-113">To troubleshoot password-based SSO, see [Troubleshoot password-based single sign-on in Azure AD](https://docs.microsoft.com/azure/active-directory/manage-apps/troubleshoot-password-based-sso)</span></span>

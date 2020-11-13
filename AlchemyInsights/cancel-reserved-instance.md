---
title: Скасування резервування
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9003552"
- "6817"
ms.openlocfilehash: 04875e33f07c6d0a4306b3579ef81f2d28c7f506
ms.sourcegitcommit: f8b41ecda6db0b8f64fe0c51f1e8e6619f504d61
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 10/28/2020
ms.locfileid: "48807985"
---
# <a name="cancelling-reservation"></a><span data-ttu-id="6f86f-102">Скасування резервування</span><span class="sxs-lookup"><span data-stu-id="6f86f-102">Cancelling Reservation</span></span>

- <span data-ttu-id="6f86f-103">**Самостійне обслуговування:** Ви можете скасувати або обміняти зарезервований екземпляр самостійно за допомогою [порталу Azure Portal](https://portal.azure.com/#blade/Microsoft_Azure_Reservations/ReservationsBrowseBlade).</span><span class="sxs-lookup"><span data-stu-id="6f86f-103">**Self-service:** You can cancel or exchange a reserved instance yourself using [Azure portal](https://portal.azure.com/#blade/Microsoft_Azure_Reservations/ReservationsBrowseBlade).</span></span> <span data-ttu-id="6f86f-104">Виберіть застереження та натисніть кнопку повернення або Exchange.</span><span class="sxs-lookup"><span data-stu-id="6f86f-104">Select the reservation and click on refund or exchange.</span></span> <span data-ttu-id="6f86f-105">Зверніть увагу, що ви повинні мати доступ до власника для того, щоб обміняти або повернути кошти на ваш номер.</span><span class="sxs-lookup"><span data-stu-id="6f86f-105">Note that you must have owner access on the Reservation Order to exchange or refund.</span></span> <span data-ttu-id="6f86f-106">Доступ до бронювання тільки не дасть вам дозволу на повернення коштів або обмін ними.</span><span class="sxs-lookup"><span data-stu-id="6f86f-106">Access to only the Reservation will not let you proceed with refund or exchange.</span></span> <span data-ttu-id="6f86f-107">Запитайте власника замовлення на резервування, щоб надати вам доступ до вашого власника замовлення.</span><span class="sxs-lookup"><span data-stu-id="6f86f-107">Ask the Reservation Order owner to give you owner access to the Reservation Order</span></span>
- <span data-ttu-id="6f86f-108">**Політика Exchange:** Ви можете обміняти замовлення для іншого резервування такого самого типу – **без штрафних санкцій** за резервним замовленням.</span><span class="sxs-lookup"><span data-stu-id="6f86f-108">**Exchange policy:** You can exchange a reservation for another reservation of the same type – there are **no penalties** on reservation exchange.</span></span> <span data-ttu-id="6f86f-109">Загальна сума зобов ‟ язання з новим резервним замовленням має бути більшою, ніж сума за сумою обмінної суми, а також майбутні щомісячні платежі (якщо це можливо).</span><span class="sxs-lookup"><span data-stu-id="6f86f-109">The total commitment with new reservation should be greater than the sum of exchanged reservation’s refund amount and the future monthly payments (if applicable)</span></span>
- <span data-ttu-id="6f86f-110">**Політика повернення коштів:** Сума відшкодування та скасовані майбутні платежі не можуть перевищувати $50 000 USD в 12-місячному прокаті.</span><span class="sxs-lookup"><span data-stu-id="6f86f-110">**Refund policy:** Sum of refund and the cancelled future payments cannot exceed $50,000 USD in a 12-month rolling window.</span></span> <span data-ttu-id="6f86f-111">Зараз ми **не стягуємо штраф** на відшкодування, але могли зарядити його в майбутньому відшкодування.</span><span class="sxs-lookup"><span data-stu-id="6f86f-111">We are **currently not charging any penalty** on refunds but could charge it on future refunds</span></span>  
    <span data-ttu-id="6f86f-112">**Винятки:** Для клієнтів угоди про державну компанію з корпоративними клієнтами</span><span class="sxs-lookup"><span data-stu-id="6f86f-112">**Exceptions:** Self-service exchange and cancel capability isn't available for US Government Enterprise Agreement customers</span></span>
- <span data-ttu-id="6f86f-113">Підтримка **API/PS/CLI** не доступна для скасування та відшкодування за [користування послугами самообслуговування та відшкодування за лазуровий бронювання](https://docs.microsoft.com/azure/cost-management-billing/reservations/exchange-and-refund-azure-reservations?WT.mc_id=Portal-Microsoft_Azure_Support)</span><span class="sxs-lookup"><span data-stu-id="6f86f-113">**API / PS / CLI** support is not available for cancellation and refunds [Self-service exchanges and refunds for Azure Reservations](https://docs.microsoft.com/azure/cost-management-billing/reservations/exchange-and-refund-azure-reservations?WT.mc_id=Portal-Microsoft_Azure_Support)</span></span>
- <span data-ttu-id="6f86f-114">Для клієнтів угоди з корпоративними клієнтами для підприємств США не діє обмін службами самообслуговування та скасування можливостей.</span><span class="sxs-lookup"><span data-stu-id="6f86f-114">Self-service exchange and cancel capability isn't available for US Government Enterprise Agreement customers.</span></span> <span data-ttu-id="6f86f-115">Інші типи передплатою на уряд США, включно з оплатою за вас і CSP, підтримуються</span><span class="sxs-lookup"><span data-stu-id="6f86f-115">Other US Government subscription types including Pay-As-You-Go and CSP are supported</span></span>

<span data-ttu-id="6f86f-116">Додаткові відомості: [обробка та використання транзакцій для повернення та Exchange](https://docs.microsoft.com/azure/billing/billing-azure-reservations-self-service-exchange-and-refund?WT.mc_id=Portal-Microsoft_Azure_Support#how-return-and-exchange-transactions-are-processed)</span><span class="sxs-lookup"><span data-stu-id="6f86f-116">Learn more : [How return and exchange transactions are processed](https://docs.microsoft.com/azure/billing/billing-azure-reservations-self-service-exchange-and-refund?WT.mc_id=Portal-Microsoft_Azure_Support#how-return-and-exchange-transactions-are-processed)</span></span>  
<span data-ttu-id="6f86f-117">Додаткові відомості: [політики Exchange і повернення коштів](https://docs.microsoft.com/azure/billing/billing-azure-reservations-self-service-exchange-and-refund?WT.mc_id=Portal-Microsoft_Azure_Support#exchange-policies)</span><span class="sxs-lookup"><span data-stu-id="6f86f-117">Learn more : [Exchange and Refund policies](https://docs.microsoft.com/azure/billing/billing-azure-reservations-self-service-exchange-and-refund?WT.mc_id=Portal-Microsoft_Azure_Support#exchange-policies)</span></span>  
<span data-ttu-id="6f86f-118">Інші запитання: [відвідуйте зарезервовані документи екземпляра](https://docs.microsoft.com/azure/billing/billing-save-compute-costs-reservations?WT.mc_id=Portal-Microsoft_Azure_Support)</span><span class="sxs-lookup"><span data-stu-id="6f86f-118">Other questions: [Visit reserved instance docs](https://docs.microsoft.com/azure/billing/billing-save-compute-costs-reservations?WT.mc_id=Portal-Microsoft_Azure_Support)</span></span>

<span data-ttu-id="6f86f-119">**Exchange наявного зарезервованого екземпляра (самостійне обслуговування)**</span><span class="sxs-lookup"><span data-stu-id="6f86f-119">**Exchange an existing reserved instance (Self-service)**</span></span>

<span data-ttu-id="6f86f-120">Ви можете обміняти замовлення для іншого резервування того самого типу.</span><span class="sxs-lookup"><span data-stu-id="6f86f-120">You can exchange a reservation for another reservation of the same type.</span></span> <span data-ttu-id="6f86f-121">Ви також можете повернути бронювання до $50 000 USD на рік, якщо вам більше не потрібно.</span><span class="sxs-lookup"><span data-stu-id="6f86f-121">You can also refund a reservation, up to $50,000 USD per year, if you no longer need it.</span></span> <span data-ttu-id="6f86f-122">Для клієнтів угоди з корпоративними клієнтами для підприємств США не діє обмін службами самообслуговування та скасування можливостей.</span><span class="sxs-lookup"><span data-stu-id="6f86f-122">Self-service exchange and cancel capability isn't available for US Government Enterprise Agreement customers.</span></span> <span data-ttu-id="6f86f-123">Інші типи передплатою на уряд США, включно з оплатою за вас і CSP, підтримуються.</span><span class="sxs-lookup"><span data-stu-id="6f86f-123">Other US Government subscription types including Pay-As-You-Go and CSP are supported.</span></span> <span data-ttu-id="6f86f-124">Ви повинні мати доступ до власника для того, щоб обміняти або повернути наявне застереження.</span><span class="sxs-lookup"><span data-stu-id="6f86f-124">You must have owner access on the Reservation Order to exchange or refund an existing reservation.</span></span>

<span data-ttu-id="6f86f-125">Наведені нижче вказівки допоможуть виконати процедуру завершення транзакції</span><span class="sxs-lookup"><span data-stu-id="6f86f-125">The following steps will guide on the procedure to complete the transaction</span></span>

1. <span data-ttu-id="6f86f-126">Увійдіть на свій [портал Azure](https://portal.azure.com/#blade/Microsoft_Azure_Reservations/ReservationsBrowseBlade).</span><span class="sxs-lookup"><span data-stu-id="6f86f-126">Log in to your [Azure portal](https://portal.azure.com/#blade/Microsoft_Azure_Reservations/ReservationsBrowseBlade).</span></span> <span data-ttu-id="6f86f-127">Виберіть застереження, які потрібно повернути, і натисніть кнопку **Exchange**</span><span class="sxs-lookup"><span data-stu-id="6f86f-127">Select the reservations that you want to refund and click **Exchange**</span></span>
2. <span data-ttu-id="6f86f-128">Виберіть продукт VM, який потрібно придбати, і введіть кількість.</span><span class="sxs-lookup"><span data-stu-id="6f86f-128">Select the VM product that you want to purchase and type a quantity.</span></span> <span data-ttu-id="6f86f-129">Переконайтеся, що новий загальний обсяг покупок більше, ніж повернення підсумку [визначає потрібний розмір, перш ніж придбати](https://docs.microsoft.com/azure/virtual-machines/windows/prepay-reserved-vm-instances?WT.mc_id=Portal-Microsoft_Azure_Support#determine-the-right-vm-size-before-you-buy)</span><span class="sxs-lookup"><span data-stu-id="6f86f-129">Make sure that the new purchase total is more than the return total [Determine the right size before you purchase](https://docs.microsoft.com/azure/virtual-machines/windows/prepay-reserved-vm-instances?WT.mc_id=Portal-Microsoft_Azure_Support#determine-the-right-vm-size-before-you-buy)</span></span>
3. <span data-ttu-id="6f86f-130">Перегляд і завершення транзакції</span><span class="sxs-lookup"><span data-stu-id="6f86f-130">Review and complete the transaction</span></span>

<span data-ttu-id="6f86f-131">**Відшкодування за зарезервованим екземпляром**</span><span class="sxs-lookup"><span data-stu-id="6f86f-131">**Refund for a reserved instance**</span></span>

<span data-ttu-id="6f86f-132">Щоб повернути замовлення, перейдіть до **відомостей про бронювання** та натисніть кнопку **повернення коштів**</span><span class="sxs-lookup"><span data-stu-id="6f86f-132">To refund a reservation, go to **Reservation Details** and click **Refund**</span></span>

<span data-ttu-id="6f86f-133">**Про-номінальний повернення:**</span><span class="sxs-lookup"><span data-stu-id="6f86f-133">**Pro-rated refund:**</span></span>

<span data-ttu-id="6f86f-134">**Pro-раціон та мінімальні вимоги до вимог для відшкодування та обміну валют**</span><span class="sxs-lookup"><span data-stu-id="6f86f-134">**Pro-ration and minimum requirement examples for refund and exchange**</span></span>  
<span data-ttu-id="6f86f-135">Приклад резервування за попереднім замовленням:</span><span class="sxs-lookup"><span data-stu-id="6f86f-135">Upfront reservation example:</span></span>

- <span data-ttu-id="6f86f-136">Ви придбали один річний терм для $120 на 1 січня</span><span class="sxs-lookup"><span data-stu-id="6f86f-136">You purchase a one-year term RI for $120 on January 1</span></span>
- <span data-ttu-id="6f86f-137">7 квітня ви хочете повернути або обміняти це застереження</span><span class="sxs-lookup"><span data-stu-id="6f86f-137">On April 7th you want to refund or exchange this reservation</span></span>
- <span data-ttu-id="6f86f-138">Оскільки бронювання прожило протягом 97 днів, ви отримаєте (1-97/365) \* $120 назад.</span><span class="sxs-lookup"><span data-stu-id="6f86f-138">Since the reservation has been live for 97 days, you will get (1-97/365) \* $120 back.</span></span> <span data-ttu-id="6f86f-139">(наприклад, $88,1).</span><span class="sxs-lookup"><span data-stu-id="6f86f-139">(i.e. $88.1).</span></span> <span data-ttu-id="6f86f-140">Зараз немає штрафних санкцій на відшкодування</span><span class="sxs-lookup"><span data-stu-id="6f86f-140">There is currently no penalty on refunds</span></span>
- <span data-ttu-id="6f86f-141">Якщо ви обмінюючись, нова покупка має бути більшою за $88,1</span><span class="sxs-lookup"><span data-stu-id="6f86f-141">If exchanging, your new purchase should be greater than $88.1</span></span>
- <span data-ttu-id="6f86f-142">Зараз немає штрафних санкцій на відшкодування</span><span class="sxs-lookup"><span data-stu-id="6f86f-142">There is no penalty on refunds currently</span></span>

<span data-ttu-id="6f86f-143">**Приклад резервування плану виставлення рахунків:**</span><span class="sxs-lookup"><span data-stu-id="6f86f-143">**Billing plan reservation example:**</span></span>

- <span data-ttu-id="6f86f-144">Ви придбали один річний терм для $10 на місяць</span><span class="sxs-lookup"><span data-stu-id="6f86f-144">You purchase a one-year term RI for $10 per month</span></span>
- <span data-ttu-id="6f86f-145">7 квітня ви хочете повернути або обміняти це застереження</span><span class="sxs-lookup"><span data-stu-id="6f86f-145">On April 7th you want to refund or exchange this reservation</span></span>
- <span data-ttu-id="6f86f-146">Оскільки останній платіж стався через 7 днів, ви отримаєте (1-7/31) \* $10 назад.</span><span class="sxs-lookup"><span data-stu-id="6f86f-146">Since the last payment happened 7 days, you will get (1-7/31) \* $10 back.</span></span> <span data-ttu-id="6f86f-147">(тобто $7,74)</span><span class="sxs-lookup"><span data-stu-id="6f86f-147">(i.e. $7.74)</span></span>
- <span data-ttu-id="6f86f-148">Майбутні платежі анулюються – $80.</span><span class="sxs-lookup"><span data-stu-id="6f86f-148">The future payments cancelled are $ 80.</span></span> <span data-ttu-id="6f86f-149">Зараз немає штрафних санкцій на відшкодування</span><span class="sxs-lookup"><span data-stu-id="6f86f-149">There is currently no penalty on refunds</span></span>
- <span data-ttu-id="6f86f-150">Це скасування буде віднімати $87,74 від вас ліміт на повернення $50 000</span><span class="sxs-lookup"><span data-stu-id="6f86f-150">This cancellation will deduct $87.74 from you’re the $50,000 refund limit</span></span>
- <span data-ttu-id="6f86f-151">У разі обміну загальним значенням нової покупки має бути більше $87,74</span><span class="sxs-lookup"><span data-stu-id="6f86f-151">If exchanging, the total value of new purchase should be greater than $87.74</span></span>

<span data-ttu-id="6f86f-152">**Рекомендовані документи**</span><span class="sxs-lookup"><span data-stu-id="6f86f-152">**Recommended Documents**</span></span>

- [<span data-ttu-id="6f86f-153">Обробку транзакцій повернення та Exchange</span><span class="sxs-lookup"><span data-stu-id="6f86f-153">How return and exchange transactions are processed</span></span>](https://docs.microsoft.com/azure/billing/billing-azure-reservations-self-service-exchange-and-refund?WT.mc_id=Portal-Microsoft_Azure_Support#how-return-and-exchange-transactions-are-processed)
- [<span data-ttu-id="6f86f-154">Політики Exchange і повернення коштів</span><span class="sxs-lookup"><span data-stu-id="6f86f-154">Exchange and Refund policies</span></span>](https://docs.microsoft.com/azure/billing/billing-azure-reservations-self-service-exchange-and-refund?WT.mc_id=Portal-Microsoft_Azure_Support#exchange-policies)
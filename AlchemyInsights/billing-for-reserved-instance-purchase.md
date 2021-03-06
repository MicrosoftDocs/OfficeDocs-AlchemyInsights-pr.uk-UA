---
title: Виставлення рахунків для придбання зарезервованого екземпляра
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
- "6814"
- "9003552"
ms.openlocfilehash: 9d71554d2089a6d9e5d4850149d113959f3d43c0
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 04/15/2021
ms.locfileid: "51820343"
---
# <a name="billing-for-reserved-instance-purchase"></a>Виставлення рахунків для придбання зарезервованого екземпляра

Плату за зарезервований екземпляр стягується з методу оплати, прив'язаної до вибраної передплати під час придбання. Тип передплати має бути укладено за корпоративною угодою (номер пропозиції: MS-AZR-0017P), Pay-As-You-Go (номер пропозиції: MS-AZR-0003P), клієнтська угода з корпорацією Майкрософт або постачальник послуг CSP.

- У розмірі передплати для підприємств витрати знімаються з балансу грошового зобов'язання або сплачуються у вигляді понаднормових
- У разі передплати на Pay-As-You-Go рахунки стягуються з кредитної картки або способу оплати за рахунком-фактурою за передплатою.

**Скасування резервування**

- **Самообслуговування:** Зарезервований екземпляр можна скасувати або обміняти самостійно [на порталі Azure.](https://portal.azure.com/#blade/Microsoft_Azure_Reservations/ReservationsBrowseBlade) Виберіть резервування та натисніть кнопку "Відшкодування" або "Обмін". Зверніть увагу, що для обміну або відшкодування потрібно мати доступ власника до замовлення на резервування. Доступ лише до резервування не дозволяє продовжити відшкодування або обмін. Попросіть власника замовлення на резервування надати вам доступ до замовлення на резервування
- **Політика Exchange:** Ви можете обміняти резервування для іншого резервування того самого типу – при цьому немає жодних копій **на** обмін резервування. Загальне зобов'язання з новим резервуванням має бути більшим, ніж сума відшкодування коштів за обмін валюти та майбутні щомісячні платежі (якщо застосовно)
- **Політика відшкодування:** Сума відшкодування та скасовані майбутні платежі не можуть перевищувати 50 000 доларів США у 12-місячному вікні rolling window. **Наразі ми не стягуємо** пенсію під час відшкодування, але можемо стягувати її з майбутніх відшкодування.

**Винятки.** Можливість самостійного обміну та скасування передплати недоступна для клієнтів, укладених за договором "Us Government Enterprise Agreement"

- **Підтримка API, PS та CLI** недоступна для скасування та відшкодування самостійних обмінів і відшкодування для резервування [Azure](https://docs.microsoft.com/azure/cost-management-billing/reservations/exchange-and-refund-azure-reservations?WT.mc_id=Portal-Microsoft_Azure_Support)
- Можливість самостійного обміну та скасування послуг недоступна для клієнтів, укладених за договором "Us Government Enterprise Agreement". Підтримуються інші типи передплат для державних установ США, зокрема Pay-As-You-Go і CSP.

Докладні відомості: [Як обробляються транзакції](https://docs.microsoft.com/azure/billing/billing-azure-reservations-self-service-exchange-and-refund?WT.mc_id=Portal-Microsoft_Azure_Support#how-return-and-exchange-transactions-are-processed) повернення та обміну Learn more [(Політики](https://docs.microsoft.com/azure/billing/billing-azure-reservations-self-service-exchange-and-refund?WT.mc_id=Portal-Microsoft_Azure_Support#exchange-policies) обміну та відшкодування) Інші запитання: Відвідання [зарезервованих екземплярів docs](https://docs.microsoft.com/azure/billing/billing-save-compute-costs-reservations?WT.mc_id=Portal-Microsoft_Azure_Support)

**Exchange наявний зарезервований екземпляр (Self-service)**

Ви можете обмінюватися резервуваннями одного й того самого типу. Ви також можете відшкодувати резервування за рік до 50 000 доларів США, якщо воно більше не потрібне. Можливість самостійного обміну та скасування послуг недоступна для клієнтів, укладених за договором "Us Government Enterprise Agreement". Підтримуються інші типи передплат для державних установ США, зокрема Pay-As-You-Go і CSP. Щоб обмінятись або відшкодувати наявне резервування, потрібно мати доступ до замовлення власника.

Нижче описано процедуру завершення транзакції.

1.Увійдіть [на портал Azure.](https://portal.azure.com/#blade/Microsoft_Azure_Reservations/ReservationsBrowseBlade) Виберіть резервування, які потрібно відшкодувати, і натисніть **кнопку Exchange** 2.Виберіть продукт віртуальної реальності, який потрібно придбати, і введіть кількість. Переконайтеся, що нова сума покупки більша за суму, що [повертається, Визначте потрібний розмір перед придбанням](https://docs.microsoft.com/azure/virtual-machines/windows/prepay-reserved-vm-instances?WT.mc_id=Portal-Microsoft_Azure_Support#determine-the-right-vm-size-before-you-buy).
3.Перегляньте та завершіть транзакцію

**Відшкодування зарезервований екземпляр**

Щоб відшкодувати резервування, перейдіть до пункту **"Відомості** про резервування" та натисніть **"Відшкодування"**

**Пропорціонне відшкодування:**

**Приклади пропорційного та мінімального вимог щодо відшкодування та обміну** Приклад резервування на передньому плані:

- Придбано річний період RI за 120 дол. США з 1 січня
- 7 квітня ви хочете відшкодувати або обміняти це резервування
- Оскільки резервування проживає протягом 97 днів, ви отримаєте (1-97/365) * $120 назад. (наприклад, 88,1 дол. США). Наразі відшкодування не стягується
- Якщо нова покупка наради на суму перевищує 88,1 дол. США,
- Наразі відшкодування не стягується

**Приклад резервування плану виставлення рахунків:**

- Придбано річний термін дії RI за 10 дол. США на місяць
- 7 квітня ви хочете відшкодувати або обміняти це резервування
- Оскільки останній платіж відбувся 7 днів, ви отримаєте (1-7/31) * повернення 10 грн. (наприклад, 7,74 грн.)
- Майбутні платежі скасовано, – 80 дол. США. Наразі відшкодування не стягується
- Це скасування вирахує 87,74 дол. США з суми відшкодування в розмірі 50 000 грн.
- Якщо нова покупка змінна, загальна вартість нової покупки має бути більшою за 87,74 грн.

**Не вдається переглянути рахунок за останній розрахунковий період**

Рахунок-фактура може не відображатися з деяких можливих причин:

- У вас є щомісячна сума кредиту з передплатою, яку ви не перевищили, або у вас є безкоштовне ознайомлення. Рахунок-фактура створюється, лише коли ви ненадійні гроші
- З дня, коли ви передплатили Azure, менше ніж за 30 днів
- Ще не створено рахунок-фактуру. Дочекайтеся завершення розрахункового періоду
- Якщо ви не адміністратор облікового запису, старі рахунки-фактури можуть бути недоступні для вас

**Завантаження рахунка-фактури з порталу Azure (PDF)**

- Виберіть передплату на сторінці ["Передплати"](https://portal.azure.com/#blade/Microsoft_Azure_Billing/SubscriptionsBlade) на порталі Azure як [користувача з доступом до рахунків-фактур](https://docs.microsoft.com/azure/billing/billing-manage-access?WT.mc_id=Portal-Microsoft_Azure_Support)
- Виберіть **Рахунки-фактури**
- Натисніть **кнопку Завантажити рахунок-фактуру,** щоб переглянути копію рахунка-фактури у форматі PDF. Якщо відображається повідомлення **Недоступно,** див. номери Чому не відображається рахунок-фактура за останній [розрахунковий період?](https://docs.microsoft.com/azure/billing/billing-download-azure-invoice-daily-usage-date?WT.mc_id=Portal-Microsoft_Azure_Support#noinvoice)

**Отримання рахунка-фактури електронною поштою (PDF)**

- Виберіть передплату на [сторінці Передплати.](https://portal.azure.com/#blade/Microsoft_Azure_Billing/SubscriptionsBlade) Виберіть пункт **"Рахунки-фактури",** а потім "Надіслати рахунок електронною поштою"
- Натисніть **кнопку "Погодитися"** та прийміть умови. Вам доведеться погодитися на кожну передплату, якою ви володієте

Примітка. Якщо ви не отримаєте повідомлення електронної пошти після виконання кроків, переконайтеся, що ваша адреса електронної пошти правильна в параметрах [зв'язку у вашому профілі](https://account.windowsazure.com/profile)

**Завантаження даних про використання з порталу Azure**

- Увійдіть [у Центр облікових записів Azure](https://account.windowsazure.com/Subscriptions) як адміністратор [облікового запису](https://docs.microsoft.com/azure/billing/billing-subscription-transfer?WT.mc_id=Portal-Microsoft_Azure_Support#whoisaa)
- Виберіть передплату, для якої потрібно отримати відомості про рахунок-фактуру та відомості про використання
- Виберіть журнал **виставлення рахунків**
- Виберіть **Переглянути поточну виписку,** щоб переглянути приблизні нарахування в момент створення прогнозованого платежу.
- Натисніть **кнопку Завантажити використання,** щоб завантажити дані про щоденне використання як файл CSV. Якщо відображається дві доступні версії, завантажте версію 2

Інші запитання: ["Відвідати зарезервовані екземпляри для docs"](https://docs.microsoft.com/azure/billing/billing-save-compute-costs-reservations?WT.mc_id=Portal-Microsoft_Azure_Support)

**Рекомендовані документи**

- [Основи виставлення рахунків](https://docs.microsoft.com/partner-center/billing-basics/?WT.mc_id=Portal-Microsoft_Azure_Support)
- [Відомості про застосування знижки зарезервованого екземпляра](https://docs.microsoft.com/azure/billing/billing-understand-vm-reservation-charges/?WT.mc_id=Portal-Microsoft_Azure_Support)
- [Завантаження або перегляд рахунка-фактури з Azure і даних про щоденне використання](https://docs.microsoft.com/azure/billing/billing-download-azure-invoice-daily-usage-date?WT.mc_id=Portal-Microsoft_Azure_Support)
- [Відомості про застосування знижки зарезервованого екземпляра](https://docs.microsoft.com/azure/billing/billing-understand-vm-reservation-charges/?WT.mc_id=Portal-Microsoft_Azure_Support)
- [Розуміння використання зарезервованого екземпляра для передплати на Pay-As-You-Go](https://docs.microsoft.com/azure/billing/billing-understand-reserved-instance-usage/?WT.mc_id=Portal-Microsoft_Azure_Support)
- [Загальні відомості про використання зарезервованого екземпляра для вашої організації](https://docs.microsoft.com/azure/billing/billing-understand-reserved-instance-usage-ea/?WT.mc_id=Portal-Microsoft_Azure_Support)
- [Витрати на програмне забезпечення Windows не включено до зарезервованих екземплярів](https://docs.microsoft.com/azure/billing/billing-reserved-instance-windows-software-costs/?WT.mc_id=Portal-Microsoft_Azure_Support)
- [Зарезервовані екземпляри в програмі Центрального постачальника хмарних рішень для партнерів](https://docs.microsoft.com/partner-center/azure-reservations/?WT.mc_id=Portal-Microsoft_Azure_Support)
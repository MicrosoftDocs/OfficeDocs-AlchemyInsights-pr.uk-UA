---
title: Чому кнопка "Додати бюджет" для мене вимкнуто?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003547"
- "6464"
ms.openlocfilehash: 18edad73f617ba180cb08576ee6e5fa8faf07128
ms.sourcegitcommit: 9a7b85eae0bb775bc2498a83d8f5fedb72a6451e
ms.translationtype: MT
ms.contentlocale: uk-UA
ms.lasthandoff: 10/27/2020
ms.locfileid: "48807674"
---
# <a name="why-is-the-add-budget-button-disabled-for-me"></a><span data-ttu-id="cba41-102">Чому кнопка "Додати бюджет" для мене вимкнуто?</span><span class="sxs-lookup"><span data-stu-id="cba41-102">Why is the Add budget button disabled for me?</span></span>

<span data-ttu-id="cba41-103">Щоб створити бюджет, знадобиться один із таких дозволів:</span><span class="sxs-lookup"><span data-stu-id="cba41-103">To create a budget, you need one of the following permissions:</span></span>

- <span data-ttu-id="cba41-104">Група «керування», «Передплата», «області груп ресурсів»</span><span class="sxs-lookup"><span data-stu-id="cba41-104">Management Group, Subscription, Resource Group Scopes</span></span>
- <span data-ttu-id="cba41-105">Учасник керування витратами</span><span class="sxs-lookup"><span data-stu-id="cba41-105">Cost Management Contributor</span></span>
- <span data-ttu-id="cba41-106">Власник</span><span class="sxs-lookup"><span data-stu-id="cba41-106">Owner</span></span>
- <span data-ttu-id="cba41-107">Внесок</span><span class="sxs-lookup"><span data-stu-id="cba41-107">Contributor</span></span>
- <span data-ttu-id="cba41-108">Лише для корпоративного клієнта: «реєстрація», «відділ», «області облікових записів»</span><span class="sxs-lookup"><span data-stu-id="cba41-108">Enterprise Customer Only: Enrollment, Department, Account Scopes</span></span>
- <span data-ttu-id="cba41-109">Адміністратор реєстрації (установлення бюджету на область реєстрації)</span><span class="sxs-lookup"><span data-stu-id="cba41-109">Enrollment Admin (set budget at Enrollment scope)</span></span>
- <span data-ttu-id="cba41-110">Адміністратор відділу (Настроювання бюджету в області департаменту)</span><span class="sxs-lookup"><span data-stu-id="cba41-110">Department Admin (set budget at Department scope)</span></span>
- <span data-ttu-id="cba41-111">Власник облікового запису (Настроювання бюджету в області облікових записів)</span><span class="sxs-lookup"><span data-stu-id="cba41-111">Account Owner (set budget at Account scope)</span></span>
- <span data-ttu-id="cba41-112">Лише сучасна угода клієнта: обліковий запис рахунку, профіль виставлення рахунків, області "рахунок-фактура"</span><span class="sxs-lookup"><span data-stu-id="cba41-112">Modern Customer Agreement Only: Billing Account, Billing Profile, Invoice Section Scopes</span></span>
- <span data-ttu-id="cba41-113">Створення "Блакитний"</span><span class="sxs-lookup"><span data-stu-id="cba41-113">Azure subscription creator</span></span>

<span data-ttu-id="cba41-114">**Я створив бюджет, коли моя вартість поточного місяця вже пройшла через бюджет. Чому я не отримав оповіщення?**</span><span class="sxs-lookup"><span data-stu-id="cba41-114">**I created a budget when my cost for the current month was already over-budget. Why did I not receive an alert?**</span></span>  
<span data-ttu-id="cba41-115">Якщо ви вже перевищили певний поріг витрат, коли ви створюєте бюджет, у якому оповіщення не буде пожежа.</span><span class="sxs-lookup"><span data-stu-id="cba41-115">If you have already exceeded a given cost threshold when you create a budget that alert will not fire.</span></span> <span data-ttu-id="cba41-116">Після запуску нового циклу, якщо ви порушують поріг, то оповіщення буде пожежа.</span><span class="sxs-lookup"><span data-stu-id="cba41-116">Once a new cycle begins, if you breach the threshold then the alert will fire.</span></span>

<span data-ttu-id="cba41-117">**Коли слід очікувати отримати оповіщення після того, як ви перевищуєте один із моїх визначених порогів сповіщень про бюджет?**</span><span class="sxs-lookup"><span data-stu-id="cba41-117">**When should I expect to receive an alert after I exceed one of my defined budget alert thresholds?**</span></span>  
<span data-ttu-id="cba41-118">Бюджети обчислюються кожні 4 години.</span><span class="sxs-lookup"><span data-stu-id="cba41-118">Budgets are evaluated every 4 hours.</span></span> <span data-ttu-id="cba41-119">Для використання даних, які можна використовувати для досягнення системи бюджетів, потрібно не менше 8 годин.</span><span class="sxs-lookup"><span data-stu-id="cba41-119">It takes a minimum of 8 hours for usage data to reach the budgets system.</span></span> <span data-ttu-id="cba41-120">Якщо врахувати це, оповіщення може тривати до 12 годин, щоб вогонь після перевищення порогу.</span><span class="sxs-lookup"><span data-stu-id="cba41-120">Given this, alerts may take as long as 12 hours to fire after you exceed a threshold.</span></span>

<span data-ttu-id="cba41-121">**Чому кнопка "Дата початку" вимкнута, коли я вибюю час скидання місяця або місяця виставлення рахунків?**</span><span class="sxs-lookup"><span data-stu-id="cba41-121">**Why is the Start date button disabled when I select a Month or Billing month reset period?**</span></span>  
<span data-ttu-id="cba41-122">Бюджети відповідають поточному календарному місяцю або поточному рахунку (у випадку, коли вибрано "місяць виставлення рахунків").</span><span class="sxs-lookup"><span data-stu-id="cba41-122">Budgets are aligned to the current calendar month or current billing period (in the case where Billing Month is selected).</span></span> <span data-ttu-id="cba41-123">Тому ми попередньо заповните це значення.</span><span class="sxs-lookup"><span data-stu-id="cba41-123">Therefore, we pre-populate this value for you.</span></span>

<span data-ttu-id="cba41-124">**Чому граф моїх витрат не відображається в досвіді створення бюджету?**</span><span class="sxs-lookup"><span data-stu-id="cba41-124">**Why do I not see a graph of my costs in the budget creation experience?**</span></span>  
<span data-ttu-id="cba41-125">Нам потрібно мінімум 2 місяці вартості даних, перш ніж ми зможемо надати графік, щоб допомогти вам у створенні бюджету.</span><span class="sxs-lookup"><span data-stu-id="cba41-125">We need a minimum of 2 months of cost data before we can render a graph to assist you with budget creation.</span></span>

<span data-ttu-id="cba41-126">**Чому я не можу встановити бюджет із передплатою, яку я щойно створив?**</span><span class="sxs-lookup"><span data-stu-id="cba41-126">**Why can't I set a budget against a subscription I just created?**</span></span>  
<span data-ttu-id="cba41-127">Після створення передплатою, дані мають 24-48 годин для обробки, перш ніж встановлювати бюджет.</span><span class="sxs-lookup"><span data-stu-id="cba41-127">After the creation of a subscription, the data takes 24-48 hours to process before setting a budget against it.</span></span>

<span data-ttu-id="cba41-128">**Ресурси бюджетної API**</span><span class="sxs-lookup"><span data-stu-id="cba41-128">**Budget API Resources**</span></span>

- <span data-ttu-id="cba41-129">" [БЮДЖЕТИ API" V1](https://docs.microsoft.com/rest/api/consumption/budgets?WT.mc_id=Portal-Microsoft_Azure_Support): надає операції для створення та оновлення бюджетів.</span><span class="sxs-lookup"><span data-stu-id="cba41-129">[Budgets API v1](https://docs.microsoft.com/rest/api/consumption/budgets?WT.mc_id=Portal-Microsoft_Azure_Support): Provides operations to create and update budgets.</span></span> <span data-ttu-id="cba41-130">Використовуючи API для бюджетів, ви можете встановити граничне значення бюджету та настроїти кілька оповіщень на пожежу під час наближення цього порогу.</span><span class="sxs-lookup"><span data-stu-id="cba41-130">Using the Budgets API, you can set a budget threshold and configure multiple alerts to fire as you approach that threshold.</span></span> <span data-ttu-id="cba41-131">Оповіщення можуть ініціювати електронну пошту або групу дій Azure, щоб виконувати автоматизацію.</span><span class="sxs-lookup"><span data-stu-id="cba41-131">Alerts can trigger an email or an Azure Action Group to perform automation.</span></span> <span data-ttu-id="cba41-132">Примітка. фільтрування для цього API не вирівнюється за допомогою фільтрування та вимірів API запитів.</span><span class="sxs-lookup"><span data-stu-id="cba41-132">Note: Filtering for this API does not align with Query API filtering / dimensions.</span></span>
- <span data-ttu-id="cba41-133">[БЮДЖЕТИ API V2](https://github.com/Azure/azure-rest-api-specs/blob/master/specification/cost-management/resource-manager/Microsoft.CostManagement/preview/2019-04-01-preview/examples/CreateOrUpdateBudget.json): створення бюджетів за допомогою більшої вартості фільтруючих можливостей, ніж V1.</span><span class="sxs-lookup"><span data-stu-id="cba41-133">[Budgets API v2](https://github.com/Azure/azure-rest-api-specs/blob/master/specification/cost-management/resource-manager/Microsoft.CostManagement/preview/2019-04-01-preview/examples/CreateOrUpdateBudget.json): Create budgets with greater cost filtering capabilities than v1.</span></span> <span data-ttu-id="cba41-134">Фільтрування Вирівнює за договором, який використовується в нашому запиті та розмірах API.</span><span class="sxs-lookup"><span data-stu-id="cba41-134">Filtering aligns to the contract used in our Query and Dimensions APIs.</span></span> <span data-ttu-id="cba41-135">Це рекомендований API для бюджетів, щоб використовувати рух вперед.</span><span class="sxs-lookup"><span data-stu-id="cba41-135">This is the recommended budgets API to use moving forward.</span></span>
- <span data-ttu-id="cba41-136">[Розміри](https://docs.microsoft.com/rest/api/cost-management/dimensions?WT.mc_id=Portal-Microsoft_Azure_Support): надає операції, щоб отримати підтримувані розміри для використання в різних областях.</span><span class="sxs-lookup"><span data-stu-id="cba41-136">[Dimensions](https://docs.microsoft.com/rest/api/cost-management/dimensions?WT.mc_id=Portal-Microsoft_Azure_Support): Provides operations to get supported dimensions for your usage under a variety of scopes.</span></span> <span data-ttu-id="cba41-137">Використовуючи API "виміри", можна отримати список вимірів, які можна використовувати як входи для створення запитів за допомогою API запитів.</span><span class="sxs-lookup"><span data-stu-id="cba41-137">Using the Dimensions API, you can retrieve a list of dimensions that can be used as inputs for generating queries with the Query API.</span></span>
- <span data-ttu-id="cba41-138">[Запит](https://docs.microsoft.com/rest/api/cost-management/query?WT.mc_id=Portal-Microsoft_Azure_Support): надає операції, щоб отримати Сукупні витрати та дані про використання на основі запиту, який ви надаєте.</span><span class="sxs-lookup"><span data-stu-id="cba41-138">[Query](https://docs.microsoft.com/rest/api/cost-management/query?WT.mc_id=Portal-Microsoft_Azure_Support): Provides operations to get aggregated cost and usage data based on the query you supply.</span></span> <span data-ttu-id="cba41-139">За допомогою API запитів можна вказати бажаний фільтрування, сортування та групування на всіх доступних розмірах (які доступні з API "виміри").</span><span class="sxs-lookup"><span data-stu-id="cba41-139">Using the Query API, you can specify your desired filtering, sorting and grouping on all available dimensions (which are accessed from the Dimensions API).</span></span>

<span data-ttu-id="cba41-140">**Прогнозовані витрати**</span><span class="sxs-lookup"><span data-stu-id="cba41-140">**Forecasted Costs**</span></span>

<span data-ttu-id="cba41-141">**Чому не відображаються прогнози для витрат у аналізі витрат?**</span><span class="sxs-lookup"><span data-stu-id="cba41-141">**Why don’t I see forecasts for my costs in Cost Analysis?**</span></span>  
<span data-ttu-id="cba41-142">Існує кілька причин, через які проекцію прогнозу може бути відсутнє для вас у аналізі витрат, деякі з них мають такий вигляд:</span><span class="sxs-lookup"><span data-stu-id="cba41-142">There are multiple reasons why the forecast projection might be missing for you in Cost Analysis, some of them are as follows:</span></span>

1. <span data-ttu-id="cba41-143">Якщо вартість даних становить менше 10 днів, діаграму прогнозу не завантажиться.</span><span class="sxs-lookup"><span data-stu-id="cba41-143">If your cost data is less than 10 days old, the forecast chart will not load.</span></span> <span data-ttu-id="cba41-144">Модель вимагає принаймні 10 днів після нещодавньої вартості даних для точних прогнозів</span><span class="sxs-lookup"><span data-stu-id="cba41-144">The model requires at least 10 days of recent cost data for accurate projections</span></span>
2. <span data-ttu-id="cba41-145">Якщо виділено історичні дати, діаграму не буде видно.</span><span class="sxs-lookup"><span data-stu-id="cba41-145">If you have selected historic dates, then the forecast chart will not be visible.</span></span> <span data-ttu-id="cba41-146">Виберіть проміжок часу, у якому майбутні дати для діаграми прогнозного відображення</span><span class="sxs-lookup"><span data-stu-id="cba41-146">Please select a date range with future dates for the forecast chart to be displayed</span></span>
3. <span data-ttu-id="cba41-147">Якщо ваш обліковий запис має кілька валют, на діаграмі прогнозу буде лише вартість проекту "Усі витрати в доларах США"</span><span class="sxs-lookup"><span data-stu-id="cba41-147">If your account has multiple currencies, the forecast chart will only project costs for 'All costs in USD'</span></span>

<span data-ttu-id="cba41-148">**Чому прогноз зміниться під час внесення змін до ресурсів?**</span><span class="sxs-lookup"><span data-stu-id="cba41-148">**Why doesn’t the forecast change when I make changes to my resources?**</span></span>  
<span data-ttu-id="cba41-149">Модель прогнозу вимагає кілька днів, щоб враховувати зміни в обліковому записі, а також не вносити негайні прогнози на основі змін у ресурсах</span><span class="sxs-lookup"><span data-stu-id="cba41-149">The forecast model requires a couple of days to account for changes in the account and does not make immediate projections based on change in resources</span></span>  
<span data-ttu-id="cba41-150">Для більших кроків збільшення або зменшення кількості ресурсів модель займе трохи більше часу, щоб ці зміни були в обліковому записі для аномалій</span><span class="sxs-lookup"><span data-stu-id="cba41-150">For larger steps of increase or decrease in resources, the model will take slightly longer to adjust to these changes to account for anomalies</span></span>

<span data-ttu-id="cba41-151">**Чому мій прогноз збільшиться після того, як ви робите покупку або придбання ринку?**</span><span class="sxs-lookup"><span data-stu-id="cba41-151">**Why does my forecast increase after I make a reservation or Marketplace purchase?**</span></span>  
<span data-ttu-id="cba41-152">Модель прогнозу враховує ваші фактичні витрати та не враховує використання та придбання окремо. Для одноразової покупки модель зменшить прогнози через 10 днів, щоб враховувати різке збільшення витрат.</span><span class="sxs-lookup"><span data-stu-id="cba41-152">The forecast model considers your 'Actual Cost' and does not account for usage and purchase separately.For a one-time purchase, the model will decrease the projections after 10 days to account for the sudden increase in costs</span></span>

<span data-ttu-id="cba41-153">**Я хочу переглянути прогнози для окремого виміру (наприклад. Метр**</span><span class="sxs-lookup"><span data-stu-id="cba41-153">**I want to see forecasts for a single dimension (eg. Meter)**</span></span>  
<span data-ttu-id="cba41-154">Зараз прогноз підтримує загальні прогнози на витрати, а не для окремих лічильників.</span><span class="sxs-lookup"><span data-stu-id="cba41-154">Forecast currently supports total cost projections and not for individual meters.</span></span> <span data-ttu-id="cba41-155">Таким чином, коли "згруповано за" виміром, прогнози міститимуться в загальній складності всіх одиниць виміру.</span><span class="sxs-lookup"><span data-stu-id="cba41-155">Hence, when 'Grouped by' a dimension, the projections will be for total of all items in the dimension</span></span>

<span data-ttu-id="cba41-156">**Рекомендовані документи**</span><span class="sxs-lookup"><span data-stu-id="cba41-156">**Recommended Documents**</span></span>

- [<span data-ttu-id="cba41-157">Що таке Лазурне керування витратами?</span><span class="sxs-lookup"><span data-stu-id="cba41-157">What is Azure Cost Management?</span></span>](https://docs.microsoft.com/azure/cost-management/overview-cost-mgt?WT.mc_id=Portal-Microsoft_Azure_Support)
- [<span data-ttu-id="cba41-158">Практичні поради з керування витратами в "Блакитний"</span><span class="sxs-lookup"><span data-stu-id="cba41-158">Azure Cost Management best practices</span></span>](https://docs.microsoft.com/azure/cost-management/cost-mgt-best-practices?WT.mc_id=Portal-Microsoft_Azure_Support)
- [<span data-ttu-id="cba41-159">Аналізувати витрати та витрати</span><span class="sxs-lookup"><span data-stu-id="cba41-159">Analyze your costs and spending</span></span>](https://docs.microsoft.com/azure/cost-management/quick-acm-cost-analysis?WT.mc_id=Portal-Microsoft_Azure_Support)
- [<span data-ttu-id="cba41-160">Огляд та аналіз витрат за допомогою аналізу витрат</span><span class="sxs-lookup"><span data-stu-id="cba41-160">Explore and analyze costs with Cost analysis</span></span>](https://docs.microsoft.com/azure/cost-management/quick-acm-cost-analysis?WT.mc_id=Portal-Microsoft_Azure_Support)
- [<span data-ttu-id="cba41-161">Керування витратами на Лазурне: ціноутворення</span><span class="sxs-lookup"><span data-stu-id="cba41-161">Azure Cost Management: Pricing</span></span>](https://azure.microsoft.com/services/cost-management/#pricing)
- [<span data-ttu-id="cba41-162">Перевірка витрат у аналізі витрат</span><span class="sxs-lookup"><span data-stu-id="cba41-162">Review costs in cost analysis</span></span>](https://docs.microsoft.com/azure/cost-management-billing/costs/quick-acm-cost-analysis?WT.mc_id=Portal-Microsoft_Azure_Support#review-costs-in-cost-analysis)
- [<span data-ttu-id="cba41-163">Навчальне відео: створення бюджету на порталі «Лазурний»</span><span class="sxs-lookup"><span data-stu-id="cba41-163">Video tutorial: Create a budget in the Azure portal</span></span>](https://www.youtube.com/watch?v=ExIVG_Gr45A&t=4s)
- [<span data-ttu-id="cba41-164">Попередні вимоги для перегляду та настроювання бюджетів</span><span class="sxs-lookup"><span data-stu-id="cba41-164">Prerequisites for viewing and customizing budgets</span></span>](https://docs.microsoft.com/azure/cost-management-billing/costs/tutorial-acm-create-budgets?WT.mc_id=Portal-Microsoft_Azure_Support#prerequisites)
- [<span data-ttu-id="cba41-165">Створення та керування бюджетами</span><span class="sxs-lookup"><span data-stu-id="cba41-165">Create and manage budgets</span></span>](https://docs.microsoft.com/azure/cost-management-billing/costs/tutorial-acm-create-budgets?WT.mc_id=Portal-Microsoft_Azure_Support#create-a-budget-in-the-azure-portal)
- [<span data-ttu-id="cba41-166">Настроювання автоматизації за допомогою ІНТЕРФЕЙСУ "Azure груп дій і бюджетів"</span><span class="sxs-lookup"><span data-stu-id="cba41-166">Configure automation with Azure Action Groups and Budgets API</span></span>](https://docs.microsoft.com/azure/cost-management/tutorial-acm-create-budgets?WT.mc_id=Portal-Microsoft_Azure_Support#trigger-an-action-group)
- [<span data-ttu-id="cba41-167">Використання сповіщень про витрати для відстеження використання та витрачання коштів</span><span class="sxs-lookup"><span data-stu-id="cba41-167">Use cost alerts to monitor usage and spending</span></span>](https://docs.microsoft.com/azure/cost-management/cost-mgt-alerts-monitor-usage-spending?WT.mc_id=Portal-Microsoft_Azure_Support)
- [<span data-ttu-id="cba41-168">Практичні поради з керування витратами</span><span class="sxs-lookup"><span data-stu-id="cba41-168">Cost Management best practices</span></span>](https://docs.microsoft.com/azure/cost-management/cost-mgt-best-practices?WT.mc_id=Portal-Microsoft_Azure_Support)  

<span data-ttu-id="cba41-169">**Навчальне відео**</span><span class="sxs-lookup"><span data-stu-id="cba41-169">**Tutorial videos**</span></span>

- [<span data-ttu-id="cba41-170">Створення бюджету на порталі «Лазурний»</span><span class="sxs-lookup"><span data-stu-id="cba41-170">Create a budget in the Azure portal</span></span>](https://go.microsoft.com/fwlink/?linkid=2146761)
- [<span data-ttu-id="cba41-171">Керування витратами за допомогою API бюджетів і груп дій</span><span class="sxs-lookup"><span data-stu-id="cba41-171">Manage costs with the Budgets API and Action Groups</span></span>](https://go.microsoft.com/fwlink/?linkid=2147038)
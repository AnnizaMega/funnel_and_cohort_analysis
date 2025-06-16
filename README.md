# 📁 Funnel and Cohort Analysis

![Tableau](https://img.shields.io/badge/Tableau-Dashboard-orange)

##  Table of Contents
- [Business Background](#business-background)
- [Analysis Method](#analysis-method)
- [Tech Stack](#tech-stack)
- [Dataset Overview](#dataset-overview)
- [Key Findings and Insights (Funnel)](#key-findings-and-insights-funnel)
- [Key Findings and Insights (Cohort)](#key-findings-and-insights-cohort)
- [Recommendations](#recommendations)
- [Links to Dashboard](#links-to-dashboard)

---

##  Business Background

This project focuses on two key analytical techniques — **funnel analysis and cohort analysis** — to help businesses:
- Understand their **customer journey**, from initial view to eventual purchase.
- Identify points where potential customers drop off and opportunities to optimize conversions.
- Monitor **customer retention and loyalty trends** over time.

---

##  Analysis Method

###  Funnel Analysis:
1️⃣ **Defining the Funnel:**  
We defined key stages in the customer journey — View Product → Add to Cart → Complete Purchase.

2️⃣ **Collecting and Analyzing Conversion:**  
Using data from a large e-commerce platform, we measured drop-offs at each stage and total conversion rate from view to purchase.

---

###  Cohort Analysis:
1️⃣ **Creating Cohorts:**  
We grouped users by their first transaction's **month of registration**.

2️⃣ **Retention Analysis:**  
Using these cohorts, we tracked their activity, transactions, and revenue over subsequent periods.  
This lets us observe trends in retention and revenue by cohort.

---

##  Tech Stack

- **Tableau:** Visualizing funnel drop-off, retention trends, and revenue by cohorts
- **Python (optional for data prep)**: pandas, numpy
- **Other:** CSV files, Microsoft Excel for initial exploration

---

##  Dataset Overview

➥ **Funnel:**  
- **Event:** view, add to cart, and purchase  
- **Features:** User IDs, Product IDs, Categories, Sessions, Conversion
- **Size:** Large, multivariate, e-commerce transactions

➥ **Cohort:**  
- **Event:** Signup, Transactions, Revenue
- **Features:** User IDs, Signup Date, Transactions, Spending
- **Size:** Large, multivariate, financial transactions

---

##  Key Findings and Insights (Funnel)

 The view-to-cart conversion drops from 100% to ≅ 10%.  
 The cart-to-purchase conversion is much higher (≅ 60%) — indicating strong buying signals once a product reaches the cart.  
 Overall view-to-purchase drops to ≅ 5%.  
 There’s a significant opportunity to increase conversions by optimizing the view-to-cart process (such as adding promotions, simplifying UI, or improving product visibility).

---

##  Key Findings and Insights (Cohort)

 **Corporate accounts** contribute a large portion of transactions and revenue.  
 There are **clear seasonal trends**, with transactions peaking in certain months (such as February), likely due to annual budgets or promotions.  
 Individual segments have potential for growth — promotions or pricing strategies could be tailored to increase their engagement.

---

##  Recommendations

➥ **Funnel:**  
 Implement promotions or incentives to move more viewers into adding products to their carts.  
 Improve UI/UX to reduce drop-offs during view-to-cart.

➥ **Cohort:**  
 Develop loyalty programs and specialized pricing plans for corporate clients.  
 Expand promotions to individual segments to increase engagement and transactions.  
 Align promotions with seasonal trends to maximize revenue during peak periods.

---

##  Links to Dashboard

➥ [Tableau Dashboard – Funnel Analysis](https://public.tableau.com/views/FunnelAnalysis-Assigment/Dashboard1?:language=en-US)

➥ [Tableau Dashboard – Cohort Analysis](https://public.tableau.com/views/cohortanalysisassigment/Dashboard1?:language=en-US)

---

 If you'd like more details or a walkthrough, please feel free to [contact me](mailto:annizamegabianalyst@gmail.com).

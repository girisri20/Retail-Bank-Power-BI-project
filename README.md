# 🏦 Retail Bank Analytics — Power BI Dashboard

## 📊 Project Overview

This project is an interactive **Retail Banking Analytics Dashboard** developed using **Microsoft Power BI**.

The dashboard provides a comprehensive view of banking operations by analyzing **customers, accounts, cards, transactions, and loans**. It converts raw banking data into interactive visualizations and key performance indicators (KPIs) that can help understand customer behavior, transaction activity, loan performance, and account/card usage.

The project is designed to provide a centralized analytical view of a retail bank's business performance.

---

## 🎯 Project Objectives

The main objectives of this project are to:

* Analyze the overall performance of the retail banking business.
* Understand customer demographics and segmentation.
* Monitor customer activity and KYC status.
* Analyze transaction volume and transaction channels.
* Evaluate loan performance and outstanding balances.
* Analyze account types and account balances.
* Understand credit-card usage and card networks.
* Track important banking KPIs through interactive dashboards.
* Provide insights that can support data-driven business decisions.

---

## 🛠️ Tools & Technologies

| Technology                     | Purpose                                      |
| ------------------------------ | -------------------------------------------- |
| **Microsoft Power BI**         | Dashboard development and data visualization |
| **Power Query**                | Data preparation and transformation          |
| **DAX**                        | Measures and KPI calculations                |
| **Data Modeling**              | Relationships between banking entities       |
| **Interactive Visualizations** | Business analysis and reporting              |

---

## 🗂️ Data Model

The Power BI project contains the following major tables:

* `customers`
* `accounts`
* `cards`
* `transactions`
* `loans`
* `loan_payments`
* `branches`
* `date_table`

The model combines customer, account, card, transaction, and loan information to provide a consolidated view of retail banking activity.

### Main Business Entities

**Customers → Accounts → Transactions**

Customers are associated with banking accounts, which generate transaction activity.

**Customers → Loans → Loan Payments**

Customers can have loans, while loan payment information supports loan and repayment analysis.

**Accounts → Cards**

Accounts can be associated with cards, allowing analysis of card types, networks, balances, and credit limits.

---

# 📑 Dashboard Pages

The report contains **5 analytical pages**.

## 1. Executive Overview

Provides a high-level summary of the bank's overall performance.

### Key KPIs

* Total Customers
* Active Customers
* Total Accounts
* Total Transaction Value
* Total Outstanding Loan
* Total Principal Amount
* Loan Default Rate

### Analysis

The page also provides visual analysis of:

* Transaction value over time
* Transaction value by channel
* Overall banking performance

This page acts as the primary management-level overview of the bank.

---

## 2. Customer Analytics

This page focuses on customer behavior and customer characteristics.

### Key KPIs

* Total Customers
* Active Customers
* Average Customer Income
* Average Credit Score

### Analysis Includes

* Customer segmentation
* KYC status
* Customer income by segment
* Credit score distribution
* Customer-level analysis

### Business Questions

* How many customers are active?
* What is the average customer income?
* What is the average credit score?
* How are customers distributed across segments?
* What is the KYC status of customers?

---

## 3. Transaction Analytics

This page analyzes banking transaction activity.

### Key KPI

* Average Transaction Value

### Analysis Includes

* Transaction amount
* Transaction channel
* Transaction status
* Account-level transaction activity
* Balance after transaction

### Business Questions

* Which transaction channels are most frequently used?
* What is the average transaction value?
* How are transactions distributed by status?
* Which accounts generate higher transaction activity?
* How does account balance change after transactions?

---

## 4. Loan Analytics

This page focuses on the bank's loan portfolio.

### Key KPI

* Average EMI

### Analysis Includes

* Principal amount
* Outstanding balance
* Loan type
* Loan status
* Loan purpose
* Interest rate

### Business Questions

* What is the total principal amount issued?
* How much loan balance remains outstanding?
* Which loan types are most common?
* What is the distribution of loan status?
* Which loan purposes have higher principal amounts?
* How do interest rates vary across loan types?

---

## 5. Account & Card Analytics

This page analyzes customer accounts and banking cards.

### Analysis Includes

* Total accounts
* Current account balance
* Account type
* Card count
* Card type
* Card network
* Credit limit

### Business Questions

* Which account types are most common?
* Which account types have higher balances?
* What types of cards are being used?
* Which card networks are most common?
* What are the available credit limits?

---

# 📈 Key KPIs

The dashboard includes several important banking metrics:

### Customer KPIs

* **Total Customers**
* **Active Customers**
* **Average Customer Income**
* **Average Credit Score**

### Account KPIs

* **Total Accounts**
* **Account Balance**
* **Account Type Distribution**

### Transaction KPIs

* **Total Transaction Value**
* **Average Transaction Value**
* **Transaction Channel**
* **Transaction Status**

### Loan KPIs

* **Total Principal Amount**
* **Total Outstanding Loan**
* **Average EMI**
* **Loan Default Rate**
* **Interest Rate**

### Card KPIs

* **Total Cards**
* **Card Type**
* **Card Network**
* **Credit Limit**

---

# 📊 Visualization Techniques

The project uses multiple Power BI visualizations, including:

* KPI Cards
* Column Charts
* Bar Charts
* Line Charts
* Donut Charts
* Interactive filters
* Time-based analysis
* Category-based comparisons

The dashboard uses a consistent layout and theme across the different analytical pages.

---

# 🔄 Data Analysis Workflow

The project follows a typical Business Intelligence workflow:

```text
Raw Banking Data
       ↓
Data Cleaning & Transformation
       ↓
Data Modeling
       ↓
Relationships Between Tables
       ↓
DAX Measures & KPIs
       ↓
Interactive Power BI Visualizations
       ↓
Business Insights
```

---

# 🧮 DAX & Measures

The dashboard uses measures to calculate important business metrics such as:

* Total Customers
* Active Customers
* Total Accounts
* Total Transaction Value
* Total Outstanding Loan
* Total Principal Amount
* Average Transaction Value
* Average Customer Income
* Average Credit Score
* Average EMI
* Loan Default Rate

These measures allow the dashboard to dynamically respond to filters and user selections.

---

# 🎨 Dashboard Design

The report uses a consistent dashboard design across all pages.

The pages use:

* Consistent visual styling
* KPI cards for important metrics
* Charts for trend and category analysis
* Interactive filtering
* A structured business-oriented layout
* A unified visual theme

The dashboard is designed to allow users to move from an overall business summary to detailed customer, transaction, loan, account, and card analysis.

---

# 💡 Business Insights

The dashboard can help banking stakeholders:

* Monitor customer growth and activity.
* Understand customer segments.
* Identify transaction patterns.
* Evaluate loan portfolio performance.
* Monitor outstanding loan balances.
* Analyze loan defaults.
* Understand account usage.
* Analyze card adoption and usage.
* Compare different banking products.
* Support data-driven decision making.

---

# 🚀 How to Use the Project

1. Download or clone this repository.
2. Open the `.pbix` file using **Microsoft Power BI Desktop**.
3. Allow Power BI to load the associated data/model if required.
4. Navigate through the dashboard pages using the page navigation.
5. Use available filters and interactive visuals to explore the data.
6. Select charts or KPIs to cross-filter other visuals.

---

# 📁 Project Structure

```text
Retail-Bank-PowerBI/
│
├── Retail bank.pbix
└── README.md
```

---

# 📌 Dashboard Pages

```text
Retail Bank Analytics
│
├── Executive Overview
│
├── Customer Analytics
│
├── Transaction Analytics
│
├── Loan Analytics
│
└── Account & Card Analytics
```

---

# 🎓 Project Skills Demonstrated

This project demonstrates practical skills in:

* Business Intelligence
* Data Visualization
* Microsoft Power BI
* Power Query
* DAX
* Data Modeling
* KPI Development
* Banking Analytics
* Customer Analytics
* Financial Analytics
* Interactive Dashboard Design
* Business Reporting

---

# 📜 Conclusion

The **Retail Bank Analytics Dashboard** transforms banking data into an interactive business intelligence solution.

By combining customer, account, card, transaction, and loan data, the dashboard provides a 360-degree analytical view of retail banking operations.

The project demonstrates how **Power BI, data modeling, DAX, and visualization techniques** can be used to convert raw data into meaningful business insights and support better decision-making.

---

## 👤 Author

**Harsha**

### Built with ❤️ using Microsoft Power BI

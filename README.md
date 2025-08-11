

# Banking Dashboard – Risk Analytics in Banking

## 📌 Problem Statement

The goal of this project is to develop a **basic understanding of risk analytics** in banking and financial services, and to demonstrate how data can be used to **minimize the risk of losing money while lending to customers**.

---

## 💡 Solution

We built **interactive dashboards using Power BI** to help banks and financial institutions make informed decisions.
The dashboards analyze an applicant’s profile to predict their likelihood of repaying loans, enabling data-driven approval decisions.

---

## 📂 About the Dataset

The dataset contains multiple interlinked tables with client and banking details, connected via **primary and foreign keys**:

* **Banking Relationship**
* **Client-Banking**
* **Gender**
* **Investment Advisor**
* **Period**

---

## 🛠 Data Cleaning & Transformation

* Created **Engagement Timeframe** (timeline of client’s relationship with bank)
* Calculated **Engagement Days** (days since joining)
* Created **Income Band**:

  * `< 100000` → Low
  * `< 300000` → Mid
* Derived **Processing Fees** based on fee structure
* Used calculated DAX functions like `SUM`, `DISTINCTCOUNT`, `SUMX`, `SWITCH`, `DATEDIFF`

---

## 📊 Key KPIs

* **Total Clients** – Distinct count of clients
* **Total Loan** – Sum of bank loan, business lending, and credit card balance
* **Bank Loan**, **Business Lending**, **Total Deposit**
* **Total Fees**, **Bank Deposit**, **Checking Account Amount**
* **Total CC Amount**, **Savings Account Amount**, **Foreign Currency Amount**
* **Engagement Account**, **Credit Card Balance**

---

## 📈 Dashboards

1. **Home**
2. **Loan Analysis**
3. **Deposit Analysis**
4. **Summary Dashboard**

These dashboards visualize:

* Loan distribution by client type
* Deposit trends
* Client engagement duration
* Account-wise transaction insights

---

## ✅ Conclusion

Power BI dashboards enable **data-driven decision making** in banking.
They provide:

* Insights into total loans, deposits, and engagement
* Client distribution across different banks
* Nationality-based loan trends
* Account type–wise financial details

---

## 🖥 Tools & Technologies

* **Power BI** – Data visualization
* **DAX** – Calculated columns & measures
* **Data Cleaning & Transformation** in Power BI

---





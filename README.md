# AtliQ Hardware: Sales Intelligence & Reporting Automation
## [View Full SQL Project Report (PDF)](./SQL%20Project.pdf)

## 📌 Executive Summary
This project involved architecting a high-performance SQL-based analytical framework to automate sales reporting for a global hardware manufacturer. By shifting business logic from manual Excel processes to **Server-Side Stored Procedures** and **UDFs**, I reduced reporting latency by **95%** and established a standardized "Single Source of Truth" for global stakeholders.

---

## 🏗️ System Architecture & Strategy
The core of this project is built on a **Star Schema** optimized for high-concurrency analytical queries.

### 1. Data Normalization (UDFs)
Created a custom **User-Defined Functions** to handle complex temporal transformations. This ensures that all transactions across multiple tables align with the specific September-August fiscal cycle, eliminating "Calendar-vs-Fiscal" reporting errors.

### 2. High-Performance Views
To simplify the analytical layer, I created **Database Views** (e.g., `net_sales`, `gross_sales`). This decouples raw transaction data from the reporting layer, allowing for sub-second query performance during high-volume joins.

### 3. Automated Performance Tiering (Stored Procedures)
I developed a **Dynamic Classification Engine** (`get_market_badge`) that uses threshold-driven logic ($>5\text{M}$ units) to programmatically assign market performance states ("Gold" vs "Silver").

---

## 🚀 Key Deliverables

| Tool | Technical Purpose | Business Impact |
| :--- | :--- | :--- |
| **Top-N Analysis** | Identifies high-velocity Markets/Products. | Facilitates strategic resource allocation. |
| **Monthly Sales API** | Parametrized procedure for stakeholders. | Enables self-service BI for Product Owners. |
| **Market Badge** | Automated performance categorization. | Standardizes regional success metrics. |

---

## 💡 Actionable Insights (FY 2021)

* **Market Leadership:** **India** dominated global sales with **$210.67M** in Net Sales, outperforming the **USA** by over **1.5x**.
* **Flagship SKU:** **AQ BZ Allin1** was identified as the highest revenue driver, generating **$33.75M** in net sales.
* **Channel Strategy:** **Amazon ($30M)** and **Atliq Exclusive** emerged as the top customers, validating a strong shift toward e-commerce and direct-to-consumer channels.

---

## 🛠️ Technical Stack & Skills
* **Database:** MySQL 
* **SQL Engineering:** Stored Procedures, UDFs, CTEs, Window Functions, Schema Design,EER.
* **Analytical Methodology:** STAR Method (Situation, Task, Action, Result).
* **Performance Tuning:** Primary/Foreign Key indexing and Joins optimization.

---

## 📂 Repository Structure
* <iframe src="https://1drv.ms/p/c/A12F2CA3782F59B4/IQSSPAwwGY_DTYwwgrPrjO2mAYI-j6r8nWqALEus542Wc1I?wdAr=1.7777777777777777" width="476px" height="288px" frameborder="0" title="PowerPoint Viewer">This is an embedded <a target="_blank" href="https://office.com">Microsoft Office</a> presentation, powered by <a target="_blank" href="https://office.com/webapps">Office</a>.</iframe>: Final slide deck for executive review.

---

### 👤 Contact & Links
**Narmatha Annadurai** – Data Analyst  
[LinkedIn Profile](https://www.linkedin.com/in/narmatha-annadurai-32ba14237/) | [LeetCode](https://leetcode.com/u/narmathaannadurai03/) Solved 300+ Database problems 

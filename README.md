#  Project Notebook: Olist E-Commerce Analytics

---

##  Overview

Olist is a Brazilian all-in-one e-commerce platform. It's not like the usual logistics companies; although it handles logistics, it does more: it connects small and medium businesses to the market by linking their products to major marketplaces, e-commerce platforms, logistics, payment, and more. (+170 integrations in one place) All that with a single contract.

After a customer purchases the product from Olist Store a seller gets notified to fulfill that order. Once the customer receives the product, or the estimated delivery date arrives, the customer receives a satisfaction survey by email where they can leave a note about the purchase experience and add comments.

Olist offers a subscription model to the ERP system so the sellers can get their work done without distraction (SaaS) by offering invoice issuance (NF-e), synchronizing multi-channel inventory control, and unifying point-of-sale (PDV) systems with shipping carriers. Their revenue model builds on software subscriptions alongside transactional commission fees per order.

---
## 🔗 Project Assets & Downloads

## 🔗 Project Assets & Data Sources

* 📊 **Power BI Dashboard (.pbix):** [Download Interactive Dashboard via Google Drive](https://drive.google.com/drive/folders/1mI6H7bPzAvfkC-qdHtKD7bSKI1EHXoFC?usp=drive_link)
* 💾 **Official Dataset:** [Brazilian E-Commerce Public Dataset by Olist on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

##  What We Found

### 1. Monetization & Financial Overview
* **Platform Revenue & Monetization:** Total platform revenue reached ~$3.73M across 2017–2018, representing a ~27.45% monetization rate (Take Rate) on total GMV. This reflects Olist's core commission structure and service fees, rather than pure product markup.
* **Peak Seasonal Performance:**
  * **November 2017 (Black Friday):** Achieved peak monthly revenue driven by high-volume seasonal discounts.
  * **December 2017 & January 2018:** December generated strong holiday sales (~744K), followed by January (~950K) driven by the Brazilian summer holiday season and "Back-to-School" demand (school supplies and electronics).

---

### 2. Payment Dynamics & Optimization
* **Credit Cards (Primary Revenue Driver):** Account for ~78% of transactions. Brazilian consumers heavily prefer credit card installment plans to avoid immediate liquidity outflow.
  * **Actionable Insight:** Negotiate better payment gateway terms and expand interest-free installment options (e.g., 10–12 installments) to directly increase Average Order Value (AOV).
* **Boleto Bancário (Cash Payments):** Represents ~20% of orders. Boleto processing introduces a 1- to 3-day approval delay before merchant fulfillment. However, it maintains a low cancellation rate (~12%), proving it is a reliable segment for cash-preferred buyers.
* **Voucher Cancellations & Cart Transparency:** Vouchers represent the second highest cancellation factor. This is largely driven by checkout discrepancies (e.g., discount not applying to freight costs).
  * **Actionable Insight:** Improve cart checkout transparency, auto-restock vouchers upon cancellation, and restrict compensation vouchers to High-SLA / VIP Sellers to safeguard customer lifetime value (CLV).

---

### 3. Operational Disruptions & Macro Events
* **External Shock (March – May 2018):** The sharp increase in late deliveries and corresponding drop in review scores were primarily caused by the Brazilian Truckers' Strike (a severe national logistics shock) rather than internal operational failure.

---

### 4. Strategic Supply Chain & Logistics Recommendations
* **Targeted Fulfillment Hub in Rio de Janeiro (RJ):**
  * **Data-Backed Rationale:** RJ represents the 2nd largest order volume state, but suffers from a 11% late delivery rate and an average delivery time of 15 days.
  * **Strategic Action:** Establish a localized Regional Fulfillment Hub in RJ to compress lead times, reduce freight costs (currently ~$305K across categories), and significantly boost customer ratings.
* **Capital Allocation & Outer States Strategy:**
  * Avoid establishing physical fulfillment hubs in low-density northern/remote states, as fixed CapEx would outweigh order revenue. Rely instead on 3PL carriers and dynamic SLA buffering.
* **Enterprise Risk & Crisis Management (SLA Buffer):**
  * Implement an internal Crisis Response Protocol & Dynamic SLA Algorithm. Automatically extend promised delivery dates during national logistics shocks to protect merchant ratings and manage customer expectations transparently.
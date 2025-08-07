# 📊 Sales Performance Analysis Report

## Executive Summary

This report presents a data-driven analysis of liquor sales over a twelve-month period, focusing on trends in purchasing behavior, product preferences, vendor/store performance, and pricing sensitivity. Key findings highlight revenue peaks in March and June, consistent mid-volume purchasing patterns, and strong brand concentration within specific price ranges. Behavioral and operational recommendations are provided to optimize future marketing, pricing, and stock strategies.

---
## Deep-Dive

This report presents an analysis of **$428.12M** in liquor sales across twelve months, aiming to identify key performance trends, product behaviors, and consumer preferences. The following summarizes the most significant findings:

- **Sales peaks occurred in March ($36.65M)** and **June ($38.89M)**, correlating with increased transaction volume (**260K+ invoices** per month). These peaks reflect heightened demand periods rather than isolated high-value purchases.
    
- On average, customers purchased **11.9 bottles per invoice**, with **54.5%** of invoices containing between **9–10.5 liters** of alcohol. This points to a consistent **behavioral saturation threshold**, where most customers appear to stop purchasing based on volume rather than price. Recognizing this intuitive decision-making pattern enables tailored strategies such as volume-based promotions, “just enough” bundle packs, and product groupings that align with natural consumer limits.
    
- The **top 10 SKUs** includes Tito’s Handmade Vodka, Captain Morgan, and Fireball Cinnamon. These products primarily fall within **750mL–1.5L bottle sizes** and **packs of 6–12**, reinforcing a preference for mid-volume, value-oriented purchases.
    
- **Median bottle price was $13.49**, with the vast majority of units sold priced **under $50**. Sales volume dropped noticeably above this price point, indicating clear price sensitivity even without dynamic pricing data.
    
- **Top 10 stores** accounted for a dominant portion of total revenue, led by Hy-Vee #3, Central City 2, and Costco. Meanwhile, vendors such as **Diageo**, **Sazerac**, and **Jim Beam Brands** topped revenue rankings.
    
- Weekday transactions consistently outperformed weekend sales across all stores, suggesting habitual purchasing behavior, possibly tied to restocking or pre-weekend planning cycles.
    

The report concludes with operational recommendations based on observed customer behavior, pricing thresholds, and product clustering. Further insight can be obtained by incorporating promotion data, inventory history, and customer identifiers in future datasets.
## 1. Sales Trend Overview

Total monthly sales demonstrated a steady upward trend from January to June, peaking in **March ($36.65M)** and again in **June ($38.89M)**.

These surges align with corresponding increases in transaction volume, as evidenced by invoice counts, suggesting heightened overall demand rather than changes in spending per transaction.

From June towards December, a plunge was observed in July considering June was the peak. Figures in sales went gradually up towards December, while figures in invoice count experienced a dip in October, rising towards December anyways.

![[Pasted image 20250807145103.png]]

Further analysis of sales distribution by days of the week reveals **stronger performance during weekdays** compared to weekends. This consistent pattern throughout the months suggests habitual, possibly pre-event or stock-up purchases, rather than spontaneous weekend buying behavior.

![[Pasted image 20250807145033.png]]

+**Actions to take:** Inventory planning and workforce scheduling should align with weekday demand cycles and high-performing months. More specific insight regarding seasons and campaigns from sales required to strategically plan discounts during peak seasons/holidays for next year.

---
## 2. Product Preference Insights & Behavioral Patterns

The majority of purchases occur within **medium-range product sizes**, specifically bottles between **750mL and 1.5L**, sold in **packs of 6–12**. This indicates a dominant preference for convenience-sized units that offer perceived value without excess.

A secondary cluster of high sales volume is observed in **1.75L bottle formats**, with minimal activity between **1.25L and 1.5L**. This indicates a **bimodal consumer preference**, where buyers either opt for **standard-sized formats** (750–1000mL) or **bulk-oriented purchases** (1.75L). Records of bulk-buyers should be looked into further to gain insight on the behavior of this particular group.

![[Pasted image 20250807145505.png]]

**SKU-level analysis** of top-performing products revealed that:

- **Tito’s Handmade Vodka** remained a consistent leader in sales (~28%)
    
- Products such as **Black Velvet**, **Captain Morgan**, and **Fireball Cinnamon** also ranked among the top sellers

![[Pasted image 20250807152909.png]]

**Purchasing volumes per invoice** indicate strong clustering:

- 54.5% of customers purchased **9–10.5L **
    
- 15.27% purchased **4.5L**
    
- ~30% purchased between **750mL and 1.5L**

![[Pasted image 20250807153803.png]]

**Interpretation:**

The product analysis reveals a **clear pattern of consumer restraint**, driven not just by price but by perceived volume. While customers predominantly purchase **750–1000mL bottles in packs of 6–12**, invoice-level data shows that **over 54.5%** of transactions total between **9–10.5L** of alcohol. This suggests a **behavioral saturation point** — customers appear to stop purchasing when they feel they’ve “reached enough,” regardless of additional options or deals available.

This volume-based heuristic is further supported by the scarcity of purchases beyond 10.5L, despite the availability of larger packs or higher volumes. Such behavioral regularity offers a strategic opportunity to design promotions, shelf arrangements, and product bundles that align with how customers **intuitively measure sufficiency**, rather than relying solely on pricing incentives.

---
## 3. Store and Vendor Performance

### 🏪 Store-Level Performance

![[Pasted image 20250807160654.png]]

Sales analysis across key store locations indicates that performance is highly concentrated among a few dominant outlets:

- **Central City 2** led all locations with **$12.10M in sales**, contributing **32.18%** of total tracked store revenue
    
- **Hy-Vee #3 / Des Moines** followed closely at **$12.26M**, accounting for **29.41%**
    
- **Costco Wholesale #788 / WDM** contributed **$4.70M** (12.18%)
    
- Remaining key contributors include:
    
    - **Hy-Vee Wine and Spirits / Iowa City** – $5.45M (15.86%)
        
    - **Wilkie Liquors** – $4.01M (11.15%)
        
    - **Sam’s Club 8162 / Cedar Rapids** – $3.69M (10.16%)
        

Monthly trends show:

- **Hy-Vee #3** and **Central City 2** consistently drove monthly performance, with **notable surges in March, June, and December**
    
- **Costco** and **Sam’s Club** displayed seasonal variability, with higher performance in mid-year months such as **June and July**
    
- **Wilkie Liquors** and **Benz Distributing**, while lower in absolute sales, maintained steady contributions across all months
    

**Interpretation:** The bulk of revenue is generated by just two locations, which together represent **over 60%** of total store-linked sales in the dataset.

**Recommendation:**

- Prioritize **Central City 2** and **Hy-Vee #3** for in-store promotions, new product launches, and operational optimization
    
- Investigate what differentiates these top performers (e.g., customer demographics, layout, stock variety) to apply winning practices across other stores
    
- Leverage **Costco** and **Sam’s Club** for targeted seasonal campaigns, especially in Q2 and Q4 where sales increase
### 🤝 Brand-Level Vendor Performance

![[Pasted image 20250807155515.png]]

Analysis of sales by brand reveals that **DIAGEO AMERICAS** dominated with **$84.71M in sales**, representing **31.09%** of total revenue. This was followed by:

- **SAZERAC COMPANY INC** – $52.33M (19.21%)
    
- **Jim Beam Brands** – $32.05M (11.76%)
    
- **Heaven Hill Brands** – $27.02M (9.92%)
    
- **PERNOD RICARD USA** – $26.43M (9.70%)
    
- **FIFTH GENERATION INC** – $25.98M (9.54%)
    
- **BACARDI USA INC** – $23.90M (8.77%)
    

Monthly breakdowns show that:

- **SAZERAC** maintained steady performance across the year, often leading month-to-month
    
- **DIAGEO** surged strongly in the second half of the year
    
- Other vendors (e.g., **FIFTH GENERATION INC**) showed intermittent spikes, contributing to monthly peaks
    

This distribution reflects both consistent vendor loyalty and brand-driven purchasing behavior.

**Recommendation:** Strengthen partnerships with top 3 vendors (DIAGEO, SAZERAC, Jim Beam), who together account for over **60% of annual sales**. Vendors showing seasonal surges may be candidates for **targeted promotions or product launches** during key months.

---
## 4. Pricing Behavior

Sales distribution across price ranges illustrates a clear concentration below the **$50** threshold, with the **$10–$30** band accounting for the majority of units sold. The **median bottle price** was **$13.49**, reinforcing the value-driven nature of purchasing behavior.

![[Pasted image 20250807145850.png]]

![[Pasted image 20250807145917.png]]

While direct analysis of price elasticity was not feasible due to static pricing, customer sensitivity to price ceilings is evident. Sales volume drops significantly past the $50 mark.

**Recommendation:** Optimize pricing strategies by positioning products at psychologically appealing thresholds (e.g., $39.99, $49.99), and consider volume-based pricing bundles that remain under $100.

---
## 5. Data Gaps and Future Recommendations

To expand analytical depth and enable more precise targeting, several data enhancements are recommended:

|Data Type|Purpose|
|---|---|
|**Customer-level IDs**|Track loyalty, purchase frequency, and segmentation|
|**Promotion/event flags**|Correlate sales peaks with external campaigns|
|**Inventory levels**|Evaluate sell-through rates and prevent stockouts|
|**Seasonal or event calendar**|Clarify causes of March and June peaks|
|**Dynamic pricing logs**|Enable price elasticity modeling and promo ROI analysis|

**Next Step:** Initiate tracking of promotion timelines, customer identifiers, and in-store execution factors to unlock more actionable insights in future cycles.

<p align = 'center'>
<img src="assets/elevate_retail_logo_github3.jpg" alt="shopping cart as logo header_image" width='300' height='300'>

<h1 align="center">Elevate Commerce Sales and Profitability Analysis</h1>
<h2 align="center">Client Background</h2>

Elevate Commerce is a small to mid-sized retail company offering a diverse range of products across categories such as furniture, technology, and office supplies. The company serves multiple customer segments, including Consumer, Corporate, and Home Office.

The analysis is based on a multi-year dataset spanning **2016–2019**, including approximately **5,000** customers and over **10,000** transactions across multiple regions and product categories. The company has demonstrated steady revenue growth over this period, surpassing **$1M** in annual revenue by 2019.

<h2 align="center">Business Objective</h2>

As the business continues to grow, leadership is focused on improving overall performance by better understanding sales trends, pricing strategies, and profitability drivers.

Reporting to the Marketing Director, this analysis evaluates sales performance and identifies key drivers of profitability across product categories and regions. The findings provide actionable insights that cross-functional teams can leverage to streamline processes and enhance overall sales performance. The key insights and recommendations focus on the following areas:

 - **Revenue – Measures overall sales performance across regions and product categories.**
- **Profit – Evaluates the actual financial gain generated from sales.**
- **Profit Margin – Assesses efficiency by comparing profit relative to revenue.**
- **Discount – Analyzes the impact of pricing strategies on profitability.**
- **Product Performance – Evaluates performance at the category and sub-category level to identify high and low performers.**
- **Regional Performance – Compares revenue and profit across regions to identify geographic opportunities and risks.**

<br>

<h2 align="center">Executive Summary</h2>

<img width="1182" height="502" alt="revenue_peaks_2019_image" src="https://github.com/user-attachments/assets/dff550aa-eaef-4ea5-b7c2-2acfd81bcdc1" />


### Key Findings and Insights
### 1. Revenue Growth and Performance Trends
- Revenue shows a clear upward trend from 2016 to 2019, with stronger performance in later years.  
- Peak revenue occurs toward the end of the timeline, reflecting sustained business growth.  
- Short-term fluctuations suggest the influence of seasonal demand patterns.  

### 2. Order Volume Trends
- Order volume increases steadily over time, especially from 2018 onward.  
- Growth in revenue closely aligns with rising order counts, indicating higher transaction activity.  
- Recurring peaks, especially in Q4, reflect consistent seasonal purchasing behavior around the holiday season.  

### 3. Customer Spending Behavior
- Average order value (AOV) remains relatively stable throughout the period.  
- Occasional spikes are brief and infrequent, implying limited change in spending patterns.  
- This suggests that revenue growth is primarily driven by overall increased order volume rather than higher spend per transaction.  

### 4. Profitability Considerations
- While revenue and order volume grow consistently, profitability varies across time and conditions.  
- Discounting appears to influence profit outcomes, particularly at higher discount levels.  
- This suggests that growth does not always translate directly into improved financial performance.  

<h2 align="center">Dataset Overview</h2>

The dataset consists of synthetic but realistically structured transactional retail sales data designed to simulate real-world business operations and purchasing behavior. It includes orders, customers, and product-level details across multiple regions and time periods, with key fields such as revenue, profit, discount, order date, product category, and regional attributes to support analysis of sales performance and profitability drivers.

The following files and the Entity Relationship Diagram (ERD) are associated with this project:

- **Dataset**: [`National_Retail_Sales`](National_Retail_Sales.xlsx)
- **Data Dictionary**: [`Retail_Sales_Data_Dictionary`](Retail_Sales_Data_Dictionary.xlsx)

<img width="912" height="501" alt="erd_image" src="https://github.com/user-attachments/assets/62982144-3f37-4c4b-96e2-4c063af86ab8" />

<h2 align="center">Sales Trend</h2>

This section highlights overall sales performance across revenue, order volume, and average order value (AOV), helping identify growth patterns and key business drivers over time.

<img width="1187" height="440" alt="sales_trend_image" src="https://github.com/user-attachments/assets/c840a2c7-f75b-4e3d-bd37-8f2df4d3a264" />

<br>

These charts show how growth has evolved and what factors are driving performance.

| Key Findings | Business Insights |
|------------------|----------------------|
| • Revenue increased steadily from 2016 to 2019, exceeding the historical average in 2019.<br>• Peak monthly revenue **(~$876K)** occurs toward the end of the period.<br>• A temporary dip after 2016 is followed by a strong recovery in 2017. | • The business shows sustained growth with stronger performance in later years.<br>• The quick recovery after 2016 suggests retail resilience rather than structural weakness. |
| • Order volume rose significantly, reaching a peak of **632** orders.<br>• Revenue and order volume trends closely align.<br>• Quarterly patterns show dips followed by recoveries. | • Growth is primarily driven by increased transaction volume rather than pricing.<br>• Demand shows cyclical pattern that should be considered in planning. |
| • AOV remains relatively stable, averaging **$3,692**.<br>• Occasional spikes **(~$6,314)** appear temporary rather than indicative of sustained growth..<br>• No consistent upward or downward trend during this timeframe. | • Customer spend per order has remained largely unchanged.<br>• Revenue growth is not driven by higher-value transactions. |
| • Revenue and order volume show recurring fluctuations, with stronger performance in 2018–2019.<br>• Declines are short-lived and followed by recovery. | • Later-year improvements suggest stronger demand or improved business operational efficiency.<br>• Short-term variability does not indicate long-term risk. |

<br>

This section evaluates sales representative performance against yearly revenue goals and the 80% performance threshold. The 2017 view (filtered by top 15 sales reps) provides a representative snapshot of both above-goal and below-goal performers, while broader trends from 2016–2019 indicate gradual improvement in overall sales execution over time.

<img width="1187" height="443" alt="sales_reps_goal_image" src="https://github.com/user-attachments/assets/1e8406ad-f2c9-4ec1-af7c-045c732a197a" />

<br>

The chart highlights variation in sales performance across representatives, with blue bars representing above-goal performers and red bars representing below-goal performers.

| Key Findings | Business Insights |
|---|---|
| • Several sales representatives exceeded both yearly revenue goals and the 80% target threshold.<br>• A mix of above-goal (blue) and below-goal (red) performers indicates uneven sales performance across the team.<br>• Higher-performing representatives generated substantially greater revenue contributions than lower-performing peers. | • Revenue growth appears increasingly supported by stronger sales execution and improved goal attainment over time.<br>• Performance differences across representatives suggest opportunities for coaching, mentoring, and incentive alignment.<br>• Consistent success among top performers may reflect effective sales strategies that can be replicated across the broader team. |


<br>
While sales performance shows strong growth, the next section shifts focus to profitability, and the factors that affect the profit performance.

<h2 align="center">Profit Trend</h2>

<img width="1187" height="415" alt="APO_top_bottom_5_sub-categories_image" src="https://github.com/user-attachments/assets/cf9e8553-d8fe-48eb-904b-79e722a56b3e" />

<br>

| Key Findings | Business Insights |
|-------------|----------|
| **Copiers (~$6K APO)** is a clear top-performing performer, with **Machines (~$2.4K)** also significantly higher than all other categories. | Profitability is **highly concentrated**, with Copiers and Machines driving strong per-order returns. |
| Most categories (**Chairs, Phones, Accessories, Binders, Appliances, Storage, Bookcases, Paper, Envelopes**) show **low APO (generally <$500)**. | Most categories contribute **lower per-order profit**, indicating a wide gap in performance. |
| High-margin sub-categories include **Labels, Paper, Envelopes, Copiers, and Fasteners**. | There is a contrast dividing between **high-margin categories** and others, highlighting performance imbalance. |
| Loss-making sub-categories include **Supplies, Tables, Bookcases, Storage, and Chairs** (down to ~-20%). | Categories like **Chairs, Storage, and Bookcases** show **consistent underperformance** across metrics. |

<br>

<img width="1187" height="468" alt="revenue_profit_quadrant_image" src="https://github.com/user-attachments/assets/5c5987a7-608e-488c-b42f-87c4b8aa054f" />

<br>

**Insights**
- **Top Performers** (**Binders, Phones, Accessories, Appliances**) generate both high revenue and high profit, making them the strongest contributors to overall performance.  
- **Growth Potential** categories (**Copiers, Paper**) show strong profit but comparatively lower revenue, indicating opportunity for expansion.  
- **Need Attention** categories (**Tables, Storage**) generate relatively high revenue but lower profit, suggesting margin inefficiencies.  
- **Underperformers** (**Supplies, Fasteners, Art**) contribute low revenue and low profit, limiting overall impact.


<img width="1187" height="465" alt="image" src="https://github.com/user-attachments/assets/2a3d1a1d-7883-450f-a718-684bd7b03d6c" />

<br>

These visuals highlight how discount levels influence profit, revealing clear thresholds where profitability begins to decline.
<br>

| **Key Findings** | **Insights** |
|------------------------|----------------------------------------|
| • Profit declines as discount levels increase.<br>• Higher discount orders often result in reduced or negative profit.<br>• Profit compresses toward lower values at higher discount levels. | • Discounting is directly eroding margins.<br>• More sales at high discounts are not improving overall profitability.<br>• Profit becomes less consistent as discounts increase. |
| • Break-even occurs around **~25–30%** discount.<br>• Average profit turns negative beyond this range.<br>• This threshold is consistent across discount bins. | • Discounts above **~25–30%** are not sustainable.<br>• This acts as a practical cutoff for pricing decisions.<br>• Staying below this level helps protect margins. |
| • Peak average profit occurs within the **~5–10%** discount range.<br>• Moderate discounts generate the highest average returns.<br>• Profit declines outside this range. | • There is a clear “sweet spot” for discounting.<br>• Small discounts help drive sales without hurting profit.<br>• Pricing should stay within this range when possible. |
| • High discount levels (>35%) frequently result in losses.<br>• Many orders fall below the profit baseline in this range.<br>• A “high discount risk zone” is labelled in heavily discounted transactions. | • High discounts carry clear financial risk.<br>• Revenue at these levels is not translating into profit.<br>• Reducing these transactions would likely improve performance. |
| • Individual high-profit orders (e.g., **~$45K**) exist but are infrequent.<br>• Profit distribution is skewed by a small number of outliers.<br>• Most orders cluster around lower profit values. | • A few large orders are inflating results but are not typical.<br>• Average performance is a better indicator than extremes.<br>• Decisions should focus on consistent, repeatable outcomes. |

<img width="1187" height="521" alt="segment_and_region_charts_image" src="https://github.com/user-attachments/assets/0319707c-3057-41c4-a61b-23194bceb614" />

<br>

**Insights**
- **Corporate** and **Consumer** segments show improvement in profit margin from 2016 to 2019, while **Home Office** experiences a slight decline.  
- Profit margins across regions are relatively consistent, though variability exists within each region.  
- **Labels** consistently appear as high-margin outliers, while **Supplies** and **Tables** represent the lowest margin points across regions.

<br>
<h2 align="center">Conclusion</h2>

This analysis highlights that while Elevate Commerce demonstrates strong overall sales growth, profitability and performance are influenced by a combination of pricing strategy, category performance, discount behavior, and sales representative performance.

Revenue and order volume increase steadily from 2016 to 2019, while average order value remains relatively stable, indicating that growth is primarily driven by increased transaction activity rather than higher spending per order. Profitability analysis further shows that a small group of high-performing categories contributes disproportionately to overall profit, while several lower-performing categories continue to underperform.

Discount analysis reveals that profitability declines significantly beyond the ~25–30% discount threshold, emphasizing the importance of pricing discipline. In addition, sales representative performance improves progressively over time, with stronger goal attainment contributing to sustained revenue growth in 2018-2019.

Overall, the business demonstrates strong growth potential, but long-term profitability will depend on balancing sales growth with pricing optimization, category management, and consistent sales execution.

<br>
<h2 align="center">Strategic Recommendations</h2>

- **Prioritize high-performing categories**: Continue investing in top-performing categories such as Binders and Phones to sustain strong revenue and profitability.

- **Optimize discount strategy**: Maintain discounts within the 5–10% range and avoid exceeding ~25–30% to protect profit margins and reduce margin erosion. 

- **Expand growth-potential categories**: Increase visibility and targeted promotion for categories such as Copiers and Paper that demonstrate strong profitability potential, with a stronger focus on the high APO sub-categories (Copier and Machines).

- **Improve underperforming categories:** Reevaluate low-performing products such as Fasteners and Appliances through pricing adjustments, bundling, or potential discontinuation.

- **Address “Need Attention” categories:** For high-revenue but low-profit items like Tables, explore cost reduction, pricing optimization, or value-added offerings to improve margins.

- **Leverage product bundling and cross-selling:** Pair underperforming items with high-performing products to increase overall basket value and improve profitability.

- **Strengthen sales execution**: Expand coaching, mentoring, and performance-sharing initiatives to improve consistency across sales representatives.

- **Implement performance incentives**: Introduce incentive programs tied to revenue growth and goal attainment to encourage stronger sales performance and sustained operational growth.






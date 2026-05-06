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
- Recurring peaks, especially in Q4, highlight consistent seasonal purchasing behavior around the holiday season.  

### 3. Customer Spending Behavior
- Average order value (AOV) remains relatively stable throughout the period.  
- Occasional spikes are not sustained, indicating limited change in spending patterns.  
- This suggests that revenue growth is primarily driven by increased order volume rather than higher spend per transaction.  

### 4. Profitability Considerations
- While revenue and order volume grow consistently, profitability varies across time and conditions.  
- Discounting appears to influence profit outcomes, particularly at higher discount levels.  
- This suggests that growth does not always translate directly into improved financial performance.  

<h2 align="center">Dataset Overview</h2>

The dataset consists of synthetic but realistically structured transactional retail sales data designed to simulate real-world business operations and purchasing behavior. It includes orders, customers, and product-level details across multiple regions and time periods, with key fields such as revenue, profit, discount, order date, product category, and regional attributes to support analysis of sales performance and profitability drivers.

The following files are associated with this project:

- **Dataset**: [`National_Retail_Sales`](National_Retail_Sales.xlsx)
- **Data Dictionary**: [`Retail_Sales_Data_Dictionary`](Retail_Sales_Data_Dictionary.xlsx)

<img width="912" height="501" alt="erd_image" src="https://github.com/user-attachments/assets/62982144-3f37-4c4b-96e2-4c063af86ab8" />

<h2 align="center">Sales Trend</h2>

This section highlights overall sales performance across revenue, order volume, and average order value (AOV), helping identify key growth patterns and the primary drivers of business performance over time.

<img width="1187" height="440" alt="sales_trend_image" src="https://github.com/user-attachments/assets/c840a2c7-f75b-4e3d-bd37-8f2df4d3a264" />

<br>

These charts show how growth has evolved and what factors are driving performance.

| Key Findings | Business Insights |
|------------------|----------------------|
| • Revenue increased steadily from 2016 to 2019, exceeding the historical average in 2019.<br>• Peak monthly revenue (~$876K) occurs toward the end of the period.<br>• A temporary dip after 2016 is followed by a strong recovery in 2017. | • The business shows sustained growth with stronger performance in later years.<br>• The quick recovery after 2016 suggests resilience rather than structural weakness. |
| • Order volume rose significantly, reaching a peak of 632 orders.<br>• Revenue and order volume trends closely align.<br>• Quarterly patterns show dips followed by recoveries. | • Growth is primarily driven by increased transaction volume rather than pricing.<br>• Demand shows cyclical behavior that should be considered in planning. |
| • AOV remains relatively stable, averaging $3,692.<br>• Occasional spikes ($6,314) are not sustained.<br>• No consistent upward or downward trend is observed. | • Customer spend per order has remained largely unchanged.<br>• Revenue growth is not driven by higher-value transactions. |
| • Revenue and order volume show recurring fluctuations, with stronger performance in 2018–2019.<br>• Declines are short-lived and followed by recovery. | • Later-year improvements suggest stronger demand or improved execution.<br>• Short-term variability does not indicate long-term risk. |

While sales performance shows strong growth, the next section shifts focus to profitability, and the factors that affect the profit performance.

<h2 align="center">Profit Trend</h2>

<img width="1187" height="400" alt="APO_top_bottom_5_sub-categories_image" src="https://github.com/user-attachments/assets/e598560e-61ff-490b-84fb-30b66b6107aa" />

<br>

| Key Findings | Business Insights |
|-------------|----------|
| **Copiers (~$6K APO)** is a clear outlier, with **Machines (~$2.4K)** also significantly higher than all other categories. | Profitability is **highly concentrated**, with Copiers and Machines driving strong per-order returns. |
| Most categories (**Chairs, Phones, Accessories, Binders, Appliances, Storage, Bookcases, Paper, Envelopes**) show **low APO (generally <$500)**. | Most categories contribute **lower per-order profit**, indicating a wide gap in performance. |
| High-margin sub-categories include **Labels, Paper, Envelopes, Copiers, and Fasteners**. | There is a clear divide between **high-margin categories** and others, highlighting performance imbalance. |
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
| • Break-even occurs around ~25–30% discount.<br>• Average profit turns negative beyond this range.<br>• This threshold is consistent across discount bins. | • Discounts above ~25–30% are not sustainable.<br>• This acts as a practical cutoff for pricing decisions.<br>• Staying below this level helps protect margins. |
| • Peak average profit occurs within the ~5–10% discount range.<br>• Moderate discounts generate the highest average returns.<br>• Profit declines outside this range. | • There is a clear “sweet spot” for discounting.<br>• Small discounts help drive sales without hurting profit.<br>• Pricing should stay within this range when possible. |
| • High discount levels (>35%) frequently result in losses.<br>• Many orders fall below the profit baseline in this range.<br>• A “high discount risk zone” is observed in heavily discounted transactions. | • High discounts carry clear financial risk.<br>• Revenue at these levels is not translating into profit.<br>• Reducing these transactions would likely improve performance. |
| • Individual high-profit orders (e.g., ~$45K) exist but are rare.<br>• Profit distribution is skewed by a small number of outliers.<br>• Most orders cluster around lower profit values. | • A few large orders are inflating results but are not typical.<br>• Average performance is a better indicator than extremes.<br>• Decisions should focus on consistent, repeatable outcomes. |

<img width="1187" height="530" alt="segment_and_region_charts" src="https://github.com/user-attachments/assets/858da3e4-21ab-4096-846b-ed4794d6aad3" />

<br>

**Insights**
- **Corporate** and **Consumer** segments show improvement in profit margin from 2016 to 2019, while **Home Office** experiences a slight decline.  
- Profit margins across regions are relatively consistent, though variability exists within each region.  
- **Labels** consistently appear as high-margin outliers, while **Supplies** and **Tables** represent the lowest margin points across regions.

## Conclusion

This analysis highlights that while Elevate Commerce demonstrates strong sales performance, profitability is driven by a combination of pricing strategy, category performance, and discount behavior. However, profitability is uneven across categories, with a small number of high-performing categories driving a significant portion of profit, while several others underperform.

Analysis shows that discounting plays a critical role in profitability, with margins declining sharply beyond the ~25–30% threshold. While some categories generate strong per-order profit, others rely on lower-margin performance, highlighting an imbalance in the current product mix.

Overall, the business has a solid foundation for growth, but improving pricing strategies and optimizing category performance will be essential to sustaining long-term profitability.

## Strategic Recommendations

- **Prioritize high-performing categories**: Continue investing in top performers such as Binders and Phones to sustain strong revenue and profitability.

- **Optimize discount strategy**: Maintain discounts within the 5–10% range and avoid exceeding ~25–30% to protect margins.

- **Scale growth potential categories**: Expand categories like Copiers and Paper through targeted marketing and increased visibility.

- **Address underperforming categories**: Reevaluate low-margin categories such as Tables, Supplies, and Fasteners through pricing adjustments or cost optimization.

- **Focus on profitable growth**: Shift emphasis from volume-driven sales to margin-driven performance to ensure sustainable performance.

===
**Recommendations**
- **Invest in Top Performers** (**Binders, Phones, Accessories, Appliances**) to sustain growth and maximize returns.  
- **Expand Growth Potential categories** (**Copiers, Paper**) through targeted marketing, bundling, or increased visibility.  
- **Improve margins in Need Attention categories** (**Tables, Storage**) by reviewing pricing, discounting, and cost structure.  
- **Reevaluate Underperformers** (**Supplies, Fasteners, Art**) for cost reduction, repositioning, or potential phase-out.
-------------

## Strategic Recommendations

- **Prioritize high-performing categories:** Continue investing in top performers such as Binders and Phones to sustain revenue and profit growth.
- **Optimize discount strategy:** Maintain discounts within the ~5–10% range and avoid exceeding ~25–30% to protect margins and prevent losses.
- **Scale growth potential segments:** Expand categories like Copiers by increasing visibility, targeted promotions, or inventory to capture additional revenue.
- **Improve underperforming categories:** Reevaluate low-performing products such as Fasteners and Appliances through pricing adjustments, bundling, or potential discontinuation.
- **Address “Need Attention” categories:** For high-revenue but low-profit items like Tables, explore cost reduction, pricing optimization, or value-added offerings to improve margins.
- **Leverage product bundling and cross-selling:** Pair underperforming items with high-performing products to increase overall basket value and improve profitability.
- **Focus on operational efficiency:** As growth is driven by volume rather than pricing, improving fulfillment, inventory management, and conversion rates will be critical to scaling profitably.

---

**Overall Insight:**  
Elevate Commerce demonstrates scalable growth driven by increased customer activity, with consistent pricing dynamics supporting stable revenue expansion.



Further analysis indicates that discounting, product category performance, and customer segmentation play key roles in driving profitability. These findings highlight opportunities to optimize pricing strategies and focus on high-performing segments to sustain long-term growth.

## Objective of the Analysis

This analysis was conducted to evaluate sales performance and identify key factors impacting profitability. The goal is to provide actionable insights into revenue trends, discount strategies, and customer segment behavior to support more informed business decisions and improve overall financial performance.

## Insights

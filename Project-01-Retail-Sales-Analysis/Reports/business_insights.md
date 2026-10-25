# Retail Sales Analysis

## Business Insights & Recommendations

**Project:** Retail Sales & Customer Analysis Using Python and Pandas\
**Dataset:** Sample Superstore\
**Analysis tools:** Python, Pandas, NumPy, Jupyter Notebook

------------------------------------------------------------------------

## 1. Executive Summary

This report summarizes an analysis of retail orders, sales, profit,
products, regions, customers, monthly sales patterns, and discount
groups.

The dataset contains **\$2,297,200.86 in sales** and **\$286,397.02 in
profit**, with an overall profit margin of **12.47%**. Across **5,009
distinct orders** and **793 unique customers**, performance varies
considerably by category, region, product, and discount group.

The most notable findings are: - **Technology** has the highest sales
and total profit among the three product categories. - The **West**
region has the highest sales, highest profit, and highest regional
profit margin. - **Furniture** has the lowest total profit among the
categories. - **November** has the highest aggregated sales across all
years, while **February** has the lowest. - The high-discount group has
negative total profit in this analysis, while the no-discount and
low-discount groups have positive total profit. - Several products have
substantial negative total profit and warrant further investigation.

> **Interpretation note:** These are descriptive findings from the
> available dataset. They show patterns and associations; they do not
> establish that a factor, such as discounting, caused a particular
> business outcome.

## 2. Overall Business Performance

  Metric                            Result
  ----------------------- ----------------
  Total Sales               \$2,297,200.86
  Total Profit                \$286,397.02
  Distinct Orders                    5,009
  Unique Customers                     793
  Overall Profit Margin             12.47%

**Insight:** The dataset records positive total profit overall, with a
profit margin of 12.47% when calculated as total profit divided by total
sales.

**Recommendation:** Track sales, profit, and profit margin together.
Sales growth alone may not indicate improved business performance if the
additional sales are not profitable.

## 3. Product Category Performance

  Category             Total Sales   Total Profit
  ----------------- -------------- --------------
  Technology          \$836,154.03   \$145,454.95
  Furniture           \$741,999.80    \$18,451.27
  Office Supplies     \$719,047.03   \$122,490.80

**Key findings** - Technology leads both total sales and total profit. -
Furniture has the lowest total profit, despite having higher sales than
Office Supplies. - Office Supplies generates more total profit than
Furniture on lower total sales.

**Recommendations** - Review Furniture products, pricing, discounting,
and costs to understand why its total profit is comparatively low. -
Investigate the product and customer mix behind Technology's stronger
results. - Compare category-level profit margins as well as total profit
before making investment or inventory decisions.

## 4. Regional Performance

  Region       Total Sales   Total Profit   Profit Margin
  --------- -------------- -------------- ---------------
  West        \$725,457.82   \$108,418.45          14.94%
  East        \$678,781.24    \$91,522.78          13.48%
  South       \$391,721.90    \$46,749.43          11.93%
  Central     \$501,239.89    \$39,706.36           7.92%

**Key findings** - West has the highest total sales, total profit, and
regional profit margin. - Central has the lowest regional profit margin
at 7.92% and the lowest total profit. - South has the lowest sales among
the four regions.

**Recommendations** - Examine Central's product mix, discount levels,
and order profitability to identify opportunities for improvement. -
Study the West region's product and customer mix to identify practices
that may be useful elsewhere. - Investigate the South region's lower
sales separately from its profitability; lower sales alone do not
explain the cause.

## 5. Product Profitability: Products with the Lowest Total Profit

The ten products with the lowest aggregated profit in the notebook are
listed below.

  -----------------------------------------------------------------------
  Product                           Total Sales              Total Profit
  ------------------- ------------------------- -------------------------
  Cubify CubeX 3D                   \$11,099.96               -\$8,879.97
  Printer Double Head                           
  Print                                         

  Lexmark MX611dhe                  \$16,829.90               -\$4,589.97
  Monochrome Laser                              
  Printer                                       

  Cubify CubeX 3D                    \$7,999.98               -\$3,839.99
  Printer Triple Head                           
  Print                                         

  Chromcraft                         \$9,917.64               -\$2,876.12
  Bull-Nose Wood Oval                           
  Conference Table                              

  Bush Advantage                     \$9,544.73               -\$1,934.40
  Collection                                    
  Racetrack                                     
  Conference Table                              

  GBC DocuBind P400                 \$17,965.07               -\$1,878.17
  Electric Binding                              
  System                                        

  Cisco TelePresence                \$22,638.48               -\$1,811.08
  System EX90                                   
  Videoconferencing                             

  Martin Yale                       \$16,656.20               -\$1,299.18
  Chadless Opener                               
  Electric Letter                               
  Opener                                        

  Balt Solid Wood                    \$6,518.75               -\$1,201.06
  Round Tables                                  

  BoxOffice By Design                \$1,706.25               -\$1,148.44
  Rectangular and                               
  Half-Moon                                     
  Conference Table                              
  -----------------------------------------------------------------------

*Some product names are shortened for readability.*

**Key finding:** The products listed above have negative total profit.
The Cubify CubeX 3D Printer Double Head Print has the lowest total
profit in this result, at -\$8,879.97.

**Recommendations** - Review product-level discounts, pricing, costs,
and order history for these products. - Check whether losses are
concentrated in particular regions or customer segments. - Do not
discontinue a product based on this table alone; review demand,
strategic importance, and the underlying cost data first.

## 6. Monthly Sales Trend

Monthly sales are aggregated by calendar month across all years in the
dataset.

  Month          Total Sales
  ----------- --------------
  January        \$94,924.84
  February       \$59,751.25
  March         \$205,005.49
  April         \$137,762.13
  May           \$155,028.81
  June          \$152,718.68
  July          \$147,238.10
  August        \$159,044.06
  September     \$307,649.95
  October       \$200,322.98
  November      \$352,461.07
  December      \$325,293.50

**Key findings** - November has the highest aggregated monthly sales at
\$352,461.07. - February has the lowest aggregated monthly sales at
\$59,751.25. - September and December also have relatively high
aggregated sales.

**Recommendations** - Consider these patterns when planning inventory,
staffing, and promotions, after checking whether they are consistent
year by year. - Compare monthly sales by year before treating these
results as a recurring seasonal trend, because this table combines all
years.

## 7. Customer Analysis

### Customer base and purchasing frequency

  Metric                                    Result
  ----------------------------------- ------------
  Unique Customers                             793
  Average Total Sales per Customer      \$2,896.85
  Customers with 1 Order                        12
  Customers with 2--5 Orders                   317
  Customers with More Than 5 Orders            464

The purchase-frequency groups sum to 793 customers, matching the
unique-customer count.

**Key findings** - 464 customers placed more than five distinct
orders. - Emily Phan placed the highest number of distinct orders in the
notebook results: **17 orders**. - The customer with the highest total
sales is Sean Miller, with **\$25,043.05** in sales. - The customer with
the highest total profit is Tamara Chand, with **\$8,981.32** in profit.

**Recommendations** - Examine repeat-customer behavior to understand
which products and segments encourage repeat orders. - Consider
retention initiatives for valuable customers, while evaluating
profitability rather than sales alone. - Investigate customers with
negative total profit separately before deciding on pricing or service
changes.

## 8. Discount and Profit Analysis

  -----------------------------------------------------------------------
  Discount Group        Total Sales       Total Profit Average Profit per
                                                                      Row
  -------------- ------------------ ------------------ ------------------
  No Discount        \$1,087,908.47       \$320,987.60            \$66.90

  Low Discount         \$846,522.24       \$100,785.47            \$26.50
  (greater than                                        
  0% and up to                                         
  20%)                                                 

  High Discount        \$362,770.15      -\$135,376.06           -\$97.18
  (greater than                                        
  20%)                                                 
  -----------------------------------------------------------------------

**Key findings** - The no-discount group has the highest total profit in
this analysis. - The low-discount group has positive total profit. - The
high-discount group has negative total profit and a negative average
profit per dataset row.

**Recommendations** - Review orders with discounts above 20%, especially
where profit is negative. - Test discount rules against product, region,
customer segment, and order size before changing policy. - Compare
like-for-like orders and include costs and business objectives where
available. These grouped results alone do not prove that discounts
caused losses.

**Metric note:** "Average Profit per Row" is the mean of the `Profit`
values for records in each discount group; it is not average profit per
distinct order.

## 9. Priority Recommendations

Based on the results in this notebook, the following actions merit
further investigation:

1.  **Investigate high-discount losses.** Review the products and orders
    contributing to the high-discount group's negative total profit.
2.  **Review Furniture profitability.** Furniture generates substantial
    sales but much lower total profit than Technology and Office
    Supplies.
3.  **Examine Central region performance.** Central has the lowest
    regional profit margin in the analysis.
4.  **Review the lowest-profit products.** Check pricing, discounting,
    and cost drivers before making product-level decisions.
5.  **Plan with monthly trends carefully.** November has the highest
    aggregated sales and February the lowest; validate the pattern by
    year before treating it as seasonality.
6.  **Build on customer relationships.** Study repeat purchases and
    customer-level profitability to identify retention opportunities.
7.  **Monitor margin alongside revenue.** Track total sales, total
    profit, and profit margin together to avoid optimizing revenue at
    the expense of profitability.

## 10. Scope and Limitations

-   Findings are based on the dataset and the notebook outputs available
    for this project.
-   Monthly sales are combined across years, so the monthly comparison
    does not by itself prove a recurring seasonal pattern.
-   Discount groups are descriptive and do not establish causation.
-   The product table shows the ten lowest-profit products; it should be
    treated as a shortlist for investigation, not a complete root-cause
    analysis.
-   Additional cost, inventory, marketing, and operational data would be
    needed to validate the recommendations and explain underlying
    causes.

## 11. Conclusion

The analysis demonstrates how Python, Pandas, and NumPy can be used to
explore retail performance and convert transaction-level data into
business insights.

Technology and the West region lead on key performance measures, while
Furniture, the Central region, selected low-profit products, and the
high-discount group warrant further review. Monthly and customer-level
results also offer useful starting points for planning and retention
analysis.

The recommendations in this report are intended as evidence-based areas
for investigation, rather than claims about causes that the current
analysis cannot establish.

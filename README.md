# Superstore Sales & Profit — EDA

Exploratory Data Analysis of a Superstore sales dataset using Python and pandas, uncovering key drivers of profit performance across product categories, discounting, and time.

## Dataset
10,194 orders, 21 columns, spanning Jan 2023 – Dec 2026. No missing values.

## Key Findings

*1. Discounting hurts profit.*
Discount and Profit show a negative correlation (-0.22). Orders discounted above ~20-25% frequently become unprofitable — by 50% discount, average profit per order is -$310. One order (a 3D printer discounted 70%) lost $6,599 on its own.

*2. Furniture underperforms despite strong sales.*
Furniture generated $754K in sales but only $19.7K profit — far below Office Supplies ($126K profit) and Technology ($146.5K profit) on similar sales volume.

*3. Tables and Bookcases are losing money.*
Tables lost -$17,753 overall despite $208K in sales — the worst-performing sub-category. Bookcases (-$3,632) and Supplies (-$1,171) also ran at a loss. Tables carry a 25.8% average discount, versus just 15.7% for Copiers (the most profitable sub-category).

*4. Copiers, Phones, and Accessories are the most profitable sub-categories*, led by Copiers at $56K profit on $150K in sales.

*5. Sales grew significantly over time* (from ~$10-30K/month in 2023 to peaks over $100K/month by 2026), but profit stayed comparatively flat — revenue growth did not translate into proportional profit growth.

## Recommendation
Reassess discount policy on Tables and Bookcases — current discount levels appear to erase margin entirely on these product lines.

## Tools Used
Python, pandas, matplotlib, Jupyter Notebook

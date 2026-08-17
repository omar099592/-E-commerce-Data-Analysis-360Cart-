You're right, my bad — with only March 2025 in the dataset, "payday-driven monthly cycle" is an overreach since there's no second month to compare against. Let me fix that.

## 360Chart — E-Commerce Analytics 

### Introduction

End-to-End business intelligence project built on a real-world-style e-commerce dataset covering 180,593 orders from March 2025.

### Key Insights

- **Demand spikes early and late in the month** — order volume peaks on the 1st and 29th, with the 18th consistently the slowest day, suggesting a possible pay-cycle effect
   worth validating against additional months of data.
- **Revenue doesn't track volume evenly** — Electronics leads revenue ($19.31M) while Home & Kitchen moves a similar number of orders but generates 35% less revenue,
   pointing to pricing/discount differences worth investigating.
- **A churned/VIP AOV paradox** — churned and VIP customers have the highest average order value (~$290), meaning the business is losing high spenders despite strong basket
   sizes — a retention issue, not a pricing one.
- **Mobile-first behavior dominates** — 57.4% of orders come from mobile, with the Native App alone driving 47% of all orders, making app experience the highest-leverage
  investment area.
- **Cross-category return patterns** — top-returned products span unrelated categories, suggesting a shared root cause (likely listing/description accuracy) rather than
 isolated product issues.
- **Healthy pricing strategy** — 76% of orders are sold at low discount levels (0–15%), showing revenue isn't dependent on heavy promotions.
- 
## **Dashboard Overview** :

### Tools Used

- **Python (pandas)** — data cleaning, exploratory analysis, discount/cancellation/return analysis
- **Power BI** — interactive dashboard design
- **DAX** — custom measures (Net Revenue, hour-based groupings, etc.)
- **Power Query** — data transformation

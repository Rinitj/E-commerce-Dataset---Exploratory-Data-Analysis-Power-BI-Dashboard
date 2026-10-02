# Ecommerce Dataset, EDA & Power BI Dashboard

Picture this, You run an e commerce business and someone hands you a slide that says 99.98% of your orders get approved. You'd probably frame that slide. Ship it to investors. Call it a day.

Except nobody asked how long that approval actually takes.

That question, the one hiding right behind the good looking number, is basically the whole reason I built this project. I took a raw e commerce dataset and pushed it through Excel and Power BI until it stopped being rows and columns and started telling me where this business was actually winning, and where it was quietly bleeding time it didn't know it was losing.

## Business Questions Addressed

* **Category Performance:** Which product categories are actually driving sales and order volume, and is the business as diversified as it looks.
* **Payment Behavior:** Which payment methods dominate transaction value, and how concentrated is that reliance.
* **Geographic Demand:** Where is customer demand actually concentrated, and does shipping cost track with it.
* **Approval Speed vs Approval Rate:** Does a near perfect approval rate also mean a fast one, or is there a gap worth investigating.
* **Seasonal Trend:** How did monthly sales move across 2017 and 2018, and where did that trend break.

## Project Scope

* **Dashboard 1, Business Overview**: the version you'd show a founder. Sales, orders, category performance, payment behavior.
* **Dashboard 2, Customer & Operational Insights**: the version you'd show an operations lead. Geography, shipping, and the approval time problem hiding in plain sight.

## Tools & Methodology

* **Excel**: filtering, cleaning, sorting, getting close enough to the raw data to spot hiding issues.
* **Power Query**: shaping and prepping the data properly before modeling.
* **Power BI**: data modeling, DAX measures, and interactive dashboards.

## Dashboard 1: Business Overview

![Dashboard 1 Business Overview](Dashboard%20Screenshots/Dashboard_1_Business_Overview.png)

* **Toys dominated the business**: roughly **$9.8M in sales** off **28.7K orders**, close to **75% of everything sold**.
* **Credit cards ran the payment side**: **$7.52M**, or **73.35%** of total payment value.

## Dashboard 2: Customer & Operational Insights

![Dashboard 2 Customer Operational Insights](Dashboard%20Screenshots/Dashboard_2_Customer_Operational_Insights.png)

* **São Paulo drove 42% of all orders** (16.2K), with Rio de Janeiro and Minas Gerais pushing the top three states to **67% of total volume**. Three regions doing almost all the work.
* **São Paulo also led shipping cost**, around **$0.70M**, **41% of the total**, tracking directly with its order volume.
* **The real twist**: a **99.98% approval rate** looks flawless, until you see the average approval time sits at **628.45 minutes (about 10.5 hours)**, and **83% of orders** took longer than 12 hours. This business isn't losing customers at approval, however it is testing their patience.
* **Sales peaked around $1.2M in December 2017**, then turned choppier through 2018 It is a shift which should be questioned.

## Analysis Areas

* Sales performance across the business
* Product category performance
* Customer and geographic patterns
* Payment method distribution
* Shipping cost versus product weight
* Order approval time and processing
* Monthly and day of week ordering rhythm

## Skills Demonstrated

Data cleaning, exploratory analysis, dashboard design, data modeling, DAX, Power Query, Excel, Power BI, and the instinct to keep digging past a metric that looks fine on the surface.

## Repository Structure

```
Ecommerce-Dataset-EDA-Power-BI-Dashboard/
│
├── Dashboard Screenshots/
│   ├── Dashboard_1_Business_Overview.png
│   └── Dashboard_2_Customer_Operational_Insights.png
│
└── README.md
```

## Key Takeaway

The key insight of this project is the realty, hiding behind the good story.the 99.98% that's secretly a 10.5 hour problem, the toy category quietly running the show, the three states carrying a business that looks national but isn't. 
These isights are understanding the business rather than just reporting numbers. 

## Future Scope

* Segment customers by frequency and spend to find real high value repeat buyers
* Forecast future sales off the monthly trend to support planning
* Dig into retention, who comes back and who disappears after one order
* Bring in cost and discount data for real profitability by category and region
* Compare order and delivery timestamps against expected delivery dates to catch actual shipping delays
* Add drill through pages, tooltips, and bookmarks in Power BI for deeper exploration
* Connect the dashboard to a live data source so it stays current instead of a single snapshot

## Author

**Rinit Jain**


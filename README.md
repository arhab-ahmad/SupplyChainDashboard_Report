# Supply Chain Performance Dashboard | Power BI

[View Dashboard (PDF)](Supplychainproject_Report.pdf)

An interactive Power BI dashboard that analyzes supplier performance, cost, lead time and product quality across a supply chain, so that procurement decisions can be made from data rather than guesswork.

## Business Problem
Which suppliers deliver the most volume and revenue, which are fastest, and where do cost and quality problems sit? This dashboard answers those questions in one view.

## Dataset
- 200 purchase orders (Jan to Jul 2025) from 5 suppliers (S1 to S5)
- 3 product categories (Haircare, Cosmetics, Skincare) delivered to 5 locations (Delhi, Mumbai, Bangalore, Chennai, Kolkata)
- Fields: order quantity, unit cost, supplier and manufacturing lead time, inspection result, defect rate, revenue, total cost

## What I Built
- **Data preparation:** imported and typed the data in Power Query
- **Date table:** created a calendar table (year, quarter, month, weekday) for time-based analysis
- **DAX measures:** Total Cost, Ordered Quantity, Monthly and Daily Orders, Min/Max Cost per Unit, Average Lead Time (supplier and manufacturing), Average Defect Rate, and High-Defect vs Low-Defect SKU counts (threshold: 2%)
- **Dashboard:** KPI cards plus supplier, location and product-type visuals, with a Product Type slicer for filtering

## Key Questions Answered
- Which supplier has the best lead time?
- Which supplier supplied the most product?
- How many SKUs come from each supplier?
- How is revenue distributed by supplier, location and product type?
- What is the total cost per supplier across locations?
- How does defect rate vary by inspection result?

## Key Insights
- Supplier S1 leads on volume (2,459 units), revenue and SKU count; S3 has the lowest average lead time (about 27 days)
- Average lead time is about 29 days and average defect rate is about 3.1%
- 136 of 200 SKUs exceed the 2% defect threshold, which points to a quality-control issue worth investigating
- Kolkata has the highest cost and revenue among the locations

## Tools
Power BI, DAX, Power Query, Excel

## Files
- `Supply_Chain_Management_Dataset_200_Rows.xlsx`: source data

## Author
Arhab Ahmad

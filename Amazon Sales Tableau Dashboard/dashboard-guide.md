# Amazon Sales Dashboard - User Guide

A comprehensive guide to understanding and using the Amazon Sales Dashboard in Tableau.

## Table of Contents
1. [Dashboard Overview](#dashboard-overview)
2. [Key Metrics Explained](#key-metrics-explained)
3. [Dashboard Components](#dashboard-components)
4. [Filtering & Interaction](#filtering--interaction)
5. [Common Use Cases](#common-use-cases)
6. [Tips & Tricks](#tips--tricks)
7. [Glossary](#glossary)

---

## Dashboard Overview

The Amazon Sales Dashboard is an interactive Tableau visualization that tracks the performance of global superstore operations from 2014-2017. It combines sales data, profitability metrics, regional performance, and customer insights in an easy-to-understand format.

### Dashboard Goals
- **Monitor Sales Performance:** Track revenue trends over time
- **Identify Profitability:** Understand which products and regions are most profitable
- **Analyze Customer Behavior:** Segment and evaluate different customer types
- **Track Operations:** Monitor shipping, returns, and order priorities
- **Support Decision-Making:** Provide data-driven insights for business strategy

---

## Key Metrics Explained

### Financial Metrics

| Metric | Definition | Importance |
|--------|------------|------------|
| **Sales** | Total revenue from products sold | Primary indicator of business activity |
| **Profit** | Revenue minus costs (COGS, shipping, discounts) | Shows actual profitability, not just sales volume |
| **Profit Margin** | (Profit / Sales) × 100 | Percentage return; higher is better |
| **Discount** | Percentage reduction offered to customers | Impacts profit; lower discounts = higher margins |
| **Shipping Cost** | Cost to deliver orders to customers | Reduces profit; analyze by ship mode for efficiency |

### Operational Metrics

| Metric | Definition | Importance |
|--------|------------|------------|
| **Quantity** | Number of items sold | Volume indicator; helps forecast inventory |
| **Order Count** | Number of distinct orders | Transaction frequency |
| **Return Rate** | (Returned Items / Total Items) × 100 | Quality/satisfaction indicator; lower is better |
| **Avg Order Value** | Sales / Number of Orders | Customer spending behavior |

### Segmentation Dimensions

| Dimension | Possible Values | Use Case |
|-----------|-----------------|----------|
| **Segment** | Consumer, Corporate, Home Office | Target different marketing strategies |
| **Category** | Office Supplies, Furniture, Technology | Product performance comparison |
| **Ship Mode** | Same Day, First Class, Second Class, Standard | Shipping cost vs. speed analysis |
| **Region/Market** | 23 global regions | Geographic performance |
| **Product** | Various office products and furniture | Product-level analysis |

---

## Dashboard Components

### 1. Sales by Region (Map Visualization)
**What it shows:** Geographic distribution of sales across 23 regions globally

**How to use:**
- Hover over regions to see exact sales amounts
- Click a region to filter all other charts
- Darker shading = higher sales
- Light shading = lower sales or no data

**Insights to look for:**
- Which regions drive the most revenue?
- Are there underperforming markets?
- How does profit compare to sales by region?

---

### 2. Sales Over Time (Trend Chart)
**What it shows:** Monthly or quarterly sales trends from 2014-2017

**How to use:**
- Identify seasonal patterns (peaks and valleys)
- Look for growth or decline trends
- Compare year-over-year performance
- Use date filters to zoom into specific periods

**Insights to look for:**
- Seasonal spikes (Q4 holidays, back-to-school)
- Growth trajectory
- Impact of business changes or promotions

---

### 3. Sales by Category (Bar Chart)
**What it shows:** Revenue breakdown by product category (Office Supplies, Furniture, Technology)

**How to use:**
- Compare bar heights to identify top categories
- Click a bar to filter entire dashboard by category
- View profit vs. sales side-by-side

**Typical findings:**
- Technology often has highest sales but lower margins
- Furniture has smaller volume but higher profit margins
- Office Supplies is reliable, stable revenue

---

### 4. Sales by Segment (Pie Chart / Treemap)
**What it shows:** Revenue split between Consumer, Corporate, and Home Office segments

**How to use:**
- See percentage breakdown of each segment
- Click segments to focus analysis
- Compare profitability across segments

**Key questions:**
- Which segment is most profitable?
- Is one segment growing while others decline?
- Do segments prefer different product categories?

---

### 5. Profit Analysis
**What it shows:** Profitability trends and profit by category/region

**How to use:**
- Red/negative values = losses or low profit
- Green/positive values = healthy profit
- Identify which products/regions are unprofitable
- Evaluate discount impact on profit

**Warning signs:**
- Profitable sales with negative profit margins
- High discount rates reducing profits
- Specific products consistently losing money

---

### 6. Return Rate Dashboard
**What it shows:** Products and regions with high return rates

**How to use:**
- High returns (red) = quality or satisfaction issues
- Low returns (green) = product satisfaction
- Investigate high-return items
- Compare return rates by region

**Actions to consider:**
- Review quality for high-return products
- Investigate regional satisfaction issues
- Adjust inventory of high-return items

---

### 7. Shipping Mode Analysis
**What it shows:** Cost and frequency by shipping method (Same Day, First Class, Second Class, Standard)

**How to use:**
- Compare shipping costs vs. order volume
- Identify if customers pay premium for faster shipping
- Evaluate standard shipping profitability

**Optimization opportunities:**
- Can more customers use Standard shipping?
- Is Same Day shipping profitable?
- Balance speed expectations with cost

---

## Filtering & Interaction

### Global Filters
Most dashboards include top-level filters:

- **Date Range:** Filter by year, quarter, month
- **Region:** Select specific geographic regions
- **Category:** Filter by product category
- **Segment:** Choose consumer type
- **Ship Mode:** Filter by shipping method

### How to Filter

1. **Click on a chart element** to filter
   - Click a region on the map to show only that region's data
   - Click a bar in the category chart to filter by category
   - Click a segment to show only that segment

2. **Use filter dropdowns** at the top
   - Click the filter field
   - Select desired values
   - Uncheck to exclude

3. **Clear filters**
   - Click "Clear All" or the filter's X button
   - Or click the dashboard background to deselect

### Drill-Down Analysis
If your dashboard supports drill-down:
- Double-click a chart to expand into detail view
- Right-click for additional options
- Use breadcrumb navigation to go back

---

## Common Use Cases

### Use Case 1: Identifying Problem Areas
**Goal:** Find underperforming products or regions

**Steps:**
1. Filter by Year (most recent)
2. Look at "Profit Margin" by category
3. Identify red/negative values
4. Click to drill into details
5. Investigate root causes

**Questions to answer:**
- Why is profit negative?
- Are discounts too high?
- Are shipping costs excessive?
- Is there a quality issue (high returns)?

---

### Use Case 2: Regional Comparison
**Goal:** Compare performance across markets

**Steps:**
1. Use Region filter to select 2-3 regions
2. Compare sales, profit, and growth
3. Look at category mix differences
4. Analyze segment preferences

**Key comparisons:**
- Total sales and profit
- Average order value
- Segment distribution
- Category preferences
- Return rates

---

### Use Case 3: Seasonal Analysis
**Goal:** Understand seasonal patterns

**Steps:**
1. Look at Sales Over Time chart
2. Note peaks and valleys
3. Filter by year to compare year-over-year
4. Identify consistent seasonal patterns
5. Note anomalies

**Insights:**
- When are peak sales months?
- How long do peaks last?
- Is growth consistent year-over-year?
- Can you forecast based on patterns?

---

### Use Case 4: Customer Segment Analysis
**Goal:** Understand different customer groups

**Steps:**
1. Filter by Segment (Consumer, Corporate, or Home Office)
2. Compare average order value
3. Look at category preferences
4. Analyze profitability
5. Evaluate shipping preferences

**Strategic questions:**
- Which segment is most valuable?
- Do segments have different needs?
- Can we target each segment differently?
- Where should we invest in growth?

---

### Use Case 5: Discount Impact Analysis
**Goal:** Understand how discounts affect profitability

**Steps:**
1. Create a scatter plot (Discount vs. Profit)
2. Look for correlation patterns
3. Identify products with high discounts
4. Compare to profitability
5. Evaluate ROI of discounts

**Findings:**
- Do deep discounts drive volume?
- Do high-discount items have high returns?
- What's the break-even discount level?
- Should we eliminate discounts on some items?

---

## Tips & Tricks

### Tableau Shortcuts

| Action | Shortcut | Purpose |
|--------|----------|---------|
| **Zoom In** | Ctrl + scroll | Focus on chart details |
| **Reset Zoom** | Ctrl + 0 | Return to normal view |
| **Full Screen** | F (on dashboards) | Hide menus for presentation |
| **Export to PDF** | Ctrl + P | Save dashboard snapshot |
| **Export to Image** | Dashboard menu | Share visual snapshot |

### Best Practices

1. **Start Broad, Then Drill Down**
   - Begin with overall metrics
   - Filter to specific areas of interest
   - Compare filtered vs. unfiltered views

2. **Look for Trends, Not Just Snapshots**
   - Don't just look at current numbers
   - Compare to historical performance
   - Identify growth or decline patterns

3. **Question Anomalies**
   - Investigate spikes or drops
   - Check for data entry errors
   - Verify with source data if needed

4. **Combine Multiple Perspectives**
   - Don't rely on one chart alone
   - Correlate findings across multiple views
   - Look for confirming or contradicting patterns

5. **Document Your Findings**
   - Note interesting insights
   - Save filtered views for reports
   - Create snapshots for presentations

---

## Glossary

| Term | Definition |
|------|-----------|
| **Drill-Down** | Clicking to view more detailed data from a summary |
| **Filter** | Restricting view to show only selected values |
| **Dimension** | A categorical variable (Region, Category, Segment) |
| **Measure** | A numerical value that can be aggregated (Sales, Profit) |
| **Aggregation** | Combining data (SUM, AVG, COUNT) |
| **YoY (Year-over-Year)** | Comparing same period in consecutive years |
| **Margin** | Profit as percentage of sales |
| **COGS** | Cost of Goods Sold |
| **SKU** | Stock Keeping Unit (product identifier) |
| **Segment** | Customer type category (Consumer, Corporate, Home Office) |

---

## Troubleshooting

### Dashboard Shows "No Data"
- Check if filters are too restrictive
- Reset all filters using "Clear All"
- Verify data file is connected (Data → Data Source)

### Numbers Look Incorrect
- Verify correct time period is selected
- Check if filters are applied (blue filter icons = active)
- Confirm aggregation method (SUM vs. AVG)

### Slow Performance
- Reduce time period selection
- Use fewer filters
- Contact Tableau admin if issue persists
- Close other applications

### Can't Click Charts
- Make sure dashboard is in "normal" view, not edit mode
- Check if selections are set to "None"
- Ensure you have sufficient Tableau permissions

---

## Getting More Help

1. **Tableau Help Menu:** Help → Tableau Help (online documentation)
2. **Tableau Community:** community.tableau.com (ask other users)
3. **Dashboard Owner:** Contact the person who created this dashboard
4. **Data Issues:** Contact the data team if numbers seem wrong

---

## Sample Questions to Ask the Data

Use this dashboard to answer questions like:

- "Which region generated the most profit last quarter?"
- "What's our return rate for Technology products in Europe?"
- "Are we over-discounting certain products?"
- "How did Q4 sales compare to last year?"
- "Which customer segment is most profitable?"
- "Do high-discount sales items have high return rates?"
- "What's the average shipping cost by region?"
- "Which months typically have the highest sales?"

---

**Happy Analyzing!**

For questions about specific insights or how to modify the dashboard, refer to [README.md](README.md).

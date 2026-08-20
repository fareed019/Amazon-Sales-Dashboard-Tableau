# Amazon Sales Dashboard

A comprehensive Tableau dashboard analyzing global superstore sales performance, profitability, and customer metrics.

## 📊 Overview

This repository contains a Tableau Desktop dashboard that provides insights into sales trends, regional performance, product categories, and customer segments across multiple global markets from 2014-2017.

**Dashboard File:** `Amazon_Sales_Dashboard.twbx`  
**Data Source:** `Global_Superstore_2018.xlsx`

## 📁 Repository Structure

```
amazon-sales-dashboard/
├── README.md                              # This file
├── dashboard-guide.md                     # Detailed dashboard documentation
├── Amazon_Sales_Dashboard.twbx            # Tableau workbook (interactive dashboard)
└── data/
    └── Global_Superstore_2018.xlsx        # Source data with 3 sheets: Orders, Returns, People
```

## 🚀 Getting Started

### Prerequisites
- **Tableau Desktop** (2019 or later recommended)
- Excel or similar spreadsheet application (optional, for data inspection)

### How to Open the Dashboard

1. **Clone or download this repository**
   ```bash
   git clone https://github.com/your-username/amazon-sales-dashboard.git
   cd amazon-sales-dashboard
   ```

2. **Open the dashboard in Tableau Desktop**
   - Launch Tableau Desktop
   - Go to **File → Open**
   - Navigate to `Amazon_Sales_Dashboard.twbx`
   - The dashboard will load with data automatically connected

3. **Explore the visualizations**
   - See [dashboard-guide.md](dashboard-guide.md) for detailed explanations of each dashboard component

## 📊 Data Description

The `Global_Superstore_2018.xlsx` file contains three sheets:

### Orders Sheet (51,290 records)
- **Time Period:** January 2014 - December 2017
- **Key Metrics:** Sales, Profit, Quantity, Discount, Shipping Cost
- **Dimensions:** Product Category, Sub-Category, Region, Market, Customer Segment, Ship Mode, Order Priority
- **Customer Data:** Customer ID, Name, Postal Code, City, State, Country

### Returns Sheet (2,033 records)
- Tracks products returned by customers
- Linked to Orders via Order ID
- Includes regional return information

### People Sheet (24 records)
- Regional managers and contacts
- Maps person to region assignments

## 💡 Key Insights Available

- **Sales Performance:** Track sales trends across time, regions, and product categories
- **Profitability Analysis:** Identify high-profit and loss-making product segments
- **Regional Comparison:** Compare performance across 23 global regions
- **Customer Segmentation:** Analyze by Consumer, Corporate, and Home Office segments
- **Return Rates:** Monitor product returns and their impact
- **Shipping Analysis:** Evaluate shipping modes and costs

## 🛠️ Customization

To modify the dashboard:

1. Open `Amazon_Sales_Dashboard.twbx` in Tableau Desktop
2. **Edit data source:** Right-click the data source → Edit Data Source
3. **Update visualizations:** Click any chart and modify filters, dimensions, or measures
4. **Save changes:** File → Save (overwrites the .twbx file)
5. **Commit to GitHub:** 
   ```bash
   git add Amazon_Sales_Dashboard.twbx
   git commit -m "Update dashboard [description of changes]"
   git push
   ```

## 📥 Updating Data

To refresh the dashboard with new data:

1. Update `Global_Superstore_2018.xlsx` with new data (maintain the same sheet structure)
2. In Tableau, the dashboard will prompt you to refresh the connection
3. Alternatively, manually refresh: Data → Refresh All
4. Save and commit the updated files

## 🔍 Troubleshooting

**Dashboard won't open?**
- Ensure Tableau Desktop is installed and up to date
- Check that both the .twbx file and data file are in the correct location
- Try opening Tableau first, then using File → Open

**Data connection broken?**
- Verify `Global_Superstore_2018.xlsx` is in the same directory or adjust the data source path
- In Tableau: Data → Edit Data Source → Update connection

**Performance issues?**
- Large dashboards can be slow; consider filtering to specific time periods
- Use Tableau's performance recording tool (Help → Settings and Performance → Start Performance Recording)

## 📋 Requirements Met

- ✅ Tableau workbook (.twbx) for version control
- ✅ Source data (.xlsx) included for reproducibility
- ✅ Comprehensive README with setup instructions
- ✅ Detailed dashboard guide (see dashboard-guide.md)
- ✅ Clear documentation for collaboration

## 🤝 Contributing

To contribute improvements:

1. Create a branch: `git checkout -b feature/dashboard-improvement`
2. Make changes to the dashboard in Tableau Desktop
3. Save and test thoroughly
4. Commit: `git commit -m "Add [feature description]"`
5. Push: `git push origin feature/dashboard-improvement`
6. Open a pull request with a description of changes

## 📝 Notes

- This dashboard uses the Global Superstore public dataset (common for Tableau training)
- Data represents 2014-2017 transactions; the "Amazon Sales Dashboard" name is for reference only
- All data is sample/anonymized and suitable for demo purposes
- Original data source: Tableau's sample datasets

## 📧 Questions?

For issues or questions about the dashboard, please open a GitHub issue or refer to [dashboard-guide.md](dashboard-guide.md) for detailed documentation.

---

**Last Updated:** August 2026  
**Tableau Version Tested:** 2023.1+  
**Data Last Refreshed:** Q4 2017

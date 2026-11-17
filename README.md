# Restaurant Sales Analysis Dashboard | Power BI

An interactive Power BI dashboard for exploring restaurant sales and operations data. The report brings together order trends, food-category quantities, delivery outcomes, payment methods, and restaurant-level order performance in a one view.

## Dashboard Preview

![Restaurant Insights — Sales & Operations Overview](Screenshots/dashboard.png)

## Dashboard at a Glance

The dashboard screenshot reports the following headline figures:

| KPI | Reported value |
|---|---:|
| Total Orders | 2,746 |
| Total Quantity Sold | 15,103 |
| Total Restaurants | 6 |
| Total Customers | 30 |
| Delivered Orders | 94.25% |

## Analysis Included

### Orders Trend Over Time
Displays order counts across the monthly sales data shown in the report. The visible data points are 792, 765, 626, and 563.

### Food Type Sales
Compares quantity sold across six food categories. Main Course and Snack are the largest categories in the displayed chart.

| Food category | Quantity shown (approx.) |
|---|---:|
| Main Course | 6.9K |
| Snack | 4.5K |
| Dessert | 1.6K |
| Breakfast | 1.6K |
| Beverage | 0.5K |
| Appetizer | 0.1K |

### Delivery Status

| Status | Orders | Share |
|---|---:|---:|
| Delivered | 2,588 | 94.25% |
| Cancelled | 158 | 5.75% |

### Payment Method

| Payment method | Orders | Share |
|---|---:|---:|
| UPI | 1,719 | 62.60% |
| COD | 750 | 27.31% |
| Card | 277 | 10.09% |

### Restaurant Performance

The chart compares order counts for six restaurants:

| Restaurant | Orders |
|---|---:|
| Bukhara 212 | 749 |
| Saravana Bhava… | 729 |
| Indian Accent 214 | 404 |
| Karavalli 213 | 370 |
| Moti Mahal 216 | 249 |
| Dakshin 217 | 245 |

## Tools

- Microsoft Power BI
- Power Query / data preparation (where used in the report)
- Data visualization and interactive report filters

## Repository Contents

```text
Restaurant-Sales-Analysis/
├── Screenshots/
│   └── dashboard.png
├── Dataset/
│   └── January_23.xlsx
│   └── February_23.xlsx
│   └── March_23.xlsx
│   └── April_23.xlsx
│   └── Other_Data.xlsx
├── Restaurant_Sales_Analysis.pbix/
│   └── bi_01.pbix
└── README.md
```

## View the Report

1. Download the `.pbix` file from this repository (once uploaded).
2. Open it with Microsoft Power BI Desktop.
3. If Power BI asks for the source data, update the data-source path or credentials as needed.
4. Use the report filters to explore the available data.

## Notes

- Figures and category values above are transcribed from the supplied dashboard screenshot; category quantities are rounded as displayed.
- The source dataset and `.pbix` file should be added to this repository separately. Do not upload confidential or restricted data.

## Author

**Anirudha Samadhan Mali**

Data Analytics | Business Intelligence | Power BI

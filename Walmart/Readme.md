🎯 Objective

To design a clean and insightful Power BI dashboard that visualizes:
- Sales performance over time
- Regional (store-wise) sales comparison
- Monthly sales distribution by store

---

## 🛠 Tools Used

- **Power BI Desktop** for dashboard creation
- **DAX** for calculated columns
- **Walmart.csv** dataset (publicly available on Kaggle)

---

## 📁 Dataset Overview

| Column         | Description                            |
|----------------|----------------------------------------|
| `Store`        | Store number (acts as region proxy)    |
| `Date`         | Weekly date of sales                   |
| `Weekly_Sales` | Sales figures in USD                   |
| `Holiday_Flag` | 1 if week includes a holiday, else 0   |
| `Temperature`  | Temperature in the region              |
| `Fuel_Price`   | Fuel price in the area                 |
| `CPI`          | Consumer Price Index                   |
| `Unemployment` | Regional unemployment rate             |

---

## 📊 Dashboard Components

### 1. **Line Chart – Sales Over Time**
- **X-axis**: `YearMonth`
- **Y-axis**: Total `Weekly_Sales`
- Shows seasonal trends and overall performance.

### 2. **Bar Chart – Sales by Store**
- Compares total sales across all Walmart stores.
- Highlights top and bottom performers.

### 3. **Donut Chart / Stacked Bar Chart – Monthly Distribution**
- **Donut Chart**: Store contribution in a selected month.
- **Stacked Bar Chart**: Multi-month breakdown by store.

### 4. **Slicers**
- `Store`: View performance of specific stores.
- `Holiday_Flag`: Toggle between holiday and non-holiday weeks.

---

## 📌 Key Insights

1. **Store 4 had the highest overall sales across all months.**
2. **April 2010 showed a noticeable sales spike.**
3. **Not all holidays resulted in higher sales – further seasonal analysis needed.**

---




# 📦 Inventory Supply to Demand Dashboard

An interactive **Tableau** dashboard that analyzes inventory supply against customer demand. It helps identify overstocked and understocked product categories, track warehouse inventory trends, and monitor inventory balance over time.

---

## 📸 Dashboard Preview

> Add your screenshot to the repository (e.g., `images/dashboard.png`) and it will display below.

![Inventory Dashboard](images/dashboard.png)

---

## 🎯 Objectives

- Compare **warehouse inventory** with **order quantity (demand)** over time
- Identify categories with **excess stock** or **shortages**
- Track **monthly inventory balance** (surplus vs. deficit)
- Evaluate **average inventory balance** and **unit cost** across product categories

---

## 📊 Dashboard Components

| Visualization | Description |
|---|---|
| **Average Unit Cost** | KPI showing the average cost per unit (≈ 1.217) |
| **Inventory Balance** | KPI showing the overall inventory balance (≈ 4,647) |
| **Inventory vs Demand by Month** | Dual-axis line chart comparing Warehouse Inventory and Order Quantity from 2015 to 2018 |
| **Monthly Inventory Balance** | Bar chart showing monthly surplus/deficit with an average reference line |
| **Supply vs Demand by Category** | Scatter plot of Supply-to-Demand Ratio vs Order Quantity per category |
| **Average Inventory Balance by Category** | Horizontal bar chart ranking product categories (Toys, Cleats, Shop By Sport, Cameras, etc.) by average monthly balance |

---

## 🔑 Key Insights

- Warehouse inventory and order quantity track each other closely from 2015 to 2017, with a sharp drop toward early 2018.
- Monthly inventory balance fluctuates between surplus and deficit, with notable spikes in 2016–2017.
- **Toys** and **Cleats** show the highest average inventory balance, while several categories sit near zero or negative.
- Most categories have a supply-to-demand ratio around 1.0, while a few outliers show significant oversupply or undersupply.

---

## 🛠️ Tools & Technologies

- **Tableau Desktop (Public Edition)**
- Dataset: Inventory / Supply Chain data (inventory date, warehouse inventory, order quantity, product category, unit cost)

---

## 📁 Repository Structure

```
├── Inventory_Dashboard.twbx    # Tableau packaged workbook
├── data/                       # Source dataset(s)
├── images/
│   └── dashboard.png           # Dashboard screenshot
└── README.md
```

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. Open `Inventory_Dashboard.twbx` in **Tableau Desktop** or **Tableau Public**.
3. Explore the dashboards (**Dashboard 1** and **Dashboard 2**) and use the filters (e.g., Order Year, Product Category) to drill down.

---

## 📈 Sheets in the Workbook

- Average Unit Cost
- Inventory Balance
- Inventory vs Demand by Month
- Monthly Inventory Balance
- Supply vs Demand by Category
- Supply to Demand Ratio
- Average Inventory Balance by Category
- Storage Cost by Category
- Overstock Storage Cost by Month
- Shipment / Delay analysis sheets

---

## 👤 Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [Your Profile](https://linkedin.com/in/your-profile)

---

## 📄 License

This project is licensed under the MIT License — feel free to use and modify it.

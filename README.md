# IBP Forecast Quality Simulation

**SKU-Level Demand Planning | Margin Risk | Sustainability KPI**

---

## 🧠 Project Overview
This simulation models a real-world SAP IBP demand planning scenario across three SKUs over 24 months. It evaluates the downstream impact of forecast error on financials and ESG performance, providing a cross-functional lens into supply chain planning, cost risk, and sustainability efficiency.

---

## 🎯 Business Context
Enterprises face significant challenges from poor forecast quality, resulting in:
- Inventory imbalances
- Margin erosion
- Excess carbon emissions

This project simulates:
- Forecast accuracy KPIs (MAPE, Bias, Forecast Accuracy)
- Margin impact of forecast deviation
- Revenue vs carbon efficiency (revenue per kg CO₂e)
- Scenario analysis: demand shocks, carbon tax, forecast-to-cash

---

## 🧩 Dataset
- **Source**: Synthetic simulation data across 3 SKUs
- **Structure**: Forecast vs actuals, revenue, carbon emissions, holding cost
- **Periods**: 24 months (Jan '23 to Dec '24)

Files:
- `SAP_IBP_Forecast_Accuracy_Tracker.csv`
- `Inventory_Holding_Cost_Simulation.csv`
- `Scenario_F_Forecast_to_Cash.csv`

---

## 📊 KPIs and Charts

### 1. Forecast Accuracy
| SKU    | MAPE   | Bias | Forecast Accuracy |
|--------|--------|------|-------------------|
| SKU_A  | 4.12%  | +4.1 | 95.88%            |
| SKU_B  | 3.85%  | -2.0 | 96.15%            |
| SKU_C  | 4.82%  | +10.2| 95.18%            |

**Chart**: `forecast_accuracy_chart.png`

---

### 2. Margin Analysis
Simulates revenue and margin deviations based on forecast error.

**Chart**: `margin_chart.png`

---

### 3. Sustainability Efficiency
**KPI**: Revenue per kg of CO₂e emitted

| SKU    | Revenue per kgCO₂e |
|--------|----------------------|
| SKU_A  | $495.91              |
| SKU_B  | $561.97              |
| SKU_C  | $588.97              |

**Chart**: `sustainability_efficiency_chart.png`

---

## 🧪 Scenario Comparisons

### Scenario C: Carbon Tax Impact
- Applied $0.05/kg CO₂e
- SKU_C had highest cost exposure

### Scenario D: Demand Shock
- Simulated volatility
- Compared forecast accuracy before/after shock

### Scenario F: Forecast-to-Cash
- Tracked actual cash realization from forecast revenue
- SKU-level cash consistency tracked

---

## 🛠️ Tools Used
- **Excel**: Forecast tracker, scenario simulation, KPI dashboards
- **Python/Jupyter**: Chart automation, error metrics
- **GitHub**: Version control, publishing

---

## 📘 How to Use
1. Clone the repo
2. Open Excel workbook `Final_KPI_Tracker.xlsx`
3. Explore Jupyter notebook in `/notebooks` for Python version

---

## 📫 Contact
Created by [Your Name] • SAP FI | IBP Candidate  
[LinkedIn](#) | [GitHub](#)

---

## License
MIT License


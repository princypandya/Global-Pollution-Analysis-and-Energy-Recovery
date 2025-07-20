# 🌍 Global Pollution Analysis and Energy Recovery

This project focuses on analyzing global pollution metrics and developing strategies for pollution reduction and energy recovery using predictive modeling.

## 📌 Objective

To analyze pollution indicators (air, water, soil), CO₂ emissions, and other environmental data across countries and years, and:

- Predict energy recovery potential from pollutants.
- Classify pollution severity.
- Recommend actionable strategies for cleaner energy and environmental sustainability.

---

## 📊 Dataset Overview

The dataset includes:

- Pollution indices (air, water, soil)
- CO₂ emissions (in MT)
- Industrial & plastic waste (in tons)
- Energy recovered (in GWh)
- Renewable energy usage (%)
- GDP per capita, population, and energy consumption

📁 **File**: `Global_Pollution_Analysis.csv`

---

## 📂 Project Structure

### 🔹 Phase 1: Data Preprocessing & Exploratory Analysis (EDA)

- ✅ Null/Invalid Value Handling  
- ✅ Outlier Handling  
- ✅ Label Encoding (Country, Year)  
- ✅ Standardization (Pollution Indexes)

### 🔹 Phase 2: Predictive Modeling

#### 🔸 Linear Regression

- **Goal**: Predict energy recovery (in GWh)  
- **Features**: Air pollution, industrial waste, CO₂ emissions, population  
- **Result**:
  - R² score ≈ 0.001  
  - Low predictive accuracy

#### 🔸 Logistic Regression

- **Goal**: Categorize CO₂ pollution severity as **Low**, **Medium**, or **High**
- **Features**: Same as above
- **Results**:
  - **Accuracy**: 71.7%  
  - **F1 Score**: 0.72  
  - Good performance in multi-class classification

---

## 📈 Visualizations

- ✅ Correlation heatmap
- ✅ CO₂ emissions by country/year
- ✅ Pollution vs. energy recovery scatterplots
- ✅ Pollution severity classification
- ✅ Bar/line plots for temporal and geographic patterns

---

## ⚙️ Technologies Used

- Python 🐍:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`
- Jupyter Notebook
- Linear and Logistic Regression Models

---

## 🔍 Key Insights

- CO₂ emissions and industrial waste show strong correlation.
- Higher pollution correlates with greater potential for energy recovery.
- Logistic Regression outperforms Linear Regression for classification.
- Significant scope for waste-to-energy conversion technologies.

---

## 📢 Recommendations

- Prioritize energy recovery investments in countries with high pollution and moderate infrastructure.
- Implement real-time pollution monitoring systems.
- Promote global cooperation in clean energy and pollution reduction.

---

## 📁 How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/princypandya/Global-Pollution-Analysis-and-Energy-Recovery.git
   cd Global-Pollution-Analysis-and-Energy-Recovery

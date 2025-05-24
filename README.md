# 🌾 Agricultural Emissions Analysis using Python

This project analyzes India's crop-wise agricultural emissions from 1965 to 2017, exploring the relationship between crop area/production and greenhouse gas emissions (CO₂ and methane).

---

## 📂 Dataset

- Crop area and production data (1965–2017) for major Indian crops

- Annual greenhouse gas emissions from OWID (Our World In Data)

---

## 🎯 Objectives

- Understand the trend of agricultural land use and crop production over decades

- Quantify the impact of major crops on methane and CO₂ emissions

- Identify low-emission and high-emission crop categories

- Analyze per-hectare methane efficiency by crop

---

## 🛠️ Methods Used

- Python libraries: `pandas`, `matplotlib`, `seaborn`

- Data aggregation and cleaning

- Correlation analysis (crop area/production vs emissions)

- Time-series trend analysis and visualization

- Emission efficiency analysis (emissions per hectare)

---

## 🔍 Key Statistical Findings



### 🌿 Emission Trends

- Cumulative CO₂ emissions have grown exponentially since 1965

- Methane emissions show a steady linear increase

### 📘 Crop Trends

- Total cultivated area has increased till early 2000s and then plateaued

- Top crops by land area: Rice, Wheat, Sugarcane, Cotton, Oilseeds

### 📊 Correlation Highlights

- Rice production has the highest correlation with methane (0.97) and CO₂ (0.93)

- Crops with strong emission correlations:
  - Rice 

  - Wheat

  - Sugarcane

  - Soybean

###  🌾 Crops with Least Emission :

  - Barley
  - Finger
  - Millet
  - Sorghum
  - Pulses

### 🧮 Methane Efficiency

- Methane emissions per hectare are highest for:

  - Rice
  - Sugarcane
  - Rapeseed
  - Mustard

Climate-resilient crops (lowest per-hectare methane):

  - Barley
  - Millets
  - Linseed

---

## 📊 Sample Visuals

![Heatmap](‎[correlation_production_heatmap.png](https://github.com/RohithRoshanMurali/Agricultural-Emissions/blob/main/correlation_production_heatmap.png))



---

## 🧠 Final Insight

- A small group of staple crops (rice, wheat, sugarcane) are responsible for a disproportionate share of emissions. 
- Transitioning to millets and pulses can offer sustainable alternatives aligned with India's climate targets.

---

## ✨ Future Ideas

- Simulate methane savings from reduced rice cultivation

- Build predictive models for agricultural emissions

- Cluster crops based on emission profiles and yield


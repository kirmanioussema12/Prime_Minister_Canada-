
### 📑 Columns

| Column | Description |
|------|-------------|
| `Order` | Chronological order of Prime Ministers |
| `Name` | Full name |
| `Gender` | Gender |
| `Age_At_Start` | Age when first became Prime Minister |
| `Height_cm_estimated` | Estimated height (cm) |
| `Birth_Date` | Date of birth |
| `First_Term_Start_Date` | Date of first term start |

📌 **Total entries:** 24 Prime Ministers (1867 → present)

---

## 🧠 Methodology

### 🔢 Numerical Computation (NumPy)
All numerical calculations are performed using **NumPy arrays**, including:

- Median height (`np.median`)
- Mean age at start (`np.mean`)
- Percentiles (`np.percentile`)
- Histograms (`np.histogram`)
- Correlation (`np.corrcoef`)
- Z-scores (outlier detection)

### 🗃 Data Handling (pandas)
Used for:
- Loading CSV data
- Type conversion (dates, numerics)
- Table summaries
- Exporting enriched datasets

### 📊 Visualization (matplotlib)
Plots include:
- Age range bar charts
- Height distribution histograms (explicit bins)
- Gender distribution
- Summary KPI bar charts (median height vs average age)

---

## 📈 Key Analyses Included

✔ Dataset inspection (`.info()`, shape, missing values)  
✔ Median height of Prime Ministers  
✔ Average age at first term  
✔ Gender count and percentages  
✔ Age distribution using **explicit bins**  
✔ Height distribution using **explicit intervals**  
✔ Cross-analysis: gender × age range  
✔ Correlation between age and height  
✔ Export of enriched dataset for further visualization  

---

## 🧪 Example Metrics

- 🧍 **Median Height (cm)** — NumPy based  
- 🎂 **Average Age at Start** — NumPy based  
- 👥 **Gender Distribution**  
- 📊 **Age & Height Histograms with Intervals**

---

## 🛠 Technologies Used

<p align="center">
  <img src="https://numpy.org/images/logo.svg" width="80"/>
  &nbsp;&nbsp;&nbsp;
  <img src="https://pandas.pydata.org/static/img/pandas_white.svg" width="120"/>
  &nbsp;&nbsp;&nbsp;
  <img src="https://matplotlib.org/stable/_images/sphx_glr_logos2_001.png" width="120"/>
</p>

- **Python 3**
- **NumPy**
- **pandas**
- **matplotlib**
- **Jupyter Notebook**

---

## 📂 Files in This Project
```text
📁 project/
├── Analysis.ipynb
├── canadian_prime_ministers_age_at_start_with_carney.csv
├── pm_dataset_enriched_for_charts_numpy.csv
└── README.md
```


---

## 🚀 Next Possible Extensions

- 📉 Boxplots (height vs age range)
- 📈 Scatter plot (age at start vs height)
- 📊 Stacked bar charts (gender × age range)
- 🧠 Statistical tests (normality, variance)
- 📘 Convert analysis into a report / PDF

---

## ✨ Author Notes

This notebook is designed to:
- Be **academically correct**
- Clearly separate **NumPy (computation)** from **pandas (structure)**
- Serve as a **data analysis learning reference** or **portfolio project**

---

🇨🇦 *Data inspired by public historical records*
⚠️ *Height values are estimated for analytical purposes*

---

⭐ If this notebook helped you, feel free to expand it further or reuse the structure for other datasets!

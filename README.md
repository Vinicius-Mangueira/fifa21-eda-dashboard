```markdown
# FIFA21 EDA Dashboard 🏟️📊

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)  
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Vinicius-Mangueira/fifa21-eda-dashboard/HEAD)  
[![Open in NBViewer](https://img.shields.io/badge/Open%20in-NBViewer-orange.svg)](https://nbviewer.org/github/Vinicius-Mangueira/fifa21-eda-dashboard/blob/main/notebooks/fifa21_eda_dashboard.ipynb)

> **Interactive Data Analysis and Visualization of FIFA 21 Player Stats**  
> Explore FIFA 21 data with Python in Jupyter: data cleaning, descriptive statistics, dynamic Plotly charts, and a world map of player nationalities—no machine learning required!

---

## 🔥 Key Features

- **Data Cleaning & Preprocessing**  
  • Missing-value handling, type conversions, derived metrics (e.g. BMI)  
- **Descriptive Statistics**  
  • Summary tables: top 10 players by Overall, club-level & position-level aggregates  
- **Static & Interactive Visuals**  
  • Histograms & boxplots (Plotly)  
  • Scatter plots with hover tooltips & filtering (Plotly + `ipywidgets`)  
  • Correlation heatmap of physical vs. technical attributes  
- **Geospatial Analysis**  
  • Folium choropleth & marker map showing player counts & average ratings by country  
- **Live Notebook**  
  • Launch on **Binder** or **NBViewer**—no local install needed  

---

## 📂 Repository Structure

```

fifa21-eda-dashboard/
├── data/
│   └── players\_fifa21.csv        # raw Kaggle data (ignored by Git by default)
├── notebooks/
│   └── fifa21\_eda\_dashboard.ipynb
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt

````

---

## 🚀 Getting Started

1. **Clone this repo**  
   ```bash
   git clone https://github.com/Vinicius-Mangueira/fifa21-eda-dashboard.git
   cd fifa21-eda-dashboard
````

2. **Create & activate a Python environment**

   ```bash
   python3 -m venv venv
   source venv/bin/activate    # macOS/Linux
   venv\Scripts\activate       # Windows
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Download the dataset**

   * Go to [Kaggle FIFA 21 dataset](https://www.kaggle.com/datasets/justinas/fifa-21-complete-player-dataset)
   * Place `players_fifa21.csv` into the `data/` folder

5. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook notebooks/fifa21_eda_dashboard.ipynb
   ```

---

## 📊 Usage & Preview

1. **Load & clean data**
2. **Compute descriptive stats** (mean, median, quartiles)
3. **Generate interactive Plotly charts**
4. **Explore world map of player nationalities**

> **Example snapshot:**
> ![Sample Plotly Scatter](docs/images/scatter_overall_vs_potential.png)
> *Interactive filtering by league & position*

---

## ☁️ Run Online

* **Binder**
  [https://mybinder.org/v2/gh/Vinicius-Mangueira/fifa21-eda-dashboard/HEAD](https://mybinder.org/v2/gh/Vinicius-Mangueira/fifa21-eda-dashboard/HEAD)

* **NBViewer**
  [https://nbviewer.org/github/Vinicius-Mangueira/fifa21-eda-dashboard/blob/main/notebooks/fifa21\_eda\_dashboard.ipynb](https://nbviewer.org/github/Vinicius-Mangueira/fifa21-eda-dashboard/blob/main/notebooks/fifa21_eda_dashboard.ipynb)

---

## 🤝 Contributing

1. Fork the repo
2. Create a feature branch (`git checkout -b feat/awesome-visual`)
3. Commit your changes (`git commit -m "Add awesome viz"`)
4. Push to the branch (`git push origin feat/awesome-visual`)
5. Open a Pull Request

Please respect the existing code style and document any new functionality.

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

> Made with ❤️ by **Vinicius Mangueira**
> Feel free to ⭐️ the repo if you find it useful!

```
```

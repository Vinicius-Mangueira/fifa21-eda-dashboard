
# FIFA21 EDA Dashboard 🏟️📊

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)  
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Vinicius-Mangueira/fifa21-eda-dashboard/HEAD)  
[![Open in NBViewer](https://img.shields.io/badge/Open%20in-NBViewer-orange.svg)](https://nbviewer.org/github/Vinicius-Mangueira/fifa21-eda-dashboard/blob/main/notebooks/fifa21_eda_dashboard.ipynb)

> **Interactive Data Analysis and Visualization of FIFA 21 Player Stats**  
> A Jupyter Notebook project covering data cleaning, descriptive statistics, interactive Plotly charts, and a Folium world map of player nationalities—no machine learning required!

---

## 🚀 Getting Started

1. **Clone the repo**  
   ```bash
   git clone https://github.com/Vinicius-Mangueira/fifa21-eda-dashboard.git
   cd fifa21-eda-dashboard
````

2. **Set up your environment**

   ```bash
   python3 -m venv venv
   source venv/bin/activate    # macOS/Linux
   venv\Scripts\activate       # Windows
   pip install -r requirements.txt
   ```

3. **Get the dataset**

   * Download from [Kaggle FIFA 21 dataset](https://www.kaggle.com/datasets/justinas/fifa-21-complete-player-dataset)
   * Place `players_fifa21.csv` inside the `data/` folder

4. **Run the notebook**

   ```bash
   jupyter notebook notebooks/fifa21_eda_dashboard.ipynb
   ```

---

## 🔥 Key Features

* **Data Cleaning & Preprocessing**
  Handle missing values, type conversions, and derive new metrics (e.g., BMI).

* **Descriptive Statistics**
  Tables showing top-10 players by overall rating, plus aggregates by club and position.

* **Static & Interactive Charts**

  * Histograms, boxplots
  * Scatter plots with hover info and filters (`Plotly` + `ipywidgets`)
  * Correlation heatmap of physical vs. technical attributes

* **Geospatial Analysis**
  `Folium` choropleth and marker map displaying player counts and average ratings by country.

* **Cloud-Ready**
  Launch instantly on **Binder** or **NBViewer**, sem instalação local.

---

## 📂 Repository Structure

```
fifa21-eda-dashboard/
├── data/                        
│   └── players_fifa21.csv      # raw data (added manually; gitignored)
├── notebooks/                  
│   └── fifa21_eda_dashboard.ipynb
├── .gitignore                  
├── LICENSE                     
├── README.md                   
└── requirements.txt            
```

---

## ☁️ Run Online

* **Binder:**
  [https://mybinder.org/v2/gh/Vinicius-Mangueira/fifa21-eda-dashboard/HEAD](https://mybinder.org/v2/gh/Vinicius-Mangueira/fifa21-eda-dashboard/HEAD)

* **NBViewer:**
  [https://nbviewer.org/github/Vinicius-Mangueira/fifa21-eda-dashboard/blob/main/notebooks/fifa21\_eda\_dashboard.ipynb](https://nbviewer.org/github/Vinicius-Mangueira/fifa21-eda-dashboard/blob/main/notebooks/fifa21_eda_dashboard.ipynb)

---

## 🤝 Contributing

1. Fork this repo
2. Create a branch:

   ```bash
   git checkout -b feat/your-feature
   ```
3. Commit your changes:

   ```bash
   git commit -m "Add awesome visualization"
   ```
4. Push & open a Pull Request

Por favor, siga o estilo existente e documente novas funcionalidades.


## 📜 License

Este projeto está sob a **MIT License**. Veja o arquivo [LICENSE](LICENSE) para detalhes.

---

Made with ❤️ by **Vinicius Mangueira** • ⭐️ se achar útil!



# IoT Water Network Monitoring

[![Python](https://img.shields.io/badge/Python-3.x-blue)](https://www.python.org/)  
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)  

---

## **Project Overview**
Analyze a city water distribution network using IoT sensor data. Clean and integrate multi-vendor CSVs, engineer anomaly indicators, perform EDA, visualize trends, and test whether mean pressure differs across zones.

---

## **Repository Structure**
```

├── src/
│   └── IoT_Water_Network_Monitoring.ipynb
├── data/
│   ├── sensors_s4.csv
│   ├── flow_logs_s4.csv
│   └── zones_s4.csv
├── graphs/
│   └── Graphs.pdf
├── docs/
│   ├── USAGE_GUIDE.md
│   ├── LIMITATIONS.md
│   └── IMPROVEMENTS.md
├── LICENSE
└── README.md

````

---

## **Datasets**
| File | Description |
|------|-------------|
| `data/sensors_s4.csv` | IoT sensor readings (pressure, flow) |
| `data/zones_s4.csv` | Zone mapping for sensors |
| `data/flow_logs_s4.csv` | Flow measurement logs |
| `graphs/Graphs.pdf` | PDF of all visualizations |
| `src/IoT_Water_Network_Monitoring.ipynb` | Notebook with cleaning, EDA, analysis, and tests |

---

## **Key Features**
- Data cleaning and integration of multi-vendor IoT CSVs  
- Anomaly detection in pressure and flow readings  
- Exploratory Data Analysis (EDA) and visualizations  
- Statistical tests on pressure differences across zones  

---

## **Requirements**
- Python 3.x  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `warnings`  
- Jupyter Notebook to run the analysis  

---

## **How to Use**
1. Clone the repository:
```bash
git clone https://github.com/<your-username>/IoT-Water-Network-Monitoring.git
````

2. Navigate to the `src/` directory:

```bash
cd IoT-Water-Network-Monitoring/src
```

3. Open the notebook:

```bash
jupyter notebook IoT_Water_Network_Monitoring.ipynb
```

4. Follow the notebook steps to reproduce data cleaning, analysis, and visualizations.
5. Generated plots are saved in `graphs/Graphs.pdf`.

---

## **Documentation**

See the `docs/` folder for detailed guides:

* `USAGE_GUIDE.md` – How to run the project
* `LIMITATIONS.md` – Current limitations of the analysis
* `IMPROVEMENTS.md` – Suggested future improvements

---

## **License**

This project is licensed under the **MIT License**.
See the [LICENSE](LICENSE) file for more details.

---

## **Author**

R Avantikaa



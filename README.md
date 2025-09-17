# Business Analyst GUI

> A desktop application for quick data cleaning, visualization, and machine-learning modeling — built with **Tkinter**, **Pandas**, **Matplotlib**, and scikit-learn.

![Python](https://img.shields.io/badge/python-3.9%2B-blue)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-green)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## 📌 Features

- **Data I/O**: Load CSV / Excel, preview, and save filtered data.
- **Cleaning & Transformation**  
  - Drop / fill missing values  
  - Remove outliers (IQR)  
  - Row filtering with expressions  
  - Computed columns, GroupBy aggregations
- **Visualization**: Bar, Line, Histogram, Scatter (Matplotlib inside Tkinter)
- **Modeling**  
  - Baseline models (Logistic/Linear Regression)  
  - Optional AutoML (auto-sklearn / TPOT)
- Responsive multi-tab interface (Data ▸ Clean ▸ Visualize ▸ Model)

---

## 🚀 Installation

1. **Clone** the repo:
   ```bash
   git clone https://github.com/your-username/business-analyst-gui.git
   cd business-analyst-gui
2. Create virtual environment (recommended):

python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate

3. Install dependencies:

pip install -r requirements.txt

   

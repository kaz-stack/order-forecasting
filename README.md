# order-forecasting
Time Series Order Forecasting using ARIMA

This project demonstrates **order demand forecasting** for a restaurant using **time series analysis** techniques such as **ARIMA** and **Facebook Prophet**.  
The goal is to predict future order quantities based on historical data trends, seasonality, and residual components using the dummy dataset `the_burger_spot.csv`.  


## Project Workflow  

| Step | Description |
|------|--------------|
| **1. Data Loading** | Loaded the dataset using pandas, parsed dates using `parse_dates=['Date']`, and set the `Date` column as index for time-series analysis. |
| **2. Exploratory Data Analysis (EDA)** | Checked missing values, visualized trends, and analyzed seasonality and patterns in restaurant orders. |
| **3. Model Building** | Built and compared two forecasting models — **ARIMA** (AutoRegressive Integrated Moving Average) and **Prophet** (Additive Model by Meta). |
| **4. Model Evaluation** | Evaluated both models using **Mean Squared Error (MSE)** and **Root Mean Squared Error (RMSE)**. |
| **5. Forecast Visualization** | Visualized actual vs. predicted values with trend lines, confidence intervals, and future projections. |

---

## 🛠️ Tech Stack  

| Category | Tools Used |
|-----------|-------------|
| **Programming Language** | Python 🐍 |
| **Data Handling & Analysis** | pandas, numpy |
| **Visualization** | matplotlib, seaborn |
| **Modeling** | statsmodels, pmdarima, prophet |
| **Environment** | Jupyter Notebook / VS Code |
| **Version Control** | Git & GitHub |

---

## ⚙️ Installation & Setup  

To run this project locally, follow these steps:

```bash
# Clone this repository
git clone https://github.com/kaz-stack/order-forecasting.git


# (Optional) Create a virtual environment
python -m venv venv
venv\Scripts\activate     # On Windows
source venv/bin/activate  # On Mac/Linux

# Install dependencies
pip install -r requirements.txt


* License:
This project is licensed under the MIT License. See the LICENSE file for details.

This project presents a predictive analytics solution for coal production in open-pit mines using time series forecasting and real-time machine performance data. It aims to improve operational efficiency by forecasting production, analyzing demand-supply gaps, and identifying key factors affecting productivity.
🔍 Project Overview

Coal mining operations often face challenges such as unpredictable demand, machinery inefficiencies, and productivity losses. This project uses historical data and modern forecasting techniques to:

- Predict daily coal production.
- Identify patterns in low productivity.
- Compare coal production with real-time demand (GAP analysis).
- Enable data-driven planning and resource allocation.
- 
 📊 Features
- 📈 **Time Series Forecasting**: Models like ARIMA, SARIMA, and SARIMAX are used to predict future coal output.
- 🛠️ **Breakdown Prediction**: Machine health indicators help detect potential failures in advance.
- 🧠 **Root Cause Analysis**: Identify factors causing low productivity—weather, equipment, shifts, etc.
- 🧾 **Model Evaluation**: Metrics like MAE, RMSE, MAPE, and R² used to rank model performance.
- 🔁 **Feedback Loop**: Models auto-update when performance drops, ensuring reliability.
- 📉 **GAP Analysis**: Compares predicted production with actual demand to minimize shortfalls.
- 🌱 **Sustainability Dashboard**: Monitors metrics like CO₂ reduction and energy savings.
🛠️ Technologies Used
- Python (Pandas, NumPy, Scikit-learn, Statsmodels)
- Jupyter Notebooks
- ARIMA, SARIMA, SARIMAX Models
- Matplotlib, Seaborn for Visualization
- Excel (.xlsx) for data inputs
- Git/GitHub for version control
 📌 How to Run
1. Clone the repo  
   ```bash
   git clone https://github.com/your-username/coal-production-forecasting.git
   cd coal-production-forecasting
   ```
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```
3. Open notebooks  
   ```bash
   jupyter notebook notebooks/project_model_building.ipynb
   ``
4. View results and visualizations in the notebook.
 📈 Sample Results
- Best performing model: **AR (Auto-Regressive)** with lowest MAE and RMSE.
- Forecasting charts, machine performance logs, and GAP analysis outputs available in the notebooks.
 Key Insights
- Production dips often correlate with poor weather or equipment breakdowns.
- ARIMA and SARIMA models give strong forecasting results when tuned properly.
- Real-time monitoring of machine data can significantly reduce breakdown frequency.

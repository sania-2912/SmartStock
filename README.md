# SmartStock
This project focuses on solving a real-world supply chain challenge by implementing AI-powered demand forecasting using open-source tools. Accurate demand prediction is crucial for minimizing waste, reducing storage costs, and improving customer satisfaction. 
The application utilizes Streamlit for a user-friendly frontend interface and Ollama for local LLM (Language Model) processing. It allows users to upload their datasets, get time-series based demand predictions, and visualize trends interactively. Our notebook-based backend ensures transparency and replicability of all results.

SmartStock-AI/
│
├── demand_forecasting.ipynb
├── inventory_monitoring.ipynb
├── pricing_optimization.ipynb
├── smartstock_agents.py
├── README.md
└── datasets/
    ├── demand_forecasting.csv
    ├── inventory_monitoring.csv
    └── pricing_optimization.csv

Demand-Forecasting:
1. Import Libraries
2. Load Dataset
3. Data Pre-processing
   - Handle missing values
   - Encode categorical
   - Scale if needed
4. Exploratory Data Analysis (EDA)
   - Histograms, boxplots
   - Correlations
5. Train-Test Split
6. Train Model
7. Evaluate Model
8. Forecast Future Demand (if time-series)
9. Save Model

Inventory-Optimization:
Import Libraries
Load Dataset
Data Pre-processing
Handle missing values
Encode categorical
Normalize stock-related features
Exploratory Data Analysis (EDA)
Stock levels, shortages
Correlation with demand
Define Optimization Constraints
Apply Optimization Algorithm
Evaluate Optimization Results
Simulate Inventory Scenarios
Save Optimization Model

Pricing-Optimization:
Import Libraries
Load Dataset
Data Pre-processing
Handle missing values
Encode categorical
Scale prices if needed
Exploratory Data Analysis (EDA)
Price vs demand
Correlation with revenue
Train-Test Split
Train Pricing Model
Evaluate Model
Optimize Prices for Profit
Save Pricing Strategy





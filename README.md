# DTDC Courier Analytics

Logistics analytics project examining shipment patterns, delivery performance, and revenue trends using Python, Looker Studio, and geospatial visualization.

## Introduction
DTDC is one of the leading courier and parcel delivery companies in India, offering national and international logistics services.  
This project focuses on analyzing real operational data from DTDC to identify patterns, evaluate logistics performance, and propose optimizations that improve customer experience while reducing operational costs.

## Dataset
Source: [Kaggle – DTDC Courier Dataset](https://www.kaggle.com/datasets/ravindrasinghrana/dtdc-courier-dataset)  
The dataset includes:
- **Origin & destination data:** city, state, postal code.
- **Weights:** actual, volumetric, and chargeable.
- **Shipping modes:** surface, air, express.
- **Costs & charges:** base tariff, value-added services.
- **Dates & signatures:** booking, delivery, confirmations.
- **Shipment status:** documents, goods, delays.

## Project Objectives
1. Measure delivery performance and punctuality.
2. Identify the most frequent routes and their associated costs.
3. Analyze weight and tariff patterns to propose optimizations.
4. Detect opportunities for cost reduction and time improvement.

## Tools & Technical Approach
- **Python:** Pandas, NumPy, Matplotlib, Seaborn, NetworkX.
- **Techniques:** data cleaning, EDA, categorical encoding, graph modeling.
- **Algorithms:** Dijkstra’s shortest path, network centrality analysis.
- **Visualization:** Looker Studio interactive dashboard.

## Key Steps
1. Converted date formats and handled missing values.
2. Created derived metrics such as `delivery_time` and `profit_margin`.
3. Performed exploratory data analysis to identify distributions, correlations, and outliers.
4. Modeled the logistics network as a directed graph to optimize routes.
5. Identified strategic hubs using centrality measures.
6. Designed a Looker Studio dashboard to visualize KPIs and logistics performance.

## Results
- Improved understanding of delivery delays and cost drivers.
- Identified top-performing and underperforming routes.
- Detected high-impact hubs for strategic planning.
- Proposed operational changes to reduce costs and improve delivery times.

📄 **[Full Report (PDF)](DTDC_Courier_Analytics.pdf)**  
📊 **[Looker Studio Dashboard](https://lookerstudio.google.com/u/0/reporting/7f86f740-d542-47ac-b9fa-e6b5fe8ed65c/page/HRcTF)**

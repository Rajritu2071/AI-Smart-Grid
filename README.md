# AI-Smart-Grid

> ML-driven energy distribution system with real-time load balancing and anomaly detection

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)
![ML](https://img.shields.io/badge/Machine%20Learning-scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)
![Hackathon](https://img.shields.io/badge/Sharda%20Technovation-Winner%20🏆-gold?style=flat)

---

## Overview

AI-Smart-Grid is an intelligent energy management system that uses machine learning to optimize power distribution across a grid network. Built and won at **Sharda Technovation Hackathon** competing against 200+ teams.

The system predicts energy demand, detects anomalies in real-time, and automatically reroutes power to prevent outages — making energy grids smarter and more resilient.

---

## Key features

- **Demand forecasting** — ML models predict energy consumption patterns across grid nodes
- **Real-time anomaly detection** — Flags faults and irregular consumption before they cascade
- **Automated load balancing** — Dynamically redistributes power to prevent overloads
- **Grid telemetry dashboard** — Live visualization of grid health and energy flow
- **IoT sensor integration** — Collects real-time data from distributed grid sensors

---

## Tech stack

- **Python** — Core ML pipeline and data processing
- **scikit-learn** — Demand forecasting and anomaly detection models
- **React** — Real-time monitoring dashboard
- **IoT integration** — Sensor data collection and processing
- **Pandas / NumPy** — Data analysis and feature engineering

---

## Project structure

```
AI-Smart-Grid/
├── src/
│   ├── models/           # ML models for demand forecasting & anomaly detection
│   ├── grid/             # Grid simulation and load balancing logic
│   ├── api/              # Backend API for dashboard communication
│   └── iot/              # IoT sensor data ingestion
├── dashboard/            # React-based monitoring dashboard
├── data/                 # Sample grid telemetry datasets
├── notebooks/            # EDA and model training notebooks
└── README.md
```

---

## How it works

```
IoT Sensors → Data Ingestion → ML Models → Decision Engine → Grid Control
                                    ↓
                            Anomaly Detection
                                    ↓
                          Real-time Dashboard
```

1. Sensors collect live energy consumption data across grid nodes
2. ML pipeline processes and predicts demand for next time window
3. Anomaly detection flags unusual patterns
4. Decision engine automatically rebalances load
5. Dashboard visualizes everything in real-time

---

## Results

- Won **Sharda Technovation Hackathon** against 200+ competing teams
- Demonstrated real-time anomaly detection with high accuracy
- Achieved significant reduction in simulated grid overload events

---

## Getting started

```bash
# Clone the repo
git clone https://github.com/Rajritu2071/AI-Smart-Grid.git
cd AI-Smart-Grid

# Install dependencies
pip install -r requirements.txt

# Run the system
python src/main.py

# Launch dashboard
cd dashboard && npm install && npm start
```

---

## Author

**Raj (Rituraj)** — AI/ML Engineer · CSE Undergrad  
[![X](https://img.shields.io/badge/X-@Rajritu2071-000000?style=flat&logo=x&logoColor=white)](https://x.com/Rajritu2071)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-rajritu2071-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/rajritu2071)

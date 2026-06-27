# 🚚 Agentic AI-Driven Optimization for Intelligent Supply Chain Optimizer

## 📌 Project Overview
I built this end-to-end platform to explore how Agentic AI can optimize supply chain logistics. Instead of relying on static models, I developed autonomous AI agents that simulate real-world logistics. My system dynamically routes resources, predicts demand, and manages inventory to keep supply chain operations stable and cost-effective.

## ⚠️ Problem Statement
Supply chains often break down when faced with unexpected delays, route disruptions, or sudden demand spikes. Traditional analytics models struggle to adapt to these changes in real-time. I wanted to solve this by creating a multi-agent system where AI continuously analyzes live data and makes instant, autonomous decisions to prevent bottlenecks and reduce operational costs.

## 🎯 Key Features & My Contributions
* **Multi-Agent Simulation:** I wrote custom AI agents (`agent.py`) capable of analyzing real-time disruptions and making independent routing decisions.
* **Predictive Demand Forecasting:** I built machine learning models (`forecaster.py`) that analyze historical data to predict future inventory needs accurately.
* **Dynamic Route Optimization:** Developed resource allocation algorithms (`optimizer.py`) focused on minimizing logistics costs and improving delivery speed.
* **Interactive Analytics Dashboard:** Designed and integrated a frontend UI to visualize agent behaviors, simulation metrics, and overall network health in real-time.

## 🛠️ Technical Expertise 
* **Backend:** Python, Multi-Agent Systems (MAS), Predictive Modeling, Optimization Algorithms.
* **Frontend:** JavaScript, HTML5, CSS3, Data Visualization.
* **Core Focus:** Data Analytics, Supply Chain Analytics, Machine Learning, Real-time processing,Pipeline automation and Problem Solving.

## 📂 Project Structure
```text
├── backend/
│   ├── agent.py         # AI Agent logic and decision-making
│   ├── forecaster.py    # Predictive analytics and demand forecasting
│   ├── optimizer.py     # Route and logistics optimization models
│   ├── app.py           # Backend server and API endpoints
│   └── data_loader.py   # Data ingestion and preprocessing
├── frontend/
│   ├── js/
│   │   ├── api.js               # Frontend-backend communication
│   │   ├── simulationManager.js # Manages UI state and AI simulation updates
│   │   └── chartConfig.js       # Data visualization configurations
│   ├── index.html       # Dashboard UI
│   └── style.css        # Styling
└── README.md

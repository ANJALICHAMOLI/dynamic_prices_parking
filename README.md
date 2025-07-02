# Dynamic Pricing for Urban Parking Lots

## 🚀 Overview
This project addresses the problem of inefficient urban parking due to static pricing. By leveraging real-time data and machine learning logic, we implement a dynamic pricing engine that adjusts prices for 14 parking lots based on demand, traffic, queue, vehicle type, and nearby competitors. Developed for the Summer Analytics 2025 Capstone by Consulting & Analytics Club × Pathway.

## 🛠 Tech Stack
- **Python** (Core logic)
- **Pandas & NumPy** (Data preprocessing and computation)
- **Pathway** (Real-time data simulation)
- **Bokeh** (Live visualization)
- **Google Colab / Kaggle** (Execution environment)

## 🧠 Architecture Diagram
```mermaid
graph TD
    A[Raw Dataset (CSV)] --> B[Preprocessing with Pandas]
    B --> C1[Model 1: Baseline Pricing]
    B --> C2[Model 2: Demand-Based Pricing]
    B --> C3[Model 3: Competitive Pricing]
    C1 --> D[Dynamic Pricing Output]
    C2 --> D
    C3 --> D
    D --> E[Visualization via Bokeh]
    D --> F[Export CSV Report]
```

## 📂 Repository Structure
```
📁 root
├── dynamic_parking_pricing.ipynb as 2.py      # Complete working code
├── dataset_capstone_project.csv        # Input dataset
├── final_dynamic_pricing_output.csv    # Output from simulation
├── README.md                           # You are here
```

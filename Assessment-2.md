# WasteWise – Project Progress Report 1

## 📌 Overview
WasteWise is a smart inventory and waste management system for restaurants. It uses AI forecasting, expiry alerts, and waste tracking to reduce food waste and improve efficiency. This report expands on the original proposal with detailed design and technical documentation.

# 🗒 Detailed User Stories


## 🖼 Wireframes
Prepared for:
- Login/Registration  
- Inventory Dashboard  
- Waste Logging Page  
- Analytics Dashboard  
- AI Suggestions Panel  

## 🗄 Database Schema
![Database Schema](assets/DatabaseSchema.png)


## 🏗 Software Architecture
![Software Architecture](assets/SoftwareArchitecture.png)


## 🤖 AI Component
The AI module, built in Python with Scikit-learn, TensorFlow, and FastAPI, provides:
- **Demand Forecasting** – Predicts stock needs from sales/waste history.
- **Waste Analysis** – Detects patterns and suggests fixes.
- **Expiry Prioritization** – Smart alerts based on expiry and usage trends.
- **Restocking Guidance** – POS-driven, seasonal-aware recommendations.  
Integrated as a microservice, it sends predictions to the backend and displays actionable insights on the dashboard.

## 🛠 Tools & Platforms
- **Version Control**: GitHub  
- **Tracking Tool**: Microsoft Planner  
- **Testing**: Jest, Mocha, Postman, Supertest  

## 🧪 Test Plan
Covers:
- Unit, Integration, Functional, and UAT  
Example UAT: Verify expiry alerts when item expiry ≤ 1 day.

## 📂 Tracking
All tasks are managed in **Microsoft Planner**, with buckets for each module, assigned owners, and tracked progress toward deadlines.

# WasteWise – Project Progress Report 1

## 📌 Overview
WasteWise is a smart inventory and waste management system for restaurants. It uses AI forecasting, expiry alerts, and waste tracking to reduce food waste and improve efficiency. This report expands on the original proposal with detailed design and technical documentation.

## 🗒 Detailed User Stories
- As a manager, I want to scan product barcodes so that I can update stock quickly.
- As a chef, I want expiry alerts so that I can use ingredients before they spoil.
- As an admin, I want waste reports so that I can comply with regulations.

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
AI uses historical sales and waste data to predict demand and suggest restocking levels.

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

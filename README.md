# Industrial Equipment Predictive Maintenance & Asset Management Agent

## Overview

This project is an automated predictive maintenance system built using **n8n**. It collects machine data from sensors, databases, and ERP systems, analyzes equipment health using AI, calculates risk levels, and automatically creates maintenance work orders when a potential failure is detected.

The main goal is to reduce machine downtime and improve maintenance efficiency.

---

## Technologies Used

- **n8n** – Workflow Automation
- **PostgreSQL** – Asset and Work Order Database
- **SAP ERP** – Enterprise Data Integration
- **AI Agent** – Failure Prediction and Maintenance Recommendations
- **Grafana** – Monitoring Dashboard
- **Email, Microsoft Teams, Slack** – Notifications
- **IoT Sensors** – Real-time Equipment Data Collection

---

## Workflow

### 1. Data Collection
The workflow collects:
- Asset information from PostgreSQL
- Equipment records from SAP ERP
- Runtime data from machines
- IoT sensor data (temperature, vibration, pressure, etc.)
- Previous maintenance history

### 2. Data Validation
Collected data is checked for missing or incorrect values before processing.

### 3. AI Analysis
The AI Maintenance Agent analyzes machine conditions and predicts possible failures based on sensor readings and historical records.

### 4. Risk Assessment
A Risk Scoring Engine classifies equipment into:
- Low Risk
- Medium Risk
- High Risk
- Critical Risk

### 5. Automated Maintenance Actions
For High or Critical risk assets:
- Maintenance work orders are generated automatically
- Technicians are assigned
- Notifications are sent through Email, Teams, and Slack

### 6. Tracking and Reporting
Completed maintenance activities are recorded in the database and included in weekly reports and management dashboards.

---

## Dashboard Metrics

The dashboard displays:
- Equipment Uptime
- MTBF (Mean Time Between Failures)
- Active Work Orders
- Downtime Hours
- Critical Alerts
- Asset Health Distribution
- Risk Heatmap

---

## Benefits

- Reduces unexpected equipment failures
- Improves maintenance planning
- Increases equipment reliability
- Automates maintenance workflows
- Provides real-time monitoring and reporting

---

## Conclusion

This project combines Industrial IoT, AI, database systems, and workflow automation to create a smart predictive maintenance solution. It helps industries monitor equipment health, predict failures before breakdowns occur, and automate maintenance operations efficiently.

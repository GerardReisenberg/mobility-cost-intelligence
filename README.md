
# Mobility Cost Intelligence Platform

## 🚀 Overview
The Mobility Cost Intelligence Platform is an API-driven system that compares vehicle operating costs across:
- Electric Vehicles (EV)
- Petrol
- Diesel
- Hybrid

The platform enables users to:
- Calculate cost per trip and per km
- Compare vehicle types side-by-side
- Run scenario simulations (fuel price, electricity tariffs)

---

## 🎯 Objective
To provide a **decision intelligence platform** that helps users:
- Reduce mobility costs
- Make data-driven fleet decisions
- Evaluate EV transition scenarios

---

## ⚙️ Current Scope (MVP)
- Cost calculation engine
- Comparison engine
- Scenario modelling
- API-first backend (FastAPI → AWS Lambda later)

---

## 🧱 Architecture (MVP)

```text
Local (Current)
--------------
FastAPI backend
Python cost engine
JSON-based inputs

Future (AWS)
------------
API Gateway
Lambda (Python)
CloudWatch
S3 / DynamoDB (optional)
``

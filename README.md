# E-Commerce Shipment Data Pipeline

A hands-on data engineering project transitioning 100 e-commerce shipment logs from Google Sheets into a structured NoSQL database (MongoDB).

## 🚀 Overview
This pipeline models, cleans, and ingests e-commerce shipment data. It enables automated tracking of logistics operations, shipping costs, and delivery statuses.

## 🛠️ Tech Stack & Tools
- **Google Sheets**: Data logic, formula checks, and preliminary structured dataset.
- **Python**: Automation, data cleaning, and dataset processing.
- **MongoDB Compass**: NoSQL database storage for nested log structures.

## 📊 Dataset Structure
The dataset contains 100 shipment records with key metrics:
- `Shipment_ID`: Unique order tracking identifier
- `Carrier`: Logistics partner (DPD, DHL, Omniva, etc.)
- `Dispatch_Date`: Order fulfillment timestamp
- `Shipping_Cost_EUR`: Delivery cost in Euros
- `Delivery_Status`: Real-time status (Delivered, In Transit, Exception)


# 🏍️ The Future of B2B Shopping: Personalized, Predictive, Powerful
<img width="2184" height="168" alt="image" src="https://github.com/user-attachments/assets/a90cf92a-0ab7-4ade-959f-aff4317186d3" />


<div align="center">

![Vahan Bazar Logo](https://img.shields.io/badge/Vahan%20Bazar-Two%20Wheeler%20Marketplace-blue?style=for-the-badge&logo=motorcycle)

[![React](https://img.shields.io/badge/React-18.2.0-61DAFB?style=flat-square&logo=react)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-Express-green?style=flat-square&logo=node.js)](https://nodejs.org/)
[![MySQL](https://img.shields.io/badge/Database-MySQL-orange?style=flat-square&logo=mysql)](https://mysql.com/)
[![Tailwind CSS](https://img.shields.io/badge/Styling-Tailwind%20CSS-38B2AC?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)

**AI-powered recommendation engine for B2B retailers – personalized, real-time, and scalable.**

</div>

---

## 📋 Table of Contents

- [🎯 Overview](#-overview)
- [✨ Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [🏗️ Project Structure](#️-project-structure)
- [🔧 API Endpoints](#-api-endpoints)
- [📊 Database Schema](#-database-schema)
- [🚀 Deployment](#-deployment)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [🙏 Acknowledgments](#-acknowledgments)

---

## 🎯 Overview

**Qwipo Recommendation System is an AI-powered engine designed to transform B2B marketplace product discovery. It delivers personalized product suggestions based on retailer interactions, purchase history, and seasonal trends..

### 🎪 Key Highlights

**User Behavior Analytics – Track retailer browsing and purchase patterns.

**Purchase Pattern Recognition – Detect seasonal cycles and category preferences.

**Hybrid Recommendation Engine – Collaborative + content-based filtering.

**Real-time API Delivery – Recommendations served in <200ms.

**Mobile-Ready Integration – Easy embedding into Qwipo’s app.
---

## ✨ Features

### 🏠 **Core Features**
- Intelligent Product Recommendations – Personalized suggestions per retailer.
- Behavior Tracking – Logs interactions for analytics and future predictions.
- ML-Powered Hybrid Engine – Combines collaborative and content-based filtering.
- Real-Time API Responses – Sub-200ms latency for instant suggestions.
- Dashboard Interface – Interactive frontend for testing and demo.

### 📊 Analytics Features**
- **Retailer Segmentation**: Classify based on purchase behavior
- **Trend Detection**: Seasonal and category-level insights.
- **AOV & Retention Metrics**: Measure business impact of recommendations.


---

## 🛠️ Tech Stack

### **Backend/Services**
- **FastAPI** - API development
- **Python** - Recommendation engine logic
- **PostgreSQL** - Relational database for transactional data
- **MongoDB** - Product catalog storage
- **Redis** - Caching for fast retrieval
- **TensorFlow / PyTorch** - ML models
- **Axios** - HTTP client

### **Infrastructure**
- **Docker** - Containerized services
- **Docker Compose** - Multi-service orchestration
- **Microservices Architecture** - Recommendation & analytics services

### **APIs**
- **REST & GraphQL** 
- **WebSocket support for real-time recommendations**


---

## 🏗️ Project Structure

```
qwipo-recommendation-system/
├── services/
│   ├── recommendation/
│   │   ├── Dockerfile
│   │   ├── main.py
│   │   ├── requirements.txt
│   │   ├── collaborative_filtering.py
│   │   ├── content_based.py
│   │   ├── hybrid_engine.py
│   │   └── database.py
│   └── analytics/
│       ├── Dockerfile
│       ├── main.py
│       ├── requirements.txt
│       └── analytics_engine.py
├── shared/
│   ├── models/
│   │   └── database_models.py
│   └── cache/
│       └── redis_manager.py
├── infrastructure/
├── tests/
├── docker-compose.yml
├── requirements.txt
└── .env

---

## 🔧 API Endpoints

### **Authentication**
```
GET    /recommendations          # Get personalized product recommendations
GET    /ml_recommendations       # Get ML-powered insights
POST   /interactions             # Log retailer interactions
POST   /retailers                # Add / update retailer info
POST   /products                 # Add / update products
```

### **Analytics Service**
```
GET    /analytics/summary        # Retailer behavior summary
GET    /analytics/trends         # Trend detection metrics
GET    /analytics/aov            # Average Order Value insights

```

---


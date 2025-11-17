# Price_Comparateur

This repository contains the full project for our **Price Comparator application**, which helps users compare prices across flights, hotels, and supermarket products. Each branch in this repository corresponds to a specific module of the project.

---

## 🌿 Branch Overview

| Branch Name           | Description                                                |
|-----------------------|------------------------------------------------------------|
| `master`              | Main base branch                                           |
| `KAA_app`             | Fullstack web app using Angular (frontend) + Flask (API)   |
| `ML_Hotels`           | Machine learning models for hotel price analysis           |
| `PowerBI_Supermarket` | Supermarket price dashboards in Power BI                  |
| `Hotels-Power-BI`     | BI visualizations for hotels (Power BI)                    |
| `Power-BI-Flights`    | BI visualizations for flight data (Power BI)               |



Welcome to the official repository of the **Price Comparator Project**, a full-stack web application designed to compare prices across **products**, **hotels**, and **flights**, offering users real-time data, predictive analytics, and intelligent recommendations.

---

## 📌 Project Overview

With the growing complexity of online shopping and travel booking, consumers often face difficulty comparing prices across various platforms. Our solution addresses this challenge by offering an integrated platform that:

- Collects and consolidates data from multiple sources
- Provides real-time and historical pricing information
- Delivers intelligent insights through machine learning
- Visualizes key trends via dynamic dashboards

---

## 🧱 Tech Stack

| Layer         | Technology Used          |
|---------------|---------------------------|
| **Frontend**  | Angular 15+ (Standalone Components) |
| **Backend**   | Flask (Python, REST API) |
| **Database**  | Microsoft SQL Server |
| **ETL**       | Talend Open Studio |
| **BI Layer**  | Power BI |
| **Dev Tools** | VS Code, XAMPP, GitHub |

---

## 🚀 Key Features

- 🛒 **Product Price Comparison** (Carrefour, MG, Géant)
- 🏨 **Hotel Price Scraper** (Kayak)
-✈️ **Flight Price Scraper**
- 🧠 **ML Models**: Clustering, Regression, Recommendation, Time Series Forecasting
- 📊 **Interactive Dashboards** (Power BI)
- 🔐 **Role-Based Access** for different users
- 📦 **Real-time Data Integration** using ETL pipelines (Talend)

---

## 🧪 Machine Learning Integration

We implemented several models using Python:

- **Clustering** to group pricing behavior
- **Regression** for price prediction
- **Hybrid Recommendation System** for personalized suggestions
- **Time Series Analysis (SARIMA)** for future trend forecasting

All models are serialized and integrated into the Flask backend for real-time access.

---

## 🛠️ How to Run the Project Locally

### 🔹 Backend (Flask)
1. Clone the repository.
2. Navigate to `/backend`.
3. Create and activate a virtual environment.
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Start the backend server:
   ```bash
   python app.py
   ```

### 🔹 Frontend (Angular)
1. Navigate to `/frontend`.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   ng serve
   ```

> **Note**: The Angular app uses a proxy to route API calls to Flask.

---

## 🧰 Data Flow & Architecture

```plaintext
[Web Scrapers] → [Talend ETL] → [SQL Server Data Warehouse] → [Flask API] → [Angular Frontend] → [User Dashboards]
                                                  ↓
                                         [ML Models + Power BI]
```

---

## 🔍 Folder Structure

```plaintext
├── backend/
│   ├── app.py
│   ├── models/
│   ├── routes/
│   └── recommender_model.pkl
├── frontend/
│   ├── src/app/
│   └── angular.json
├── talend_jobs/
├── powerbi_dashboards/
├── README.md
└── requirements.txt
```

---



## 🌍 Project Deployment

- Local development using **XAMPP** (MySQL Server) and **Angular CLI**
- Future-ready for deployment to **Azure**, **Heroku**, or **Dockerized environments**

---

## 📈 Business Value

This project goes beyond a basic comparator by offering a complete **decision-support system**, empowering users to:
- Discover best prices across platforms
- Track price trends
- Receive personalized recommendations
- Make smarter and faster purchase decisions

---

## 👥 Team Members

- **Mohamed Aziz Labidi / Mohamed Amine Hedhili / Omar Hamdi / Rania Ben Hmida / Eya Hammami / Cyrine Chaouch** – Backend & Data Integration  




## 📣 Contact

For more information or collaboration, feel free to reach out via:
- LinkedIn: [Mohamed Aziz Labidi / Mohamed Amine Hedhili / Omar Hamdi / Rania Ben Hmida / Eya Hammami / Cyrine Chaouch ]
- Email: [keepallaffordable@gmail.com]

---

## 📌 License

This project is open for educational and non-commercial use only. For other uses, please contact the author.

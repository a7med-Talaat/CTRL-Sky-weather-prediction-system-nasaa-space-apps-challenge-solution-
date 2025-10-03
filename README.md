# 🛰️ CTRL + Sky: NASA GES DISC Weather Explorer

**CTRL + Sky** is an advanced, AI-powered weather prediction system built to analyze historical patterns and forecast future conditions for any global location. It leverages simulated data access from **NASA's Goddard Earth Sciences Data and Information Services Center (GES DISC)** and modern machine learning techniques, all presented in a sleek, interactive, space-themed web application.

---

## ✨ Key Features

### 1. Advanced AI-Powered Prediction Engine

The core application provides sophisticated weather analysis and prediction based on location and date.

* **Global Location Analysis:** Select any point on the **interactive Leaflet map** or use the **Nominatim Geocoding search**.
* **Historical Data Integration:** Simulates analysis of historical weather patterns from **NASA GES DISC datasets** (e.g., MERRA-2, GPCP) and a Kaggle Global Temperatures Dataset, allowing selection of a data training range (5 to 30 years).
* **Multi-Model Prediction:** For future dates, the system utilizes one of four simulated advanced AI models:
    * **Basic Climate Model**
    * **Machine Learning Model** (Simulated Neural Network)
    * **Hybrid AI Model** (Combines multiple approaches)
    * **Ensemble Model (Advanced):** Includes **Monte Carlo Simulation** and **Bayesian Updating** for highly accurate predictions with uncertainty quantification.
* **Detailed Prediction Metrics:** Provides key performance indicators for predictions, including the **Confidence Score**, **Error Margin (°C)**, **Model Accuracy (%)**, and **Training Time (ms)**.

### 2. Interactive Visualization & Analysis

Results are presented with a focus on scientific detail and clarity.

* **Probability Analysis:** Displays the likelihood of five key weather states in a **Radar Chart** and visually engaging probability circles: **Clear Skies, Cloudy, Very Windy, Very Wet,** and **Uncomfortable (Extreme Temperatures)**.
* **Temperature Trend Chart:** Visualizes long-term temperature trends, including average, maximum, and minimum recorded temperatures and the overall climate change over the selected range.
* **Analysis Summary & Data Preview:** Provides a concise, natural-language summary of the AI model's findings and a toggleable, structured **JSON preview** of the raw prediction data and model metrics.
* **Data Download:** Allows users to download the full prediction data in **CSV** and **JSON** formats.

### 3. Engaging "Weather Personality" Game

A fun, interactive quiz to personalize the user experience and connect them with the weather data.

* **7-Question Quiz:** Answers are scored to determine which of the four seasons matches the user's weather preferences.
* **Personalized Results:** Displays a detailed "Season Personality" with an icon, title, description, and key traits.

---

## 💻 Technology Stack

| Category | Technology | Purpose |
| :--- | :--- | :--- |
| **Frontend** | HTML5, CSS3 | Structure and custom space-themed UI/UX. |
| **Styling** | **Bootstrap 5.3**, Font Awesome | Responsive layout and cosmic-themed components. |
| **Mapping** | **Leaflet.js** | Interactive map for location selection. |
| **Charting** | **Chart.js** | Data visualization for probability and temperature trends. |
| **Logic** | Pure JavaScript (ES6+) | All application logic, including the AI model simulations and game functions. |
| **APIs** | OpenStreetMap Nominatim | Geocoding service for location search. |

---

## 🖼️ Preview

<img width="1280" height="638" alt="image" src="https://github.com/user-attachments/assets/ce512c0c-5fb5-4539-88eb-28eb7c49d8a1" />


---

## 🚀 Getting Started

To run this project locally, simply save the code as an HTML file (e.g., `index.html`) and open it in any modern web browser. All dependencies (Bootstrap, Leaflet, Chart.js, Font Awesome) are loaded via CDN.

```bash
# Clone the repository (if applicable)
# git clone [repo-url]

# Or, just save the provided HTML code to a file named index.html
open index.html

# 🌍 Google Play Store Global Install Trends Dashboard

> An interactive data visualization project that analyzes global Google Play Store app installations across countries and top-performing categories using Plotly Choropleth Maps.

---

# 📑 Table of Contents

- <a href="#project-title">Project Title</a>
- <a href="#brief-summary">Brief One Line Summary</a>
- <a href="#overview">Overview</a>
- <a href="#problem-statement">Problem Statement</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools-and-technologies">Tools and Technologies</a>
- <a href="#methods">Methods</a>
- <a href="#key-insights">Key Insights</a>
- <a href="#dashboard-model-output">Dashboard / Output</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#how-to-run-this-project">How to Run this Project?</a>
- <a href="#results-conclusion">Results & Conclusion</a>
- <a href="#future-work">Future Work</a>
- <a href="#author-contact">Author & Contact</a>

---

<h2 id="project-title">📌 Project Title</h2>

# Google Play Store Global Install Trends Dashboard

---

<h2 id="brief-summary">📝 Brief One Line Summary</h2>

An interactive Plotly dashboard that visualizes Google Play Store app installation trends across countries and top-performing categories using animated global choropleth maps.

---

<h2 id="overview">📖 Overview</h2>

This project analyzes Google Play Store application data to identify the most popular app categories based on installation counts and visualize their global reach.

The dashboard processes installation statistics, filters the highest-performing categories, assigns geographical regions, and presents insights through interactive choropleth maps.

A time-controlled visualization mechanism is also implemented to simulate restricted dashboard access during specific business hours.

---

<h2 id="problem-statement">⚠️ Problem Statement</h2>

With thousands of applications available across multiple categories, understanding global adoption trends becomes challenging.

This project aims to:

- Analyze installation trends across app categories
- Identify top-performing categories
- Visualize global app adoption patterns
- Generate geographical insights
- Create an interactive dashboard experience
- Simulate business-hour dashboard access

---

<h2 id="dataset">📂 Dataset</h2>

The project uses a Google Play Store dataset containing app-related information.

### Dataset Features

- App Name
- Category
- Rating
- Reviews
- Size
- Installs
- Price
- Content Rating

### Data Processing

The project performs:

- Install count cleaning
- Category filtering
- Country assignment
- Installation aggregation
- Dashboard visualization

---

<h2 id="tools-and-technologies">🛠️ Tools and Technologies</h2>

## Programming Language

- Python

## Libraries Used

- Pandas
- NumPy
- Plotly Express
- PyTZ
- Datetime

## Development Environment

- Jupyter Notebook
- VS Code

---

<h2 id="methods">⚙️ Methods</h2>

## 1. Data Cleaning

Installation counts were cleaned by:

- Removing commas
- Removing '+' symbols
- Converting values to numeric format
- Removing invalid entries

## 2. Category Filtering

Categories beginning with:

- A
- C
- G
- S

were excluded from analysis.

## 3. Top Category Selection

The top 5 categories were identified based on total installation counts.

## 4. Country Assignment

Random countries were assigned for visualization purposes:

- India
- United States
- Brazil
- Germany
- United Kingdom
- Canada
- Australia
- France
- Japan
- South Africa

## 5. Data Aggregation

Installation counts were aggregated by:

- Country
- Category

## 6. Highlight Generation

Applications were classified as:

- Above 1M Installs
- Below 1M Installs

## 7. Time-Based Dashboard Logic

The visualization is configured to display only between:

```text
6:00 PM IST → 8:00 PM IST
```

---

<h2 id="key-insights">📊 Key Insights</h2>

- A small number of categories contribute to the majority of app installations.
- Installation trends vary significantly across regions.
- Geographic visualization helps identify market opportunities.
- High-install categories dominate user engagement.
- Interactive dashboards improve analytical decision-making.

---

<h2 id="dashboard-model-output">📈 Dashboard / Output</h2>

## Dashboard Workflow

```text
Google Play Store Dataset
          ↓
Data Cleaning
          ↓
Category Filtering
          ↓
Top 5 Category Selection
          ↓
Country Assignment
          ↓
Install Aggregation
          ↓
Interactive Choropleth Dashboard
```

---

## Dashboard Features

### 🌍 Choropleth Map

Displays:

- Country-wise installs
- Category-wise installs
- Animated category transitions
- Installation intensity

### 🎯 Highlight Indicators

Apps categorized as:

- Above 1M Installs
- Below 1M Installs

### ⏰ Time-Based Access Control

Dashboard is visible only during:

```text
6 PM – 8 PM IST
```

---

<h2 id="project-structure">📁 Project Structure</h2>

```bash
Google_Play_Store_Dashboard/

│
├── task2.ipynb
├── google_play_store_dataset.csv
├── README.md
└── outputs/
```

---

<h2 id="how-to-run-this-project">🚀 How to Run this Project?</h2>

## Clone Repository

```bash
git clone https://github.com/yashrajmohanty03-ai/google-play-store-dashboard.git

cd google-play-store-dashboard
```

## Install Dependencies

```bash
pip install pandas numpy plotly pytz
```

## Run Notebook

```bash
jupyter notebook task2.ipynb
```

## Execute Notebook Cells

Run all cells sequentially to:

- Load dataset
- Clean installation data
- Filter categories
- Aggregate country-wise installs
- Generate choropleth dashboard

---

<h2 id="results-conclusion">📈 Results & Conclusion</h2>

## Results

The dashboard successfully:

- Processed Google Play Store installation data
- Identified top-performing categories
- Generated country-wise install statistics
- Visualized trends through animated choropleth maps
- Implemented time-based dashboard availability

## Output
![image alt](https://github.com/yashrajmohanty03-ai/Ev2/blob/5dc52f310a416d3f2c5317ec46237cc21a374e52/ev2.jpeg)

## Conclusion

This project demonstrates how data visualization techniques can transform raw installation data into actionable business insights. The combination of geographical mapping, category analysis, and interactive dashboards provides an effective way to understand app adoption trends worldwide.

---

<h2 id="future-work">🔮 Future Work</h2>

Future enhancements include:

- Real-time Google Play Store data integration
- Streamlit dashboard deployment
- Advanced market analytics
- Sentiment analysis integration
- User demographic insights
- Power BI integration
- Predictive install forecasting

---

<h2 id="author-contact">👨‍💻 Author & Contact</h2>

## Yashraj Mohanty

### Areas of Interest

- Data Analytics
- Data Visualization
- Business Intelligence
- Machine Learning

### Contact

- GitHub: https://github.com/yashrajmohanty03-ai
- LinkedIn: https:// linkedin.com/in/yashraj-mohanty
- Email: yashrajmohanty3@gmail.com
---

<p align="center">
⭐ If you found this project useful, consider giving it a star on GitHub!
</p>

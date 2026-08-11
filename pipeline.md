## 1. Data Collection
- APIs (SpaceX API)
- Web Scraping (Wikipedia launch data)
- Dataset (if available)

## 2. Data Wrangling
- Cleaning (missing values, duplicates)
- Imputing
- Outlier handling
- Define Target Variable (Class: landed / not landed)
- Define Independent Variables

## 3. EDA
- SQL-based Analysis (if using a DB)
- Visual Analysis (plots, distributions)
- Identify Relationships
- Correlation Analysis
- Feature Engineering
- Visual Analytics & Dashboards (Folium map, Plotly Dash)

## 4. Feature Preparation
- Encoding (categorical → numerical)
- Scaling / Normalizing

## 5. Model Development & Evaluation
- Train/Test Split
- Decide Model(s)       ─┐
- Fit and Predict        │
- Classify with Metrics  │  → GridSearchCV handles this
- Tune Hyperparameters  ─┘
- Compare Models
- Select Best Model

<div align="center">
  <a href="https://www.linkedin.com/in/alexander-rodriguez-/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://www.kaggle.com/al3xrods" target="_blank">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle Badge"/>
  </a>
</div>

---

### 👨‍💻 About Me
I am a **Computer Science student in my final semester**, specializing in **Data Science and Machine Learning**. I enjoy translating complex datasets into actionable business insights and building robust predictive models. My expertise spans Deep Learning, Geospatial Analysis, Time-Series Forecasting, and Classical Machine Learning.

---

### 🛠️ Technical Toolbox

| Category | Technologies |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) |
| **Machine Learning & Deep Learning** | ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Scikit-Learn](https://img.shields.io/badge/scikit_learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) |
| **Data Analysis & GIS** | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![GeoPandas](https://img.shields.io/badge/GeoPandas-15A2B8?style=flat-square&logo=pandas&logoColor=white) |
| **Visualization** | ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square) ![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=flat-square) |
| **Developer Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) |

---

## 🧠 Highlighted Data Science Projects

### 1. 🔬 Deep Learning & Computer Vision
#### [Chest X-Ray Pneumonia Classification](https://github.com/al3xrods/chest-xray-pneumonia)
*Developed a deep learning pipeline to classify pediatric chest X-rays, supporting clinical decision-making.*
* **Methodology**: Evaluated a custom Convolutional Neural Network (CNN) against transfer learning benchmarks (ResNet50, EfficientNetB0). Implemented image preprocessing, class weight balancing, and data augmentation (rotation, brightness, contrast adjustment) to handle class imbalance.
* **Results**: Achieved a **92.20% test accuracy** (93.41% train, 91.63% validation) using the custom CNN.
* **Tech Stack**: `TensorFlow` `Keras` `CNN` `Data Augmentation` `Scikit-Learn` `Matplotlib`

---

### 2. 🗺️ Geospatial Data Science
#### [Optimal Coffee Shop Location in Denver](https://app.datacamp.com/workspace/w/5acb88ba-3302-42e8-8a07-9c7f34ff9ba0)
*Conducted a geographic suitability analysis to identify the optimal neighborhood for establishing a new coffee shop.*
* **Methodology**: Utilized `GeoPandas` to map and analyze existing Starbucks locations in Denver, Colorado. Integrated census tract demographic data and shapefiles of Denver neighborhoods, performing spatial joins and coordinate mapping (EPSG:4326). Targeted neighborhoods with high concentrations of the primary demographic (ages 18–34).
* **Results**: Identified the top three underserved neighborhoods matching key demographic profiles, visualizing findings via interactive `Plotly` maps and `Contextily` basemaps.
* **Tech Stack**: `GeoPandas` `Contextily` `Plotly Express` `Seaborn` `Spatial Joins`

---

### 3. 🤖 Machine Learning & Natural Language Processing
#### [Predicting Christmas Movie Grossings](https://github.com/al3xrods/christmas-movie-prediction)
*Built an end-to-end regression model to predict the box office success of holiday movies using textual and tabular data.*
* **Methodology**: Performed NLP sentiment analysis on movie descriptions using `NLTK` VADER. Engineered a custom `Director_Success_Rate` feature using graph-based network analysis (`NetworkX`) of historical cast/director earnings and ratings. Constructed a robust `Scikit-Learn` pipeline using `ColumnTransformer`, `QuantileTransformer`, and `CountVectorizer` for text features.
* **Results**: Trained a `HistGradientBoostingRegressor` with absolute error loss, achieving a **Test MAE of 1.71M** (a massive reduction from the 56.86M baseline).
* **Tech Stack**: `Scikit-Learn` `NLTK (VADER)` `NetworkX` `HistGradientBoosting` `Feature Engineering`

#### [Reducing Hospital Readmissions](https://app.datacamp.com/workspace/w/1dbd970b-fdc5-4d03-88ae-37838aff7330)
*Developed a predictive model to identify high-risk patients likely to be readmitted within 30 days, optimizing resource allocation.*
* **Methodology**: Conducted exploratory data analysis on clinical features (e.g., A1C test results, age groups, medications). Preprocessed categorical features and handled class imbalance. Tuned hyperparameters using `RandomizedSearchCV` across multiple classifiers.
* **Results**: Optimized the model specifically for the **ROC-AUC metric (achieved 0.66)** to ensure balanced sensitivity.
* **Tech Stack**: `Scikit-Learn` `RandomizedSearchCV` `Supervised Classification` `Seaborn`

#### [Helping Reduce Employee Turnover](https://app.datacamp.com/workspace/w/ec5ae7a2-89e0-47db-9452-6110a89b56ad)
*Built a classification pipeline to predict employee churn and identify key drivers of turnover.*
* **Methodology**: Preprocessed imbalanced training data using `RandomOverSampler` to prevent data leakage. Trained and compared multiple classifiers, including Logistic Regression, Random Forest, AdaBoost, SVMs, and `XGBoost`.
* **Results**: Evaluated models using ROC-AUC and classification metrics to deliver a highly interpretable model indicating major churn risk factors.
* **Tech Stack**: `Scikit-Learn` `XGBoost` `Imbalanced-Learn (RandomOverSampler)` `ROC-AUC`

---

### 4. 📈 Statistics & A/B Testing
#### [Understanding Local Electricity Market](https://app.datacamp.com/workspace/w/af6be56a-687f-4ea3-8a0d-2a1dadb79655)
*Analyzed and forecasted energy prices in a local electricity market using time-series analysis.*
* **Methodology**: Assessed stationarity using the Augmented Dickey-Fuller (ADF) test. Performed STL (Seasonal and Trend decomposition using Loess) to isolate trends, seasonality, and residuals. Used Autocorrelation (ACF) and Partial Autocorrelation (PACF) to determine model orders.
* **Results**: Implemented `ARIMA` and `ARMA` models to forecast future energy prices.
* **Tech Stack**: `Statsmodels` `ARIMA` `Time Series Decomposition` `ADF Test` `Scipy`

#### [Impact of Website Redesign (A/B Testing)](https://github.com/al3xrods/Website_Redesign/blob/main/Website_Redesign.ipynb)
*Conducted statistical hypothesis testing on user conversion rates following a website redesign.*
* **Methodology**: Analyzed user behavior across a control group (original design) and multiple treatment groups (new designs). Conducted Chi-Square tests of independence and Fisher's exact tests to evaluate conversion rate differences.
* **Results**: Detected a statistically significant increase in conversion rates for a specific treatment group, providing data-backed recommendations for the redesign launch.
* **Tech Stack**: `A/B Testing` `Hypothesis Testing` `Chi-Square` `Fisher's Exact Test` `Scipy.stats`

#### [Customer Segments for Marketing Campaign](https://app.datacamp.com/workspace/w/66b04f38-08b7-4de4-b839-6f4da4d67275)
*Segmented a customer base to optimize targeting for an upcoming marketing campaign.*
* **Methodology**: Applied Singular Value Decomposition (SVD) for dimensionality reduction. Clustered the reduced feature space using `K-Means`. Used Chi-Square tests to validate the independence of demographic features across clusters.
* **Results**: Defined distinct, actionable customer personas to guide personalized marketing strategies.
* **Tech Stack**: `K-Means Clustering` `SVD` `Dimensionality Reduction` `Chi-Square Test`

---

## 🐍 Python Automation & Utilities

#### 🖼️ [Unsplash Wallpaper Downloader](https://github.com/al3xrods/wallpaper_donwloader)
* A CLI automation tool that downloads themed wallpapers from Unsplash.
* **Features**: Automatically manages a local wallpaper directory by purging older files and moving new downloads, ensuring a fresh desktop background without manual overhead.
* **Tech Stack**: `Python CLI` `Requests` `OS Integration`

#### 📂 [EPUB to MOBI Converter](https://github.com/al3xrods/Calibre-Epub-to-Mobi-Conversion)
* An automation script that integrates with the Calibre application to batch-convert EPUB files to Kindle-compatible MOBI formats.
* **Tech Stack**: `Python` `Calibre CLI Integration` `Subprocess`

---

## 🎯 Current Focus
* **Deep Learning Theory & Architectures**: Expanding expertise in convolutional neural networks, transfer learning, and image preprocessing.
* **Advanced NLP**: Exploring transformer models and text embedding techniques.

---

<div align="center">
  <sub>Let's connect! Feel free to reach out on <a href="https://www.linkedin.com/in/alexander-rodriguez-/">LinkedIn</a> or check my work on <a href="https://www.kaggle.com/al3xrods">Kaggle</a>.</sub>
</div>
"""

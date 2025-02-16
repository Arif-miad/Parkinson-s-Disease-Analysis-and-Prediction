

### **🧠 Parkinson’s Disease Analysis and Prediction**  

#### **📌 Project Overview**  
This project focuses on **Exploratory Data Analysis (EDA) and regression modeling** for predicting Parkinson’s disease severity. The dataset contains **various acoustic and motor features** related to speech and movement, which are used to analyze patterns and build predictive models.  

#### **📂 Dataset Description**  
The dataset consists of **numerical features** related to speech and motor functions, commonly used for Parkinson’s disease diagnosis. Key columns include:  

- `fundamental_freq_hz`, `max_freq_hz`, `min_freq_hz` – Frequency-related features  
- `jitter_percent`, `jitter_abs`, `shimmer`, `shimmer_db` – Acoustic perturbation measures  
- `spread_1`, `spread_2`, `detrended_fluctuation`, `ppe` – Nonlinear dynamic features  
- `motor_updrs_score`, `total_updrs_score` – Disease severity scores  
- `age`, `gender`, `test_time` – Patient demographic and test metadata  

#### **📊 Exploratory Data Analysis (EDA)**  
We perform **30+ visualizations**, including:  
✅ **Univariate Analysis** (Histograms, Boxplots)  
✅ **Bivariate Analysis** (Scatterplots, Correlation Heatmap)  
✅ **Multivariate Analysis** (Pairplots, Feature Distributions)  
✅ **Feature Importance Analysis**  

#### **🛠️ Code Implementation**  

##### **📌 1. Data Preprocessing**  
- Handling missing values (if any)  
- Label encoding categorical columns (e.g., `gender`)  
- Normalization/standardization of features  

##### **📌 2. Data Visualization**  
- Correlation heatmaps for feature relationships  
- Distribution of key variables  
- Outlier detection using boxplots  

##### **📌 3. Regression Modeling**  
We compare **top 10 regression models** for predicting Parkinson’s severity (`motor_updrs_score` and `total_updrs_score`):  
1️⃣ **Linear Regression**  
2️⃣ **Ridge Regression**  
3️⃣ **Lasso Regression**  
4️⃣ **Decision Tree Regressor**  
5️⃣ **Random Forest Regressor**  
6️⃣ **Gradient Boosting Regressor**  
7️⃣ **XGBoost Regressor**  
8️⃣ **Support Vector Regressor (SVR)**  
9️⃣ **K-Nearest Neighbors (KNN) Regressor**  
🔟 **Neural Network (MLP Regressor)**  

##### **📌 4. Model Evaluation**  
- **Metrics Used**: RMSE, MAE, R² Score  
- **Hyperparameter Tuning** using GridSearchCV  
- **Feature Importance Analysis**  

#### **📜 Installation & Usage**  
1️⃣ Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/parkinsons-regression.git  
   cd parkinsons-regression
   ```  
2️⃣ Install dependencies:  
   ```bash
   pip install -r requirements.txt  
   ```  
3️⃣ Run the analysis:  
   ```bash
   python main.py  
   ```  

#### **📌 Results & Insights**  
📍 **EDA revealed key patterns in the dataset**  
📍 **Random Forest & XGBoost performed best for regression tasks**  
📍 **Feature importance showed that jitter, shimmer, and spread features are significant**  

#### **📖 Future Work**  
🚀 **Try deep learning-based models**  
🚀 **Investigate time-series trends in the dataset**  
🚀 **Optimize feature selection techniques**  

#### **🔗 Connect With Me**  
- **Kaggle**: [Arif Miah](https://www.kaggle.com/code/arifmia/exploratory-data-analysis-and-regression-modeling)  
- **LinkedIn**: [Arif Miah](www.linkedin.com/in/arif-miah-8751bb217)  

#### **🤝 Contributing**  
Feel free to **fork this repository** and contribute improvements!  

#### **📜 License**  
This project is under the **MIT License**.  




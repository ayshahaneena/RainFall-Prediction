# Rainfall Prediction  
## 🌟 Overview  
Rainfall prediction is crucial for effective planning in agriculture, water resource management, and disaster prevention. This project leverages machine learning techniques to predict rainfall using a dataset sourced from Kaggle. The model aims to provide accurate predictions that can assist in informed decision-making.  

## 📊 Dataset  
- **Source**: [Kaggle Dataset](#)  
- **Features**:  
  - Temperature  
  - Humidity  
  - Wind Speed  
  - Atmospheric Pressure
  - cloud	rainfall
  - sunshine
  - winddirection
  - windspeed
  - Other weather-related factors  
- **Target Variable**: Rainfall  

### Data Preprocessing  
- handled the issue of imbalanced data set through over sampling 
- Handled missing values using mode imputation.    
- Performed Exploratory Data Analysis (EDA) to identify patterns and relationships.
- Handled the issue of multicolinearity.
   

## ⚙️ Methodology  
### Models Used  
- Random Forest classifier  
 

### Evaluation Metrics  
- Cross-Validation (CV) Score with Hyperparameter Tuning  
- Accuracy 
  
## 📈 Results  
- **Best Model**: Random Forest Classifier  
- **Performance**:  
  - **Training Data Accuracy**: 85%  
  - **Testing Data Accuracy**: 80%
  -  
- **Insights**:  
  - Humidity and temperature were the most important predictors.  
  - Seasonal patterns significantly impact rainfall predictions.
  - Pressure (-0.09): There is a weak negative correlation between pressure and rainfall, indicating that lower pressures might slightly correspond to higher rainfall.
  - Sunshine (-0.55): There is a moderate negative correlation between sunshine and rainfall, suggesting that less sunshine is associated with more rainfall
  - Humidity (0.49): There is a moderate positive correlation between humidity and rainfall, indicating higher humidity levels often accompany higher rainfall.
  - Cloud (0.63): There is a moderate positive correlation between cloud and rainfall, indicating more clouds often accompany higher rainfall. 


## 🔍 Insights  
- Strong correlations observed between key features.  
- Seasonal patterns significantly impact rainfall predictions.  
  

## 📜 License
This project is licensed under  MIT License.

## 🤝 Acknowledgments
Dataset: [Kaggle]
Tools: Scikit-learn, Pandas, Matplotlib, Seaborn , pickle

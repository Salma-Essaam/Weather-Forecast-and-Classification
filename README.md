# Weather Forecast and Classification using Machine Learning

This project analyzes and predicts weather conditions using machine learning models.  
It includes data preprocessing, feature encoding, visualization, and model evaluation for weather classification and temperature prediction.

## Project Overview
- Loaded and explored historical weather data  
- Visualized relationships between precipitation, wind, and temperature  
- Encoded categorical weather conditions using One-Hot Encoding  
- Built and compared predictive models:
  - Ridge Classifier  
  - Random Forest Classifier  
- Evaluated model performance with cross-validation  

## Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

## Dataset
The dataset (`weather.csv`) contains daily weather records, including:
- **precipitation**  
- **temp_max**  
- **temp_min**  
- **wind**  
- **weather condition** (e.g., sun, rain, fog)

## How to Run
1. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn

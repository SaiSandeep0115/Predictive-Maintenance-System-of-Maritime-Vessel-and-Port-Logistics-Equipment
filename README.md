# Predictive-Maintenance-System-of-Maritime-Vessel-and-Port-Logistics-Equipment

## Languages:
- **Python**
  
## Important Libraries:
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **PySpark**
- **PySpark.SQL**

## Technologies:
- **MySQL**
- **Data Analysis**
- **Machine Learning**
- **Big Data Analytics**

### Abstract:
This project focuses on predictive maintenance for vessel and port handling equipment. Utilizing various datasets from Kaggle, we developed models to predict the condition of critical components, ensuring operational efficiency and reducing downtime.

### Dataset:
Naval Vessel Dataset: Includes data on turbines and compressors to assess their conditions.
AGV Datasets: Data on bearings, servomotors, and battery Remaining Useful Life (RUL).

### Methodology:
Data Preprocessing: Cleaned and transformed the datasets for analysis.
Exploratory Data Analysis: Visualized and explored data relationships.
Model Development:
For Bearings: Utilized PySpark and MySQL for handling large datasets.
For Others: Implemented models using Scikit-learn.

### Models:
For the Naval Vessel Parts, the compressor model achieved an impressive R² score of 0.982854, with a mean squared error (MSE) of 0.000004, mean absolute error (MAE) of 0.001044, root mean square error (RMSE) of 0.001923, and mean absolute percentage error (MAPE) of 0.00107, utilizing a Decision Tree algorithm. The turbine model also employed a Decision Tree, yielding a R² score of 0.966855, an MSE of 0.000002, an MAE of 0.000669, an RMSE of 0.001373, and a MAPE of 0.000678.
In the Automated Guided Vehicle Parts, the battery model demonstrated exceptional performance with a linear regression approach, achieving a R² score of 0.99952, MSE of 49.984151, MAE of 4.491966, RMSE of 7.069947, and an extraordinarily high MAPE of 9.086208e+12. For the servomotor, a Random Forest model was utilized, resulting in a R² score of 0.831742, MSE of 31.291155, MAE of 3.639412, RMSE of 5.59385, and a MAPE of 0.573671. Finally, logistic regression was applied to the bearing models, with Bearing 1 achieving a perfect result of 1.0000 and Bearing 2 scoring 0.8906.

### Results and Conclusion:
The predictive models demonstrate high accuracy in predicting the condition of vessel and port handling equipment. The findings can help in implementing effective maintenance strategies, enhancing operational reliability.

### Disclaimer:
The datasets for Automated Guided Vehicles (AGVs), including bearings, servomotors, and batteries, were not collected directly from AGVs. Due to a lack of specific data, these datasets are assumed to represent similar conditions for the purpose of analysis. The findings from this project may not accurately reflect real-world scenarios. Further validation and refinement are necessary to ensure reliability and effectiveness in practical applications.

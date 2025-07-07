## Projects

####   AI-Optimized Predictive Maintenance
- AI project for sustainable development
- Economic sector analysis (Industry)
- Use predictive maintenance to monitor the operation of industrial machines and predict failures
- Binary classification with LightGBM (Predict failure or no failure) with an accuracy of 98%
- Multiclass classification with LightGBM (Predict the faulty component) with an accuracy of 99.9%
- Regression with XGBRegressor (Predict number of days before failure) with an MAE of 0.14 or 3 hours and 24 minutes
- Tools used: Python, Scikit-learn, LightGBM, XGBRegressor | Dataset: [Microsoft Azure Predictive Maintenance](https://www.kaggle.com/datasets/arnabbiswas1/microsoft-azure-predictive-maintenance)
**Links**: [Report](https://drive.google.com/file/d/1VgAG7dDSWL28ndv5Ke_3Gaals17xTx6N/view?usp=sharing)
[Repository](https://github.com/marieangedieng/maintenance-predictive)

####   Analysis and Implementation of Machine Learning Techniques
- Development and comparison of multiple ML models on various problems
- Implementation of regression models (linear, polynomial, Ridge, Lasso) with performance optimization
- Classification of Iris species with KNN and decision trees (accuracy from 94–100%)
- Comparative analysis of clustering techniques (K-Means, hierarchical, DBSCAN) on different datasets
- Dimensionality reduction using PCA on the MNIST dataset
- Study of algorithmic bias and interpretability on the COMPAS dataset
- Tools used: Python, Scikit-learn, Pandas, NumPy, Matplotlib | Datasets: Iris, MNIST, COMPAS
**Link**: [Report](https://drive.google.com/file/d/1_ZWurXvt-zwvQKtQ5aGBgtDzyYbsH-6M/view?usp=sharing)

####   Credit Scoring System – Predictive Model
- Developed a scoring model to predict default risk of clients
- Implemented an ensemble model (Stacking: LGBM + Random Forest + Logistic Regression)
- Advanced data preprocessing and feature engineering (ratios, custom encodings)
- Improved overall classification accuracy to 82\% vs. 77\% with the baseline model
- Tools used: Python, Scikit-learn, LightGBM, Pandas | Dataset: [Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk/data)
**Links**: [Presentation](https://drive.google.com/file/d/1foW6ximwjcSG-58h7n8RfUe0zkMrrpdx/view?usp=sharing)
[Notebook in HTML](https://drive.google.com/file/d/1jDmAVwrNhojfnq_5dPTg6duE9KhqofNh/view?usp=drive_link)

####   Real Estate Price Prediction with Deep Learning
- Developed a deep learning model to predict real estate prices (Boston Housing dataset)
- Implemented a neural network with 3 hidden layers using Keras/TensorFlow
- Optimization using L2 regularization and 20\% Dropout to reduce overfitting
- 5-fold cross-validation with Mean Absolute Error (MAE) between 2.05 and 2.65
- Performance comparison of models with and without regularization over 100 and 500 epochs
- Developed an interactive interface using Streamlit to visualize performance and test the model
- Tools used: Python, TensorFlow, Keras, Streamlit, Pandas, Scikit-learn | Dataset: Boston Housing
**Links**: [Report](https://drive.google.com/file/d/1vA9H9B8HBAqnv9j9KSrqxTpZuDKyCMZx/view?usp=sharing)
[Notebook](https://github.com/marieangedieng/reports/blob/main/Projet_2.ipynb)

####   Smart IoT System with AI-Based Anomaly Detection
- Developed an intelligent embedded system to monitor temperature, humidity, gases (MQ2), and air quality (MQ135) using ESP32
- Trained an anomaly detection model on Google Colab and deployed inference (TensorFlow Lite) via MQTT to bypass ESP32 memory limits
- Integrated with ThingsBoard for real-time visualization of data and anomaly indicators, with automation rules (heating, lights, humidifier, etc.)
- Implemented preprocessing (normalization), expected value prediction and residual-based anomaly detection with thresholding
- Tools used: Wokwi simulation – Processing on Google Colab – Visualization with ThingsBoard
**Links**: [Projet Wokwi](https://wokwi.com/projects/426533449236603905)
[Visualisation on ThingsBoard](https://demo.thingsboard.io/dashboard/c700c680-0a9f-11f0-b029-835883384c03?publicId=bd6a1560-020a-11f0-9dbc-834dadad7dd9)
[Report and Codes](https://github.com/marieangedieng/reports/tree/main/ProjetIot)

####   Health-Oriented Data Analysis
- Descriptive, bivariate, and multivariate analysis of data from 449 women (149 heart attack cases, 300 controls)
- Developed three predictive models with up to 89.66\% accuracy
- Identified main risk factors: oral contraceptives (OR = 8.91), smoking (OR = 11.28 for former smokers)
- Tools used: R, logistic regression, Random Forest, SVM, PCA, MCA
**Links**: [Report](https://drive.google.com/file/d/1mHbzk7W6RFyt4J_TQNNfA3alPGjDUJOF/view?usp=sharing)
[Repository](https://github.com/marieangedieng/reports/tree/main/HealthDataAnalysis)

####   Fertility Rate Trend Analysis by Country
- Time series analysis of fertility rates (1950–2023) with a focus on France
- Comparison of predictive models: ARIMA, AUTO-ARIMA, and SARIMAX
- Optimization: AUTO-ARIMA outperformed classical ARIMA
- SARIMAX model with 5-year seasonality yielded the best graphical predictions
- Tools used: Dickey-Fuller stationarity tests, differencing, ACF/PACF, Ljung-Box tests
**Links**: [Report](https://drive.google.com/file/d/1kke2ZzrQKrfnoowSxDlTovIFeIUYqLll/view?usp=sharing)
[Repository]()

####   Data Analysis : Survival Analysis Using the Cox Proportional Hazards Model 
- Conducted survival analysis using the Cox proportional hazards model, ensuring adherence to the proportional
hazards assumption through diagnostic tests with R.
- Analyzed patient survival times and identified significant risk factors (e.g., age, alcohol consumption, and drug
use) influencing mortality rates.
**Link**: [Report](cox.pdf)

#### Greenhouse gases: distribution and forecasting  
- Fit a shifted exponential distribution and a Verhulst distribution on time series data for the global greenhouse
gas emissions using Levenberg-Marquardt for parameter estimation
- Data optimization: The Verhulst distribution is the one that best describes the data
- 30-year punctual forecasting and confidence interval prediction
- Tools Used : SCILAB DeskTop, TexMaker | SciLab, Latex
**Link**: [Report](ghg.pdf)


#### Web Application of job portal 
- Design pattern implementation (Observer, Strategy, and Simple Factory)
- Implementation of Laravel controllers
- Deployment on a server
- Tools Used :PhpStorm, Laravel Forge, DigitalOcean Droplet, PhpMyAdmin | HTML, CSS, PHP, SQL
**Link**: [Code](https://github.com/marieangedieng/jobFinder)


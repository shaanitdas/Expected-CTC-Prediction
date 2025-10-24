# Expected-CTC-Prediction
A comprehensive machine learning solution for predicting Expected Cost-To-Company (CTC) for job candidates using ensemble learning techniques with 99.97% accuracy.

🎯 Project Overview
This project predicts the Expected CTC (salary expectations) for job candidates based on their professional profile, educational background, experience, and performance metrics. It uses advanced Ensemble Learning with a Stacking Regressor that combines Random Forest, XGBoost, and LightGBM models.

For complete files and documents (models.pkl) access , visit the google drive link: https://drive.google.com/drive/folders/1f2PqPh4rmAC0nj2NHamswOk1Iz-rOCol?usp=drive_link


Key Highlights
✅ 99.97% Test R² Score 
✅ RMSE: 18,988 
✅ Ensemble Learning - Combines 3 powerful ML algorithms (Random Forest, XGBoost and LightGBM)
✅ Production Ready - Includes deployment artifacts (scalers, encoders, models)
✅ Complete ML Pipeline - From EDA to model deployment

main.ipynb                       # Main training notebook (Complete ML Pipeline)
test.ipynb                       # Testing the model on manual input data 
expected_ctc.csv                 # Training dataset
Random_Forest_Model.pkl          # Saved Random Forest model
XGB_Model.pkl                    # Saved XGBoost model
LGBM_Model.pkl                   # Saved LightGBM model
Stacking_Regressor_Model.pkl     # Best model (Ensemble)
labelencoder1.pkl                # Saved label encoder
scaler2.pkl                      # Saved feature scaler

Model Speciality
No Overfitting!
Train and Test R² scores are nearly identical (0.999+ for both)
Minimal gap between Train and Test RMSE
Excellent generalization capability

Requirements
Python >= 3.9
pandas >= 1.3.0
numpy >= 1.21.0
scikit-learn >= 1.0.0
xgboost >= 1.5.0
lightgbm >= 3.3.0
matplotlib >= 3.4.0
seaborn >= 0.11.0
joblib >= 1.1.0
wordcloud >= 1.8.0

Future Enhancements:
Deploy as REST API using Flask/FastAPI
Create interactive web dashboard using frontend (react.js)

⭐ Star this repo if you find it useful!

Made with ❤️ and lots of ☕


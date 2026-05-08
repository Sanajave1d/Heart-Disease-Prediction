# Heart Disease Prediction with KNN
A machine learning project using K-Nearest Neighbors (KNN) algorithm to predict the presence of heart disease based on patient health metrics.

## Features
- **KNN Classifier**: Efficient implementation of K-Nearest Neighbors algorithm
- **Data Preprocessing**: StandardScaler normalization for accurate distance calculations
- **Performance Metrics**: Accuracy and F1-Score evaluation
- **Interactive UI**: Streamlit web app for real-time predictions
- **User-Friendly Interface**: Input health metrics and get instant disease predictions

## Dataset
- Heart disease classification dataset with patient health indicators
- Features: Age, Gender, Chest Pain Type, Blood Pressure, Cholesterol, Heart Rate, ST Depression, and more
- Target: Binary classification (Heart Disease: Yes/No)

## Technologies Used
- Python, scikit-learn, pandas, numpy
- Streamlit (for interactive web interface)
- Joblib (for model serialization)

## Model Performance
- **Accuracy**: ~88% on test data
- **F1-Score**: ~89%
- KNN effectively captures complex patterns in medical data

## Usage
Run the Streamlit app to make predictions:
```bash
streamlit run app.py
```

Input your health metrics and get instant predictions with confidence scores.

## How KNN Works
- Uses distance-based classification (finds k nearest neighbors)
- Classifies new data points based on majority vote of neighbors
- Effective for non-linear medical data patterns

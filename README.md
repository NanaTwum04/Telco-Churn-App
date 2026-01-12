# Customer Churn Prediction ML App

A streamlit web application for predicting customer churn using machine learning.

## Features

- **Data Upload & Exploration** - Upload CSV files and visualize with interactive charts
- **Preprocessing Pipeline** - Handle missing values, encode categories, and scale features
- **Multiple ML Models** - Train and compare KNN, Random Forest, and Neural Networks
- **Model Evaluation** - View metrics, confusion matrices, ROC curves, and feature importance
- **Real-time Predictions** - Make predictions on new customer data
- **Export Models** - Download trained models and artifacts for production use

## Installation
```bash
# Clone the repository
git clone https://github.com/NanaTwum04/churn-prediction-app.git
cd churn-prediction-app

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run MLProject.py
```

## Requirements

- Python 3.10+
- streamlit
- pandas
- numpy
- scikit-learn
- plotly
- seaborn
- matplotlib

## Usage

1. **Upload Dataset** - Go to Dataset page and upload your CSV file
2. **Preprocess** - Configure preprocessing options (drop columns, impute, encode, scale)
3. **Train Models** - Select models and set hyperparameters
4. **Evaluate** - Compare model performance with detailed metrics
5. **Predict** - Enter new customer data to get churn predictions

## Dataset Format

Your CSV should contain:
- Customer features (numeric and categorical)
- A target column (e.g., "Churn", "Exited") with binary values (0/1)

Example:
```csv
Age,Gender,Balance,NumOfProducts,IsActiveMember,Churn
42,Male,50000,2,1,0
35,Female,75000,1,0,1
```

## Models

- **K-Nearest Neighbors** - Simple, distance-based classifier
- **Random Forest** - Ensemble method with feature importance
- **Neural Network (MLP)** - Deep learning for complex patterns

## Tech Stack

- **Frontend**: Streamlit
- **ML**: scikit-learn
- **Data**: pandas, numpy
- **Visualization**: Plotly, Seaborn, Matplotlib

## License

MIT License - feel free to use this project for your own purposes.

## Author

Nana Adu-Twum(https://github.com/NanaTwum04)

## Contributing

Issues and pull requests are welcome!

---

⭐ Star this repo if you find it helpful!
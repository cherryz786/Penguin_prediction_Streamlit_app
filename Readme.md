
# Penguin Prediction App

This project allows you to predict the species of a Palmer penguin based on its physical characteristics and location.

## Key Features:

User-friendly Streamlit app for easy interaction and prediction.
Random Forest model trained on the Palmer Penguins dataset for accurate prediction.
Multiple input options: Users can either enter penguin features manually or upload a CSV file.
Clear prediction results: Displays both the predicted species and prediction probabilities.


## Getting Started:

Install required libraries:

```Bash
pip install streamlit pandas numpy pickle sklearn
```

Download the model file:
Download the penguins_clf.pkl file from the repository.
Place it in the same directory as the app file.
Run the app:

```Bash
streamlit run app.py
```

## Usage:

Provide input:

Manually: Use the sidebar to select the penguin's island, sex, and enter its physical measurements.
Upload CSV: Upload a CSV file containing multiple penguin data points.
View prediction:

The app will display the predicted species and its probability.


## Dataset:

Data obtained from the palmerpenguins library: https://github.com/allisonhorst/palmerpenguins in R by Allison Horst.


## Model:

Random Forest classifier trained using scikit-learn.

## Project Structure:

```
├── penguins-app.py                 # Streamlit app file
├── penguins-model-building.py      # Model Building file
├── penguins_cleaned.csv            # Cleaned dataset
├── penguins_clf.pkl                # Saved model file
└── README.md                       # This file
```


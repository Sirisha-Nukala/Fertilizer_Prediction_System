# 🌱 Fertilizer Recommendation System

A Machine Learning project that recommends the most suitable fertilizer
based on soil characteristics, crop type, and environmental parameters.

The system uses a **Decision Tree Classifier** trained on a fertilizer
recommendation dataset and saves the trained model for future
predictions.

------------------------------------------------------------------------

## 📌 Project Overview

Farmers often struggle to choose the correct fertilizer for their
crops.\
This project aims to solve that problem using **Machine Learning**.

The model analyzes factors like:

-   Soil Type
-   Crop Type
-   Temperature
-   Humidity
-   Moisture
-   Nitrogen
-   Potassium
-   Phosphorous

Based on these inputs, the system predicts the **best fertilizer** to
use.

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   Python
-   Pandas
-   Scikit-learn
-   Pickle
-   Label Encoding
-   Decision Tree Algorithm

------------------------------------------------------------------------

## 📂 Project Structure

fertilizer-recommendation-system │ ├──
fertilizer_recommendation_dataset.csv ├── train_model.py ├── model.pkl
├── fertilizer_encoder.pkl └── README.md

------------------------------------------------------------------------

## ⚙️ Model Training

Run the training script:

``` bash
python train_model.py
```

This script will:

1.  Load the dataset\
2.  Encode categorical features\
3.  Train the Decision Tree model\
4.  Save the trained model

Saved files:

-   `model.pkl`
-   `fertilizer_encoder.pkl`

------------------------------------------------------------------------

## 🧠 Machine Learning Workflow

1.  Data Collection\
2.  Data Preprocessing\
3.  Feature Encoding\
4.  Model Training\
5.  Model Serialization using Pickle\
6.  Prediction

------------------------------------------------------------------------

## 🚀 Future Improvements

-   Build a **Flask / Streamlit web application**
-   Add real-time fertilizer prediction
-   Improve model accuracy with advanced algorithms
-   Deploy the model to the cloud

------------------------------------------------------------------------

## 👨‍💻 Author

**Kumar Karri**

If you found this project helpful, feel free to ⭐ the repository.

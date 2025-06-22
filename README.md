
🌱 Fertilizer Recommendation System

This project is focused on predicting the optimal type of fertilizer for a given agricultural field based on several environmental and crop-related parameters using machine learning techniques.

📌 Project Overview

The goal of this project is to recommend the best fertilizer using various inputs such as:

- Temperature
- Humidity
- Moisture
- Soil Type
- Crop Type
- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)

The model uses a classification algorithm trained on a labeled dataset to predict the most suitable fertilizer from a predefined list.

🚀 How to Run the Notebook

1. Clone the Repository

git clone https://github.com/yourusername/Fertilizer-Recommendation.git
cd Fertilizer-Recommendation

2. Install Dependencies

Make sure you have Python 3.x installed. Then install the required libraries:

pip install pandas numpy scikit-learn matplotlib seaborn

3. Launch the Notebook

jupyter notebook Fertilizers_prediction.ipynb

📊 Features Used

| Feature      | Description                            |
|--------------|----------------------------------------|
| Temperature  | Current temperature in Celsius         |
| Humidity     | Relative humidity percentage           |
| Moisture     | Soil moisture content                  |
| Soil Type    | Categorical label of soil (e.g., Sandy)|
| Crop Type    | Categorical label of crop (e.g., Rice) |
| Nitrogen     | Nitrogen level in soil                 |
| Phosphorus   | Phosphorus level in soil               |
| Potassium    | Potassium level in soil                |

🧠 Model Training

- Data preprocessing: Label encoding for categorical data
- Train/Test split
- Model: Random Forest Classifier (best performing)
- Evaluation: Accuracy, Confusion Matrix

✅ Results

- Achieved high accuracy (typically >90%) on the test dataset.
- Random Forest performed better than other models like Logistic Regression or KNN.

📌 Future Improvements

- Add advanced feature engineering (e.g., interactions or derived variables)
- Try deep learning models for comparison
- Build a Streamlit web app for farmer-friendly deployment
- Add support for regional languages

🧑‍💻 Author

Sagar H M
Data Scientist


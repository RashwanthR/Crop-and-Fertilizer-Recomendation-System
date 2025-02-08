# Crop-and-Fertilizer-Recomendation-System-Using-ML

This repository contains Jupyter notebooks that implement machine learning models to recommend the best crops and fertilizers based on soil and environmental conditions. The system leverages data-driven techniques to help farmers optimize their agricultural practices for higher yields and sustainability.

Project Overview

This system consists of two primary components:

1. Crop Recommendation System

Objective: Predict the most suitable crop to grow based on soil and climatic parameters.

Input Features:

Nitrogen (N)

Phosphorus (P)

Potassium (K)

Temperature

Humidity

pH Level

Rainfall

Output: Recommended crop (e.g., Rice, Maize, Wheat, etc.).

Machine Learning Algorithm Used: Decision Tree / Random Forest (configurable in the notebook).

2. Fertilizer Recommendation System

Objective: Suggest the best fertilizer based on soil deficiencies and crop requirements.

Input Features:

Soil Nutrient Composition (N, P, K levels)

Crop Type

Output: Recommended fertilizer type.

Machine Learning Algorithm Used: Decision Tree / Support Vector Machine (SVM) (configurable in the notebook).

Installation & Setup

To use this project, follow these steps:

1. Clone the Repository

  git clone https://github.com/your-username/crop-fertilizer-recommendation.git
  cd crop-fertilizer-recommendation

2. Install Required Libraries

Ensure you have Python installed (preferably Python 3.8+) and install the dependencies using:

pip install -r requirements.txt

Alternatively, install the necessary packages manually:

pip install numpy pandas matplotlib seaborn scikit-learn

3. Run the Jupyter Notebook

Launch Jupyter Notebook and open either crop.ipynb or fertilizer.ipynb:

jupyter notebook

Dataset

Crop Recommendation Dataset: dataset/Crop_recommendation.csv

Fertilizer Recommendation Dataset: dataset/Fertilizer Prediction.csv

Ensure these datasets are placed inside the dataset/ folder before running the notebooks.

How to Use

1. Crop Recommendation

Open crop.ipynb in Jupyter Notebook.

Run the notebook step-by-step.

Enter soil and climate parameters.

Get the best crop recommendation based on ML predictions.

2. Fertilizer Recommendation

Open fertilizer.ipynb in Jupyter Notebook.

Run the notebook step-by-step.

Enter soil nutrient levels and crop type.

Get the best fertilizer recommendation based on ML predictions.

Results & Insights

The ML models provide high accuracy in predicting the most suitable crop and fertilizer.

Helps in precision farming, reducing excessive fertilizer use and improving crop selection.

Ensures sustainable agriculture by optimizing soil health and resource allocation.

Future Improvements

Expand the dataset with real-time soil and climate data.

Implement deep learning models for improved accuracy.

Develop a web-based UI or mobile app for easier access.

Integrate weather forecasting for dynamic crop recommendations.

License

This project is open-source under the MIT License. Feel free to modify and use it.

Contributing

Contributions are welcome! Feel free to fork this repository, create a new branch, and submit a pull request.

Contact

If you have any questions or suggestions, reach out via:

Email: your-email@example.com

GitHub Issues: Open an Issue

Happy Farming & Smart Agriculture!

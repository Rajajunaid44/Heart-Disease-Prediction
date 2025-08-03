# ❤ Heart Disease Prediction System

![Heart Disease Prediction Banner](https://img.shields.io/badge/Machine%20Learning-Heart%20Disease%20Prediction-red?style=for-the-badge&logo=heart)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-Latest-orange)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/Rajajunaid44/Heart-Disease-Prediction/graphs/commit-activity)

## 📋 Table of Contents
- [About The Project](#-about-the-project)
- [Dataset Information](#-dataset-information)
- [Features](#-features)
- [Demo](#-demo)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#-usage)
- [Model Performance](#-model-performance)
- [Technologies Used](#-technologies-used)
- [Future Improvements](#-future-improvements)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

## 🔍 About The Project

This project aims to predict the likelihood of heart disease in patients based on their medical attributes. Cardiovascular diseases are the leading cause of death globally, taking an estimated 17.9 million lives each year. Early detection and management are crucial for people with heart disease or at high risk.

Using machine learning algorithms, we've developed a predictive model that can assist healthcare professionals in identifying patients who might be at risk, potentially saving lives through early intervention and treatment.

## 📊 Dataset Information

The dataset used contains several parameters which can be used to predict heart disease:

- *Age*: Age of the patient
- *Sex*: Sex of the patient
- *Chest Pain Type*: Type of chest pain experienced
- *Resting Blood Pressure*: Resting blood pressure value
- *Cholesterol*: Serum cholesterol in mg/dl
- *Fasting Blood Sugar*: > 120 mg/dl (1 = true; 0 = false)
- *Resting ECG*: Resting electrocardiographic results
- *Max Heart Rate*: Maximum heart rate achieved
- *Exercise Induced Angina*: Exercise-induced angina (1 = yes; 0 = no)
- *ST Depression*: ST depression induced by exercise relative to rest
- *Slope of ST Segment*: Slope of the peak exercise ST segment
- *Number of Major Vessels*: Number of major vessels colored by fluoroscopy
- *Thalassemia*: A blood disorder called thalassemia
- *Target*: Heart disease diagnosis (1 = disease; 0 = no disease)

## 🌟 Features

- *Data Preprocessing*: Advanced cleaning and normalization techniques
- *Exploratory Data Analysis*: Comprehensive visualization of patterns and correlations
- *Multiple ML Models*: Comparison of several algorithms to find the best performer
- *Feature Importance*: Analysis of which factors most strongly indicate heart disease
- *Interactive Prediction*: User-friendly interface for making predictions on new data
- *Model Evaluation*: Detailed performance metrics to validate model accuracy

## 🎬 Demo

![Demo GIF](https://raw.githubusercontent.com/Rajajunaid44/Heart-Disease-Prediction/main/demo.gif)

> Note: Add a demo GIF or screenshot of your application here

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip package manager

### Installation

1. Clone the repository:
bash
git clone https://github.com/Rajajunaid44/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction


2. Create and activate a virtual environment (optional but recommended):
bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


3. Install required packages:
bash
pip install -r requirements.txt


## 💻 Usage

1. *Run the Jupyter Notebook for analysis*:
bash
jupyter notebook Heart_Disease_Analysis.ipynb


2. *Run the prediction application*:
bash
python app.py


3. *Input patient data for prediction*:
   - Enter the required medical parameters in the form
   - Click "Predict" to see the heart disease risk assessment

## 📈 Model Performance

We evaluated several machine learning models and achieved the following performance:

| Model | Accuracy | Precision | Recall | F1 Score |
|-------|----------|-----------|--------|----------|
| Random Forest | 88.5% | 89.2% | 87.6% | 88.4% |
| Logistic Regression | 84.3% | 85.1% | 83.7% | 84.4% |
| Support Vector Machine | 86.7% | 87.3% | 85.9% | 86.6% |
| K-Nearest Neighbors | 83.2% | 84.5% | 82.1% | 83.3% |

The Random Forest model performed best overall and was selected for the final implementation.

## 🛠 Technologies Used

- *Python*: Core programming language
- *Pandas*: Data manipulation 
- *Scikit-Learn*: Machine learning algorithms and model evaluation
- *Matplotlib & Seaborn*: Data visualization
- *Jupyter Notebook*: Interactive development and documentation

## 🔮 Future Improvements

- [ ] Implement deep learning models for improved accuracy
- [ ] Create a more interactive web interface with additional visualizations
- [ ] Incorporate more features/parameters for prediction
- [ ] Deploy as a web service for wider accessibility
- [ ] Develop a mobile application for on-the-go risk assessment

## 👥 Contributing

Contributions make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are *greatly appreciated*.

1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
3. Commit your Changes (git commit -m 'Add some AmazingFeature')
4. Push to the Branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

## 📝 License

Distributed under the MIT License. See LICENSE for more information.

## 📬 Contact

Junaid Raja - [@Rajajunaid44](https://github.com/Rajajunaid44)

Project Link: [https://github.com/Rajajunaid44/Heart-Disease-Prediction](https://github.com/Rajajunaid44/Heart-Disease-Prediction)

---

<p align="center">
  Made with ❤ for better healthcare
</p>

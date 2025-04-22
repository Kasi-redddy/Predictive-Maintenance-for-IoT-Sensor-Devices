# Predictive-Maintenance-for-IoT-Sensor-Devices

# Predictive Maintenance for IoT Sensor Devices 🚀

Welcome to my **Predictive Maintenance for IoT Sensor Devices** project! In this project, we predict potential equipment failures based on sensor data, helping businesses avoid unexpected downtimes by identifying issues before they become critical.

By leveraging machine learning, we forecast whether a device will fail within the next 24 hours based on sensor data readings. This repository includes everything from data exploration, feature engineering, model building, and evaluation, to model interpretability. It's a fun and insightful way to see how we can use data to predict industrial equipment behavior!

##  Project Structure

Here’s a quick overview of the files in this project:

- **data/**: Contains the training and test datasets (`train.csv`, `test.csv`).
- **notebooks/**: The Jupyter notebook (`Finfresh_task.ipynb`) where I performed all the steps: data exploration, model training, and evaluation.
- **requirements.txt**: A list of all Python dependencies you'll need to run this project.
-

## Task Breakdown

### 1. **Understand the Data**
I started by diving into the data. The first step was exploring the features and understanding their relationships. I visualized the data, checked for missing values, and identified the key features that influenced equipment failures.

### 2. **Build Predictive Models**
Then, I trained multiple classification models, including:
- Logistic Regression
- Random Forest
- XGBoost

I evaluated these models based on metrics such as:
- Precision, Recall, and F1-Score
- Confusion matrix
- ROC AUC (for overall model performance)

### 3. **Feature Engineering**
Feature engineering is where the magic happens! I created new features like rolling averages, drift indicators, and other metrics that helped the models perform better. These features improved the model’s ability to identify failure patterns.

### 4. **Model Interpretability**
In predictive maintenance, it's essential to understand why the model makes certain predictions. I used **SHAP** (SHapley Additive exPlanations) to provide insights into the model's decisions. The notebook explains how each feature contributed to the model’s predictions.

### 5. **Final Evaluation**
Once the model was performing well on the training set, I tested it on unseen data (`test.csv`) to see how well it generalized. This gave me a better understanding of how the model would perform in real-world scenarios.

##  Requirements

To run this project, you'll need Python 3.x and a few libraries. Simply run the following to install everything you need:

```bash
pip install -r requirements.txt

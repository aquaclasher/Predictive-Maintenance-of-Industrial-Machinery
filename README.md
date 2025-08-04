# Predictive Maintenance of Industrial Machinery

This repository contains a capstone project for the **IBM SkillsBuild for Academia** program. The project focuses on developing a machine learning model to predict and classify failures in industrial machinery before they occur, enabling a shift from reactive to proactive maintenance.

## 📝 Problem

[cite_start]Unplanned machinery failures are a significant cause of costly production downtime and inefficient maintenance cycles in manufacturing[cite: 317, 320]. [cite_start]The challenge is to anticipate these failures and understand their specific root cause in advance[cite: 319].

## 💡 Solution

We developed a multi-class classification model using IBM Watson Studio's AutoAI feature. The model, a **Snap Random Forest Classifier**, analyzes real-time sensor data (temperature, torque, tool wear, etc.) to predict the specific mode of an impending failure. The model was trained using an incremental learning approach to handle data arriving in batches.

## 🛠️ Key Features & Technology

* **Model**: Snap Random Forest Classifier
* **Platform**: IBM Watson Studio & watsonx.ai
* **Libraries**: Scikit-learn, SnapML, Pandas, Matplotlib
* [cite_start]**Dataset**: [Machine Predictive Maintenance Classification on Kaggle](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification) [cite: 321]

## 📂 Repository Contents

* `Project_Presentation.pdf`: The final project presentation slides.
* `_P5 - Snap Random Forest Classifier_ Model Builder.ipynb`: The Jupyter Notebook containing the model training and deployment process.
* [cite_start]`Predict_Maintenance_with_new_data.csv`: The test dataset used for model evaluation[cite: 1].

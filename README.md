❤️ Heart Disease Classifier Model
🔬 Project Overview

Objective: Predict whether a patient has heart disease based on clinical features 🩺

Model Used: DecisionTreeClassifier🌳

Evaluation Metrics: Accuracy 📊, Confusion Matrix 🗂️

📂 Dataset
The dataset (heart.csv) contains clinical records for 302 patients, each described by 13 features and a binary target.

Columns:

👴 age: Age of patient (years)

🚻 sex: Gender (1 = male, 0 = female)

❤️ cp: Chest pain type (1-typical angina, 2-atypical angina, 3-non-anginal pain, 4-asymptomatic)

💉 trestbps: Resting blood pressure (mm Hg)

🧪 chol: Serum cholesterol (mg/dl)

🍬 fbs: Fasting blood sugar (1 = high, 0 = low)

🔎 restecg: Resting ECG results (0-normal, 1-ST-T abnormality, 2-left ventricular hypertrophy)

🏃 thalach: Maximum heart rate achieved

🏋️ exang: Exercise-induced angina (1 = yes, 0 = no)

📉 oldpeak: ST depression induced by exercise

📐 slope: Slope of ST segment during peak exercise (1-upsloping, 2-flat, 3-downsloping)

🚦 ca: Major vessels colored by fluoroscopy (0–4)

🔬 thal: Thallium scan result (1-fixed defect, 2-reversible defect, 3-normal)

🩺 target: Heart disease (1 - Yes, 0 - No)

⚙️ Requirements
Python 3.x 🐍

pandas 🐼

numpy 🧮

matplotlib 📈

seaborn 🌊

scikit-learn 🤖

🚀 Installation & Usage
bash
pip install -r requirements.txt
📦 Place the heart.csv dataset in the working path

💻 Open and run Heart_disease_classifier_model.ipynb

🏋️‍♂️ Train and test the Decision Tree Model

🎯 Accuracy (~78.7%) and confusion matrix will be shown

🗂️ Project Structure
Heart_disease_classifier_model.ipynb – Main Jupyter Notebook

heart.csv – Dataset file

requirements.txt – Required packages list

🏆 Results
Accuracy: ~78.7% ✅

Confusion Matrix: See notebook output 🗂️

📝 Notes
Dataset cleaned for nulls and duplicates 🧹

Outlier removal not required

Feature exploration and visualization included 📈

🌐 License
Open source for educational use! 📚


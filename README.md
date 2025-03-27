# Heart Attack Prediction Using Machine Learning

## Introduction
Heart disease is a leading cause of mortality worldwide, and early detection is crucial in preventing fatal heart attacks. With advancements in machine learning (ML), predictive models can help assess the risk of heart attacks based on various health parameters. This project presents a Heart Attack Prediction System built using Python, Streamlit, and machine learning algorithms.

## Project Overview
This project leverages ML models to predict the likelihood of a heart attack based on a patient's medical data. The system consists of:
- A web-based interface (Streamlit) for user interaction.
- Machine learning models trained on patient health data.
- Real-time predictions based on user input.

- ![image](https://github.com/user-attachments/assets/1c222196-974c-4895-9869-672a37c40c35)
- ![image](https://github.com/user-attachments/assets/07892d32-ac6f-453b-8bb4-d12c92e34468)

# Download Code :-[ Click here](https://updategadh.com/)

## Dataset
The project uses a dataset (`hf.csv`) containing medical records of patients. The key features include:
- **Age**
- **Anaemia**
- **Creatinine Phosphokinase**
- **Diabetes**
- **Ejection Fraction**
- **High Blood Pressure**
- **Platelet Count**
- **Serum Creatinine**
- **Serum Sodium**
- **Sex**
- **Smoking**
- **Time (Follow-up period)**
- **DEATH_EVENT** (Target variable indicating survival or fatality)

## Model Training
The `heart.py` script processes the dataset and trains different machine learning models. The steps include:

1. **Data Preprocessing:** The dataset is loaded, and features (X) and target variable (y) are separated.
2. **Data Splitting:** The dataset is split into training and testing sets using `train_test_split`.
3. **Model Training:** The project implements multiple ML algorithms, including:
   - Decision Tree Classifier
   - Random Forest Classifier
4. **Evaluation:** Models are tested on unseen data, and accuracy scores are calculated.
5. **Model Serialization:** The best-performing model is saved as a Pickle (`.pkl`) file for later use.

## Web Application (Streamlit)
The `app.py` script powers the web-based frontend using Streamlit. Key features:
- **User-friendly UI:** Patients or doctors can input health parameters.
- **Model Integration:** The trained model (`hf1.pkl`) is loaded to make real-time predictions.
- **Automated Browser Launch:** The app opens automatically in the browser for easy access.

## How It Works
1. User inputs medical data (e.g., age, diabetes status, blood pressure, etc.).
2. The system processes the input and applies the trained model.
3. A prediction result is displayed, indicating the risk level of a heart attack.

## Why This Matters
- **Early Detection:** Helps identify at-risk individuals before serious complications.
- **AI-Powered Insights:** Provides an objective analysis based on historical data.
- **User-Friendly:** Accessible to medical professionals and patients.

## Future Enhancements
To improve this project, we could:
- Integrate Deep Learning models for higher accuracy.
- Expand the dataset for better generalization.
- Develop a mobile-friendly version for broader accessibility.
- Add data visualization features for better interpretability.

## Conclusion
This Heart Attack Prediction System is a step towards AI-driven preventive healthcare. By leveraging machine learning and Streamlit, this project provides an easy-to-use solution for early risk assessment. With continuous improvements, it could become a valuable tool for predictive analytics in healthcare.

## Installation and Usage
### Prerequisites
Ensure you have Python installed and install the required dependencies using:
```bash
pip install -r requirements.txt
```

### Running the Application
Run the following command to start the Streamlit app:
```bash
streamlit run app.py
```
The application will launch in your default web browser.

## License
This project is licensed under the MIT License.

## Author
Developed by Rishabh Saini


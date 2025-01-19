# **LiverRisk Predictor** ❤

This repository contains all the necessary files for deploying a **Machine Learning Web Application** built with **Flask**. The application is designed to predict the likelihood of liver disease in patients based on medical records. 


---

## **Problem Statement**

The dataset consists of patient records, with each record containing medical test results and a class label indicating whether the patient has liver disease or not. The objective of the project is to use these patient records to predict whether a new patient is at risk for liver disease based on the provided medical features.

The dataset includes:
- **416 records** of patients with liver disease (labeled as `1`).
- **167 records** of patients without liver disease (labeled as `0`).
- **441 male patients** and **142 female patients**.

The goal is to develop a machine learning model that can take in various medical features, such as **bilirubin levels**, **liver enzyme values**, and **albumin levels**, and predict the likelihood of a liver disease diagnosis.

---

## **Dataset**

The dataset used for training the model is the **Liver Disease Dataset**, which contains the following features:

- **Age**: Age of the patient.
- **Gender**: Gender of the patient (1 = Male, 0 = Female).
- **Total Bilirubin**: Total bilirubin level in the blood.
- **Alkaline Phosphatase**: An enzyme found in the liver, bones, kidneys, and bile ducts.
- **Alamine Aminotransferase (ALT)**: Liver enzyme that helps break down proteins.
- **Aspartate Aminotransferase (AST)**: Liver enzyme involved in amino acid metabolism.
- **Total Proteins**: The total amount of proteins in the blood, consisting of albumin and globulin.
- **Albumin**: A protein produced by the liver, important for maintaining blood volume.
- **Albumin and Globulin Ratio**: The ratio of albumin to globulin proteins in the blood.

These features are used to classify whether a patient is at risk for liver disease or not.

---

## **Technologies Used**

- **Python**: For the development of the machine learning model and backend logic.
- **Machine Learning**: Using classification algorithms to predict liver disease.
- **Pandas**: For data manipulation and preprocessing.
- **NumPy**: For numerical computing and handling data arrays.
- **Scikit-learn**: For implementing machine learning models and evaluation metrics.
- **Flask**: For building the web application and deploying the model.
- **HTML**: For creating the structure and layout of the web interface.
- **CSS**: For styling the web pages.
  

---

## **How the Model Works**

1. **Data Preprocessing**:
   - The data is cleaned and preprocessed by handling missing values, normalizing the data, and encoding categorical features (like gender).
   
2. **Model Training**:
   - Several machine learning classification algorithms (like Logistic Regression, Random Forest, etc.) are trained on the dataset.
   - After training, the best-performing model is selected based on evaluation metrics such as accuracy, precision, recall, and F1-score.

3. **Prediction**:
   - The web application takes in user input (age, gender, bilirubin levels, etc.) and processes it through the trained model to predict whether the patient has liver disease or not.
   
4. **Output**:
   - The prediction is displayed on the web interface, providing a simple and accessible way to determine liver disease risk.

---

## **Features**

- **User Input**: The web interface allows users to input the necessary medical test results to predict liver disease risk.
- **Model Prediction**: Based on the input data, the machine learning model predicts the likelihood of liver disease.
- **Web Interface**: Built with **Flask**, the app has a simple and intuitive design that allows for easy interaction.

---

## **Contribution**

Feel free to fork this repository and contribute to the project! If you find any issues or have suggestions for improvements, please open an issue or create a pull request.

---

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## **Acknowledgments**

- The dataset used in this project was sourced from various healthcare records.
- Special thanks to the contributors and the open-source community for providing the tools and libraries used in this project.

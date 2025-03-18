# Mitigating Bias in Machine Learning Models for Student Depression Prediction

## Project Overview
This project focuses on identifying and mitigating bias in a machine learning model that predicts student depression. Various bias mitigation strategies were tested, including:
- **SMOTE (Synthetic Minority Over-sampling Technique)**
- **Massaging (Preprocessing)**  
- **Fairness Loss Function (In-processing)**
- **Oversampling (Preprocessing)**  

The goal is to improve fairness while maintaining model performance.

## Dataset
The dataset used in this project contains student demographic information and mental health indicators. It includes sensitive attributes such as **education level**, which may introduce bias into predictions.

## Technologies Used
- **Python**  
- **Scikit-Learn** (Machine Learning Models)  
- **Fairlearn** (Fairness Metrics)  
- **Imbalanced-learn** (SMOTE)  
- **Matplotlib & Seaborn** (Data Visualization)  

## Bias Mitigation Strategies
We tested the following techniques to reduce bias and improve fairness:
1. **Preprocessing: SMOTE** (Lance) - Resampled training data to balance groups.  
2. **Preprocessing: Massaging** (Megan) - Adjusted labels for fairness before training.  
3. **In-processing: Fairness Loss Function** (Cole) - Modified the loss function to penalize unfair predictions.  
4. **Preprocessing: Oversampling** (Arnav) - Increased representation of underrepresented groups in the dataset.  

## Key Findings
- **Fairness Loss Function** had the **best performance improvement**, increasing accuracy by **5.76%** while reducing bias.  
- **SMOTE with Scaling** improved accuracy by **3.5%** and significantly lowered bias.  
- **Oversampling** had a **minimal impact**, improving accuracy by only **0.05%**.  
- **Massaging** had **negative fairness effects**, increasing bias despite slightly improving accuracy.

## References
- Fairlearn Documentation
- Imbalanced-Learn (SMOTE)
- Bias Mitigation Strategies

## Contributors
- Lance Santana - SMOTE + Scaling
- Megan Yip - Massaging
- Cole Hammes - Fairness Loss
- Arnav Swami - Oversampling

## Disclaimer: 
AI was used for debugging, refining methods, and improving explanations.

# Predicting Phishing Attempts by Disassembling and Analyzing URLs

## Project Overview
This project aims to build and compare machine learning models to detect phishing attempts based on the structure of URLs. Phishing remains one of the most prevalent cyber threats, and this project seeks to develop effective models that can identify potential phishing websites.

## Features
- **Data Source**: Phishing Websites Dataset (Mendeley Data)
- **Data Preprocessing**: Handling missing values, feature extraction from URL components, and outlier analysis.
- **Model Training**: Multiple models were trained, including Logistic Regression and Random Forest, to predict phishing attempts.
- **Feature Analysis**: Quantile-Quantile (Q-Q) plots and visualizations were used to assess URL patterns, including dots, hyphens, slashes, and other elements indicative of phishing.

## Key Steps
1. **Data Preparation**: 
   - Preprocessing URL data by extracting relevant features (e.g., quantity of dots, slashes).
   - Handling outliers through various techniques such as keeping or imputing outlier values.
   
2. **Model Training and Evaluation**:
   - Training of Logistic Regression and Random Forest models.
   - Evaluation based on accuracy and AUC scores, with Random Forest showing superior performance.

3. **Results**:
   - Random Forest achieved an accuracy of 97.1% and an AUC score of 96.9%, outperforming Logistic Regression.
   - Retaining outliers in the dataset improved model performance.

4. **Visualization**:
   - Visualizations include box plots and bar graphs showing the importance of features such as URL directory length.

## Contributors
- Logan Warren
- Xavier Bear
- Charles Tran

## License
This project is licensed under the MIT License.

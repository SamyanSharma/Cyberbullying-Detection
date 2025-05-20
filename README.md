# Cyberbullying Detection

[![Project Status](https://img.shields.io/badge/Status-Active-success.svg)](https://github.com/Samyan1Sharma/Cyberbullying-Detection)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/Samyan1Sharma/Cyberbullying-Detection/blob/main/LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](https://github.com/Samyan1Sharma/Cyberbullying-Detection/blob/main/CONTRIBUTING.md)
![Machine Learning](https://img.shields.io/badge/Type-Machine_Learning-blue)
![NLP](https://img.shields.io/badge/Focus-Natural_Language_Processing-brightgreen)
![Python](https://img.shields.io/badge/Language-Python-blue)

A ML Model for detecting toxic content in text using machine learning, achieving **81.28% accuracy** with Random Forest classification.

## 📌 Overview
This project develops a machine learning model to detect cyberbullying in digital text. By analyzing language patterns, it automatically flags potentially harmful content (harassment, hate speech, or toxicity) to support safer online interactions. This machine learning model detects cyberbullying in text using the [Cyberbullying Classification Dataset](https://www.kaggle.com/datasets/andrewmvd/cyberbullying-classification). Our **Random Forest model achieves 81.28% accuracy**, outperforming 5 other algorithms.

## 🎯 Objectives
- Automated Detection: Deploy ML models to flag cyberbullying with high precision.
- Scalability: Ensure the solution adapts to large-scale social media data.
- Bias Mitigation: Minimize false positives/negatives through robust model training.
- Actionable Insights: Provide transparency in detection for fair moderation.

## 📊 Performance Highlights
| Model               | Test Accuracy | ROC AUC  |
|---------------------|---------------|----------|
| **Random Forest**   | 81.28%        | 0.954    |
| Logistic Regression | 72.73%        | 0.914    |
| LinearSVC          | 69.31%        | 0.894    |
> *Full comparison available in [Cyberbullying Detection/Cyber_Bullying_Detection_Final.ipynb](Cyberbullying%20Detection/Cyber_Bullying_Detection_Final.ipynb)*

## ✨ Key Features

- **High Accuracy**: 81.28% test accuracy with Random Forest
- **Multiple Algorithms**: Comparison of 6 or more different models
- **Comprehensive Metrics**: Accuracy, cross-validation scores, and ROC AUC

## 🛠 Technical Implementation

### Dataset
- **Source**: Kaggle ([Cyberbullying Classification Dataset](https://www.kaggle.com/datasets/andrewmvd/cyberbullying-classification))
- **Samples**: 47692 labeled text entries
- **Classes**:
The model detects six types of text content:
  - 👴 `Age`  
  - 🌍 `Ethnicity`  
  - ⚧️ `Gender`  
  - 🕌 `Religion`  
  - 💢 `Other Cyberbullying`  
  - ✅ `Not Cyberbullying`  
- **Preprocessing**:
  - Text Cleaning (special characters, lowercase)
  - Text Stemming
  - Text Lemmatization
  - TF-IDF Vectorization


### Evaluation Metrics
- Precision, Recall, F1-Score (to handle class imbalance).
- Confusion Matrix for error analysis.
- AUC-ROC to evaluate model robustness.

## Contributing 
We warmly welcome contributions to the Cyberbullying Detection project! Please checkout [CONTRIBUTING](CONTRIBUTING.md) for more information.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details..

## Acknowledgments
- Thanks to all contributors who have helped make this project possible
- Special thanks to the open-source community for their invaluable tools and libraries

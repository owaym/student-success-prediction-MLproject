# Student Success Prediction in Education

## Overview

Education plays a crucial role in our lives, and even during the pandemic, we continued to receive education through both online and offline resources. Recent advancements in educational technologies have greatly influenced the field of education, and it has become essential for institutions to adapt to these changes.

The purpose of this project was to explore whether it is possible to predict student success based on features collected through the Open University (OU) dataset. Additionally, we aimed to investigate whether the demographics of students can be used to predict their achievements.

## Dataset

The dataset consists of 7 different courses presented to students via online platforms. This publicly available dataset has been used in various research articles, and for this project, we leveraged it to predict students' success. 

### Key Features of the Dataset:
- Data related to student demographics.
- Features from online courses, including course performance indicators.

## Objective

The main goal of the project was to:
- Predict students' success using demographic features and course performance data.
- Evaluate the impact of various algorithms on prediction accuracy.

## Methodology

The model was built using **Python 3.0**. Various machine learning algorithms were implemented to predict students' success and compare their performance:

- **Random Forest**
- **Decision Tree**
- **Support Vector Machine (SVM)**
- **FeedForward Neural Network**
- **K-Nearest Neighbors (KNN)**
- **Gradient Boosting (XGBoost)**
- **Naïve Bayes**

### Algorithm Performance:
- **Best performing algorithm:** Random Forest.
- **Poorest performing algorithm:** Naïve Bayes.

## Challenges

The dataset had several missing values, which posed challenges during the model training process. Additionally, predicting student success is inherently complex, as many factors influence the outcomes, such as personal, academic, and external factors.

## Conclusion

The results of this project suggest that it is indeed possible to predict student success based on course data and demographics. While the Random Forest model showed the best performance, further research is required to refine the predictions, especially considering the complexity of student success. We hope that further research in this area will contribute to the improvement and development of educational technology systems.

## Future Work

- Improve data preprocessing and handling of missing values.
- Investigate the inclusion of more complex features or external factors.
- Explore other machine learning models and their combinations for better prediction.

## Dependencies

- Python 3.0
- Libraries: `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `xgboost`, etc.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.


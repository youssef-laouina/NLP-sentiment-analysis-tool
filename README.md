# Sentiment Analysis on Amazon Fine Food Reviews
## Overview
This project focuses on sentiment analysis using Amazon Fine Food reviews. The main objective is to build a robust model capable of accurately predicting the sentiment of reviews. Two models were developed: a Random Forest Classifier and a Passive-Aggressive Classifier. Throughout the project, special attention was given to the inconsistencies in the predictions and the importance of model calibration to enhance performance.

## Project Structure
The project is structured as follows:

1. Data Collection: Amazon Fine Food reviews dataset.
2. Data Preprocessing: Cleaning and preparing the data for model training.
3. Model Development: Implementing Random Forest and Passive-Aggressive Classifiers.
4. Model Calibration: Assessing and calibrating the models to improve prediction reliability.
5. Evaluation: Measuring the accuracy of the models on test and validation datasets.

## Key Insights
**Model Calibration**: Initially, the models exhibited poor calibration. Through calibration techniques, the prediction reliability significantly improved.
**Calibration Techniques**: Both ***PLATT*** scaling and ***SPLINE*** calibration were tested. PLATT scaling proved to be the most effective for both models.
**Performance**: After calibration, both models showed substantial improvements in accuracy on validation data.

## Model Performance
### Random Forest Classifier
- Accuracy on Test Data: ~70%
- Accuracy on Validation Data: 90%

### Passive-Aggressive Classifier
- Accuracy on Test Data: ~80%
- Accuracy on Validation Data: 100%

## Inconsistencies and Calibration
During the project, it was observed that the initial predictions were inconsistent, leading to unreliable sentiment analysis. The calibration of models was crucial in resolving these issues. PLAT scaling was particularly effective in enhancing the reliability and accuracy of both the Random Forest and Passive-Aggressive classifiers.

## Conclusion
This project demonstrates the significance of model calibration in sentiment analysis. By focusing on the inconsistencies and employing effective calibration techniques, we achieved high accuracy levels, especially on validation data. The Random Forest classifier and Passive-Aggressive classifier both benefited from PLAT scaling, showcasing the potential of calibration in improving model performance.

### Model Performance Summary

#### Logistic Regression
- **Accuracy**: 0.878
- **Precision**: 0.857
- **Recall**: 0.692
- **F1 Score**: 0.766
- **AUC**: 0.89

#### Decision Tree
- **Accuracy**: 0.867
- **Precision**: 0.938
- **Recall**: 0.577
- **F1 Score**: 0.714
- **AUC**: 0.85

### ROC Curve
The ROC curve visually represents the trade-off between the true positive rate (sensitivity) and the false positive rate (1 - specificity) for the models. Below is the ROC curve:

![image](https://github.com/user-attachments/assets/a30fdbb5-52e2-4f11-95b7-f2cec9218c62)


### Analysis
- **Logistic Regression** shows a well-balanced performance with a high recall and precision, indicating it effectively identifies positive cases while maintaining a low false positive rate. Its AUC of 0.89 suggests it is a strong model for distinguishing between the classes.
  
- **Decision Tree** performs well in terms of precision, but its lower recall indicates that it misses some positive cases. The AUC of 0.85, while still good, suggests that the Decision Tree model is slightly less effective compared to Logistic Regression in this dataset.

### Conclusion
Overall, the **Logistic Regression model** outperforms the Decision Tree in most metrics, particularly in recall and AUC. Given these results, Logistic Regression would be the recommended model for predicting the occurrence of death events in patients with heart failure.

If you need further assistance with analysis or model improvement strategies, feel free to ask!

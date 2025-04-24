# ⚡ Power Consumption Prediction in Tetouan City using Machine Learning

This project focuses on leveraging machine learning algorithms to predict power consumption in Tetouan City, Morocco, based on environmental data collected throughout the year 2017. The dataset includes factors such as temperature, humidity, wind speed, and solar radiation, along with power usage in three distribution zones: Quads, Smir, and Boussafou.
We analyzed three energy zones separately and built predictive models for each. In addition to regression tasks, we also categorized consumption levels for classification models.

---

## Dataset Description

- **Source**: UCI Machine Learning Repository
- **Period Covered**: January 1, 2017 – December 30, 2017
- **Instances**: 52,417
- **Features**: Temperature, Humidity, Wind Speed, General/Diffuse Flows, DateTime (engineered), and Zone-specific power consumption.

---

## Methodology

- **Feature Engineering**: Extracted temporal features (hour, day, month, etc.)
- **Model Types**:
  - Regression: Decision Tree, Random Forest, KNN, SVR, Neural Networks
  - Classification: Naïve Bayes, KNN (categorical), Neural Networks (with bins)
- **Evaluation Metrics**: MAE, RMSE, R² for regression; Accuracy, Precision, Recall for classification



## Conclusion

This study shows that advanced models like Random Forests and Neural Networks are well-suited for energy prediction tasks. Future work could include real-time predictions and model deployment.

---

## References

- UCI Machine Learning Repository: [Power Consumption of Tetouan City](https://archive.ics.uci.edu/ml/datasets/Power+consumption+of+Tetouan+city)
- Scikit-learn Documentation
- TensorFlow Documentation

---

## Team and Contributions

### Students:
| Name              | Group | 
|-------------------|-------|
| YAGOUB Douaa Manel| 03    |
| BOUDAOUD Amira    | 02    |
| MERS Wafaa        | 03    |

**Project Date**: April 2024  
**Institution**: [ENSIA]

---

##  Files Included

- `notebook`: Jupyter Notebooks for analysis and modeling
- `report`: Final project report and visualizations
- `README.md`: Project summary and credits

---

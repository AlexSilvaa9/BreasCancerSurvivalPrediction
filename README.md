### Breast Cancer Survival Prediction

#### Author: Alejandro Silva Rodriguez

#### Available on: [webpage](https://alexsilvaa9.github.io/BreasCancerSurvivalPrediction/)

---

### Overview

This repository contains the code and documentation for a project focused on developing predictive models in biomedicine, particularly aimed at estimating the probability of survival in cancer patients. The project employs a dataset comprising clinical and demographic variables related to cancer patients.

---

### Table of Contents

1. **Introduction**
   - Provides an overview of the project's objective and dataset description.

2. **Data Cleaning**
   - Covers the process of importing and cleaning the dataset, including transformations and summary statistics.

3. **Statistical Analysis**
   - Includes univariate analysis, homogeneity analysis, bivariate analysis, and association analysis.

4. **Models Comparison**
   - Compares different predictive models and variable selection methods to identify the most effective approaches.

5. **Deployment**
   - The final model is deployed in a Shiny app. You can access the Shiny app to predict the probability of survival in breast cancer patients based on the selected variables by visiting this [link]([webpage](https://alexsilvaa9.github.io/BreasCancerSurvivalPrediction/).

---

### Conclusion

In this project, we have compared the performance of various machine learning algorithms for predicting survival rates in breast cancer. We have adapted the validation process and the hyperparameter selection to our computational resources.

In the variable selection process, we found that the most performant technique is the wrapper method, although it is computationally expensive. The filter method is less computationally intensive but does not consider the interaction between variables. Embedded methods offer a good compromise between the two previous methods but are not as performant as the wrapper method.

The final model uses a Neural Network, achieving an AUC of 0.87 in the cross-validation process. The model is deployed in a Shiny app, which allows users to predict the probability of survival in breast cancer based on four variables: age at diagnosis, year of diagnosis, tumor stage, and tumor grade.

The next step is to carry out external validation of the model. This process will enable us to evaluate the model's performance on new data.

---

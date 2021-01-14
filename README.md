This portfolio consists of 5 projects. Specifically, 

**[Project1]** used multiple feature-selection-based linear regression models and tree-based regression models to **predict house prices**. One file is the [final report]([Project1.2]PredictingHousePrices_Report.pdf) and the other one is the [presentation slides]([Project1.1]PredictingHousePrices_Slides.pdf).

> - Used 𝑑𝑝𝑙𝑦𝑟 and 𝑡𝑖𝑑𝑦𝑟 packages (𝑅 language) for data cleaning and feature engineering.
> - Built linear regression model based on forward stepwise feature selection, lasso regression, pruned decision tree, and random forest to forecast house prices.
> - Tuned hyperparameters using 10-fold cross validation; Visualized the hyperparameter tuning using ggplot2.
> - Received a RMSE of 0.1428 on validation set on Kaggle and 98 points out of 100 in the class.

**[Project2]** used 5 linear classification models and 8 non-linear classification models to **predict whether an insurance claim is fraud or not**. One file is the [final report]([Project2.2]AutoInsuranceFraudClaimsDetection_Report.pdf) and the other one is the [presentation slides]([Project2.1]AutoInsuranceFraudClaimsDetection_Slides.pdf).

> - Selected and generated predictors from raw data; Explored and visualized relationships between predictors and response variable.
> - Applied up-sampling method and alternate cutoff method to improve the negative effect of imbalanced data.
> - Built 5 linear models, including LDA, Sparse LDA, PLS-DA, Logistic Regression, and penalized Logistic Regression.
> - Built 8 nonlinear models, including MDA, Neural Network, Averaged Neural Network, SVM, KNN, Decision Tree, Random Forest, and Gradient Boosting Tree.
> - Tuned hyperparameters using 10-fold cross validation.
> - Best model: Gradient Boosting Tree with an alternate cutoff of 0.25. AUC = 0.8849, Sensitivity:0.86, Specificity:0.87.


**[Project3]** used multiple linear regression, KNN, single-hidden-layer neural network, averaged neural network, regression tree, and random forest models to **predict airbnb prices**. One file is the [final report]([Project3.2]AirbnbPredictionReport.pdf) and the other one is the [presentation slides]([Project3.1]AirbnbPredictionSlides.pdf). All algorithms are manually derived in the final report.

**[Project4]** used linear regression and single-hidden-layer neural network to **predict a user's viewport trajectory when watching a 360 video**, given different conditions, including whether use gaze data, different durations of prediction window and history window, and latitude position prediction or longitude position prediction. The [final result]([Project4.2]ViewportPrediction.png) is visualized in the .png file and the [detailed introduction]([Project4.1]ViewportPredictionCode.ipynb) is included in the .ipynb file.

**[Project5]** is a [Micromap visualization project]([Project5]LinkedMicromapVisualization.pdf).

# Handwritten Digits Classification

In this project, the effectiveness of five classification-based machine learning algorithms: K-Nearest Neighbours, Decision Trees, Logistic Regression, Support Vector Machines, and Random Forest are evaluated with the aim of identifying the most effective algorithm for classifying [handwritten digits](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html).

<p align="center">
  <img src="https://github.com/jxne00/handwritten-digits/blob/main/src/digits_plot.png" alt="Plot of handwritten digit images" width="800">
</p>

## Results

The results reveal that the Support Vector Machine performed best with an accuracy of 98.06%, while the Decision Tree algorithm showed subpar performance with an accuracy of 88.89%. 

<p align="center">
  <img src="https://github.com/jxne00/handwritten-digits/blob/main/src/final_metrics.png" alt="Dataframe with metrics for each algorithm" width="600">
</p>

### SVM

Confusion Matrix:

<img src="https://github.com/jxne00/handwritten-digits/blob/main/src/svm_confusion_matrix.png" alt="confusion matrix for SVM" width="600">

Plot of handwritten digit images with their predicted and actual label:

<img src="https://github.com/jxne00/handwritten-digits/blob/main/src/svm_pred_vs_actual.png" alt="Plot of images with SVM predicted and actual labels" width="800">

# Rock V/S Mine Classification Project

This project uses logistic regression to classify objects as either **rock** ('R') or **mine** ('M') based on sonar signal data. The dataset contains 60 features, representing the energy reflected from sonar signals, and the goal is to build a model that predicts whether the object is a rock or a mine.


## Model

We used **Logistic Regression** from the `scikit-learn` library to classify the objects. The dataset was split into training (90%) and test (10%) sets, stratified to maintain an equal distribution of rock and mine samples.

### Steps:
1. **Data Loading**: The dataset is loaded from `sonar_data.csv`.
2. **Preprocessing**: The 60th column, containing labels ('R' for rock, 'M' for mine), is separated from the features.
3. **Model Training**: The logistic regression model is trained on the training data.
4. **Evaluation**: We calculate accuracy on both the training and test sets and create various visualizations to interpret the results.

## Results

- **Training Accuracy**: 83.42%
- **Test Accuracy**: 76.19%

## Visualizations

1. **Training vs Test Accuracy**: A bar plot comparing the accuracy of the model on the training and test datasets.
2. **Confusion Matrix**: A heatmap representing the confusion matrix, showing how well the model classifies rocks and mines.

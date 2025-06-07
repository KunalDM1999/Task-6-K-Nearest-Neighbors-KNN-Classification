# Task-6-K-Nearest-Neighbors-KNN-Classification
1. Dataset Used:
Iris dataset with 150 samples and 5 columns (4 features + 1 target: Species).

2. Target Variable:
Species with 3 classes — Iris-setosa, Iris-versicolor, Iris-virginica (balanced: 50 each).

3. Libraries Used:
pandas, numpy, matplotlib, seaborn, scikit-learn.

4. Preprocessing Done:

* Dropped Id column.

* Encoded Species using LabelEncoder.

* Scaled features using StandardScaler.

5. Exploratory Data Analysis:

* Plotted distribution plots for all features.

* Detected 4 outliers in SepalWidthCm.

* Found 0.96 correlation between PetalLengthCm and PetalWidthCm.

6. Train-Test Split:
Split dataset into training and testing sets (80% train, 20% test) using train_test_split.

7. Model Training:
Used KNeighborsClassifier from sklearn with multiple values of K.

8. Model Evaluation:

* Evaluated using accuracy and confusion matrix.

* Found lowest error rates at K = 9, 11, 14.

9. Feature Selection for Visualization:
Chose PetalLengthCm and PetalWidthCm for 2D visualization due to high correlation and clear separation of classes.

10. Decision Boundary Visualization:

* Plotted 2D KNN decision boundaries with test/train points.

* Visualized class regions and interpretation showed clear boundaries and good performance.

# EXPERIMENT 3: ENSEMBLE LEARNING (BAGGING & BOOSTING)

### 1. Aim
To implement Ensemble Learning techniques such as Bagging and Boosting using Python libraries.

### 2. Resources Required
1. Dataset file.
2. Google Colab.
3. Minimum 4 GB RAM.
4. Intel i5 processor or above.
5. Python libraries.

### 3. Theory

**1. Ensemble Learning**

Ensemble Learning is a machine learning technique that combines multiple models to produce better and more accurate predictions than a single model.

It uses multiple decision trees or weak learners and combines their results to improve overall performance.

There are two main techniques of Ensemble Learning:

**A. Bagging (Bootstrap Aggregating)**

Bagging is an ensemble learning technique used to reduce variance and improve prediction accuracy.

- Multiple subsets of the original dataset are created randomly using replacement.
- Different decision trees are trained on these subsets.
- The final prediction is obtained by combining the predictions of all trees.
- Random Forest is a popular example of Bagging.

**Steps of Bagging:**

1. Select random samples from the training dataset with replacement.
2. Train a separate decision tree on each sample.
3. Repeat the process to create multiple decision trees.
4. Combine the predictions of all trees to get the final result.

**Advantages of Bagging:**
1. Reduces overfitting and variance.
2. Works well with large datasets.
3. Improves prediction accuracy.
4. Handles high-dimensional data effectively.

**Disadvantage:**
- Requires more memory and computational power because multiple models are trained.

**B. Boosting**

Boosting is an ensemble learning technique that combines multiple weak learners to create a strong learning model.

- Models are trained one after another.
- Each new model focuses more on the errors made by the previous model.
- The final prediction is obtained by combining the results of all models.
- Gradient Boosting is a popular example of Boosting. It uses a gradient descent approach to reduce errors.

**Steps of Boosting:**

1. Train the first model using the training dataset.
2. Identify the incorrectly predicted samples.
3. Give more importance to the samples that were predicted incorrectly.
4. Train the next model to reduce the previous errors.
5. Combine the predictions of all models to get the final output.

**Advantages of Boosting:**
1. Improves prediction accuracy.
2. Supports different loss functions.
3. Converts weak learners into strong learners.
4. Works well with complex datasets.

**Disadvantages:**
1. Requires proper tuning of hyperparameters.
2. Training can take more time because models are trained sequentially.

### 4. Conclusion
Hence, we have successfully implemented Ensemble Learning techniques such as Bagging and Boosting on a dataset using Python libraries.
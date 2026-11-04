# EXPERIMENT 2: LOGISTIC REGRESSION

### 1. Aim
To implement Logistic Regression using Python libraries.

### 2. Resources Required
1. Dataset file.
2. Google Colab.
3. Python libraries (NumPy, Pandas, Matplotlib and Scikit-learn).
4. Minimum 4 GB RAM.
5. Intel i5 processor or above.

### 3. Theory

**1. Logistic Regression**

Logistic Regression is a supervised machine learning algorithm used for classification problems.

- It predicts a categorical dependent variable using one or more independent variables.
- Unlike Linear Regression, it predicts categories such as Yes/No, True/False and 0/1.
- Example: Predicting whether a passenger survived or not using the Titanic dataset.

**2. Working of Logistic Regression**

1. Collect the dataset containing independent and dependent variables.
2. Divide the dataset into training and testing data.
3. The algorithm learns the relationship between input and output variables.
4. Calculate the probability of a particular class.
5. Convert the probability into a final class using a threshold value.

**3. Sigmoid Function**

Logistic Regression uses a mathematical function called the Sigmoid Function or Logistic Function.

- It converts predicted values into probabilities between 0 and 1.
- Its output forms an S-shaped curve.

**Formula:**

S(x) = 1 / (1 + e⁻ˣ)

Where:
- S(x) = Predicted probability.
- e = Euler's mathematical constant.
- x = Input value.

**4. Threshold Value**

A threshold is used to convert predicted probability into a category.

Default threshold = **0.5**

- If probability ≥ 0.5 → Class 1 (Yes).
- If probability < 0.5 → Class 0 (No).

Example:
- Probability 0.8 → Survived.
- Probability 0.3 → Not Survived.

**5. Types of Logistic Regression**

1. **Binary Logistic Regression:** Used for two categories, such as Yes/No or Pass/Fail.
2. **Multinomial Logistic Regression:** Used for more than two unordered categories, such as Car, Bus or Train.
3. **Ordinal Logistic Regression:** Used for more than two ordered categories, such as Poor, Average, Good and Excellent.

**6. Applications**
1. Email spam detection.
2. Disease prediction.
3. Customer churn prediction.
4. Loan approval prediction.
5. Fraud detection.
6. Student pass/fail prediction.

### 4. Conclusion
Hence, we have successfully implemented Logistic Regression on the Titanic training dataset using Python libraries. The model predicts categorical outcomes by calculating probabilities using the Sigmoid Function and classifying them using a threshold value.
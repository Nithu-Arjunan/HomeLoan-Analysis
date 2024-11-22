**Overview**

This project aims at building a deep learning model to predict the chance of default for future loans using historical data. The dataset is highly imbalanced and includes a lot of features that make this problem more challenging.

**Model Architecture**

The deep learning model comprises:

Input Layer: 14 features as input.

Hidden Layers: 5 fully connected layers with ReLU activation.

Dropout applied at varying rates (0.2–0.6).

Batch Normalization after each layer.

Ridge(l2) regularization applied to mitigate overfitting.

Output Layer: A single neuron with a sigmoid activation for binary classification.

**Techniques Used**

Data Preprocessing:

Missing value imputation.

Outlier detection and treatment (Winsorization and box plots).

SMOTE for handling class imbalance.

Regularization:
Ridge (L2)

Optimization:
Adam optimizer.

Model Evaluation:
Accuracy, Recall, Precision, and Loss.

**Results**

Accuracy: 82%

The model successfully achieves a good balance between training and validation accuracy with reduced overfitting after applying dropout, batch normalization, and regularization.

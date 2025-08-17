🔧 Generator Failure Prediction using Neural Networks
📌 Overview

This project develops and tunes deep neural network models to predict generator failures before they occur. The goal is to enable predictive maintenance, reducing overall costs by catching issues early:

1 = Failure (repair needed)

0 = No Failure

Cost implications of predictions:

✅ True Positive (TP): Correctly predicts failure → Repair cost (preferred).

❌ False Negative (FN): Missed failure → Replacement cost (most expensive).

⚠️ False Positive (FP): Predicts failure when none → Inspection cost (least expensive).

The model emphasizes recall to minimize false negatives and reduce replacement costs.

🛠 Features

Built multiple Neural Network architectures using TensorFlow/Keras

Hyperparameter tuning for:

Optimizers (SGD, Adam)

Learning rate & momentum

Activation functions & weight initializers (He, Xavier)

Dropout & Batch Normalization

Evaluation using Accuracy, Precision, Recall, F1-score

Addressed class imbalance via class weighting, threshold tuning, and SMOTE experiments

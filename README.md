# ECG-Time-Series-Classification

Comparison of Models

In the task of ECG time-series classification, three models—1D CNN, 2D CNN, and a Multi-class Neural Network—were compared based on their accuracy and classification metrics.

1.The 1D CNN achieved an accuracy of 93.60% and demonstrated strong performance across all classes, with particularly high true positive (TP) rates for Class 4 (0.99) and Class 2 (0.97). Its classification report highlights balanced precision, recall, and F1-scores for all classes, indicating robust generalization and accurate predictions for the time-series data.



2.The 2D CNN, designed to leverage spatial relationships, outperformed the 1D CNN slightly, with an accuracy of 93.97%. It exhibited slightly better recall for Classes 0, 2, and 3 compared to the 1D CNN and maintained high precision and F1-scores across all categories. Its TP rates were consistently high, particularly for Class 4 (0.98) and Class 2 (0.96).



3.The Multi-class Neural Network attained a slightly lower accuracy of 92.43%, which, although respectable, lagged behind the CNN architectures. The precision, recall, and F1-scores were slightly lower across most classes, especially for Class 0. The model performed well overall but did not capture the sequential patterns in the ECG time-series data as effectively as the CNNs.



Advantages of Using the 2D CNN:

Higher Accuracy and Robustness: The 2D CNN achieved the best overall accuracy, demonstrating superior ability to extract features from ECG data by leveraging spatial relationships.

Balanced Performance Across Classes: The model consistently performed well for all classes, reducing the likelihood of misclassification in critical classes.

Suitability for Complex Patterns: ECG data often exhibit intricate temporal and spatial patterns. The 2D CNN effectively captures these patterns, making it highly suitable for tasks where spatial features are significant.

Improved Generalization: The higher precision, recall, and F1-scores across all classes indicate better generalization to unseen data compared to the other models.

Why Choose the 2D CNN Over Others?

While the 1D CNN and Multi-class Neural Network are computationally less demanding, the 2D CNN's ability to leverage spatial relationships in the ECG data gives it a critical edge for accuracy and reliability. This is particularly important in medical diagnostics, where even small improvements in classification performance can lead to significant real-world benefits, such as earlier and more accurate detection of cardiac abnormalities. The slightly higher computational cost of the 2D CNN is justified by its superior performance and potential to reduce diagnostic errors.

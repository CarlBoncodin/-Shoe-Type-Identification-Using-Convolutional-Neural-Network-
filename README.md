# Shoe Type Identification Using Convolutional Neural Network

This project leverages Convolutional Neural Networks (CNNs) for automating the categorization of shoes in disaster relief efforts. Traditional methods of shoe type identification in such scenarios are often insufficient, leading to inefficiencies. By employing CNNs, specifically a model inspired by AlexNet, this project aims to enhance the accuracy and efficiency of shoe classification. The goal is to streamline the sorting process, thereby improving the overall effectiveness of disaster relief operations and potentially influencing the footwear industry.

Objectives
-
- Automate Shoe Categorization: Develop a CNN-based system to automatically classify shoe types from images.
- Achieve High Accuracy: Train the CNN model to reach a validation accuracy of at least 85%.
- Evaluate Performance: Test the model to ensure it achieves an accuracy greater than 75% on a separate test dataset.
- Suggest Improvements: Propose enhancements such as using a camera and expanding the dataset to improve model performance.

Methodology
-
- Dataset Preparation: Collect and preprocess a large shoe image dataset from Kaggle. Split the dataset into training (80%), validation (10%), and test (10%) sets.
- Data Augmentation: Apply image augmentation techniques such as rotation, scaling, and translation to enrich the training data and reduce overfitting.
- CNN Design: Create a CNN model in MATLAB with multiple convolutional layers, max-pooling, and fully connected layers inspired by AlexNet. Train the model using Stochastic Gradient Descent with Momentum (SGDM) for optimization.
- Training and Testing: Train the CNN model using the training dataset and validate it against the validation set. Test the final model on the test dataset to assess its performance and accuracy.

Result
-
The CNN model achieved an average validation accuracy of 90.67% and a test accuracy of 89.20%. This performance exceeds the initial goal of 85% validation accuracy and surpasses current literature benchmarks of 75% accuracy. The results indicate that the CNN effectively categorizes shoe types, demonstrating the potential for automated sorting in disaster relief operations. Further improvements are recommended, including the use of real-world camera data and expanding the dataset to enhance model accuracy and robustness.

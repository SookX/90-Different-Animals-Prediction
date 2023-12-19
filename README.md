# 90 Different Animals Prediction Model

## Overview

This repository contains a machine learning model aimed at predicting 90 different animal classes. The model has been trained on a dataset consisting of 5400 images, achieving significant accuracies on both the training and test data sets.

## Dataset

The dataset comprises 90 classes of animals, with 48 images per class used for training and 12 images per class for testing. For a more robust model, increasing the dataset size per class is recommended.

## Model Architecture and Performance

### Model 3

- **Accuracy:**
    - Training Data: 99.98%
    - Test Data: 95.56%
- **Architecture:** [Specify the architecture used, if applicable]
- **Training Parameters:** [Include relevant parameters used for training]

### Future Improvement Suggestions

1. **Extended Training (More Epochs):** Consider training the model for longer durations to potentially improve performance.
2. **Experiment with Different Architectures:** Explore alternative neural network architectures to identify better-performing models.
3. **Increase Data Quantity:** Obtain additional diverse images for each class to enhance the model's generalization.
4. **Avoid Fine-Tuning:** Refrain from excessive fine-tuning to prevent overfitting and maintain model robustness.

## Repository Structure

- `data/`: Contains the dataset used for training and testing.
- `models/`: Includes saved model weights and architectures.
- `results/`: Holds result logs, performance metrics, and evaluation summaries.

## Usage

1. **Dataset Preparation:** Ensure the dataset is structured correctly within the `data/` directory.
2. **Model Training:** Use the provided scripts or notebooks to train the model.
3. **Evaluation:** Assess the model's performance using the test data and record performance metrics.

## Future Work

Continued improvements and experiments will be conducted to enhance the model's accuracy and robustness. Contributions and suggestions are welcome.

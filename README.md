# Lung Cancer Detection using Deep Learning

This repository contains the final project for the Deep Learning course at Carnegie Mellon University Africa. The project focuses on leveraging deep learning techniques to improve the early detection of lung cancer using CT scan images and the EfficientNet-B7 model.

## Team Members

Our team is composed of the following members:
- **Pericles ADJOVI**
- **Ange IZABAYO**
- **Eric NIYIGENA**
- **Benjamin Hubert ISHIMWE**

## Context and Background

Lung cancer remains a leading cause of cancer-related mortality worldwide, primarily due to the challenges of early detection. This project aims to improve diagnostic accuracy and generalizability by utilizing the EfficientNet-B7 model trained on the LIDC-IDRI dataset, which contains CT scan images of lung nodules. The methodology includes data augmentation to balance class distribution and dropout regularization to mitigate overfitting.

## Dataset

We use a preprocessed version of the [LIDC-IDRI dataset](https://www.kaggle.com/datasets/mahounanpericles/ensemble-learning-on-lidc-dataset), available publicly on Kaggle. It contains CT scan images categorized into training, validation, and test sets.

## Project Structure

This repository includes the following files:


        ├── LICENSE
        ├── Pericles_implementation_baseline2.ipynb
        ├── README.md
        └── idl-group-17-code.ipynb



- **Pericles_implementation_baseline2.ipynb**: The baseline implementation of the model.
- **idl-group-17-code.ipynb**: The final implementation, incorporating optimizations and enhancements.

## How to Run

The notebooks can be executed on **Kaggle**, **Google Colab**, or **SageMaker**.

### Steps to Run:
1. Clone this repository or download the notebooks:
   ```bash
   git clone https://github.com/Pericles001/lungcancerdetectiondl.git
   cd lung_cancerdetectiondl

1.  Open one of the notebooks on your preferred platform:

    -   **Kaggle**: Upload the notebook and the dataset.
    -   **Colab**: Open the notebook, mount Google Drive, and upload the dataset.
    -   **SageMaker**: Upload the notebook and dataset to your SageMaker environment.


2.  Run the cells sequentially to train, evaluate, and visualize results.

Results
-------

-   **Baseline Accuracy**: The baseline model achieved a test accuracy of approximately 96.8%.


-   **Final Model Performance**:
    -   Training Accuracy: 98.01%
    -   Test Accuracy: 97.28%
    -   AUC-ROC Score: 0.9921

The final implementation improved upon the baseline through enhanced regularization techniques and better data preprocessing.

Conclusion
----------

This project demonstrates the effectiveness of deep learning models, particularly EfficientNet-B7, in detecting lung cancer from CT images. By improving sensitivity and reducing false positives, this solution has significant potential for real-world clinical applications.

References
----------

-   Dataset: [Ensemble Learning on LIDC Dataset](https://www.kaggle.com/datasets/mahounanpericles/ensemble-learning-on-lidc-dataset)
-   Repository: [GitHub](https://github.com/Pericles001/lungcancerdetectiondl)
Brain Tumor Classification using EfficientNet V2S

Overview:
This project focuses on the classification of brain tumors into four categories: glioma, meningioma, pituitary, and no tumor. Leveraging the power of deep learning, we employ EfficientNet V2S, a state-of-the-art convolutional neural network architecture, to achieve high accuracy in identifying and categorizing brain tumors from MRI scans.

Introduction:
Brain tumor classification is a critical task in medical imaging, aiding in the diagnosis and treatment planning for patients. Accurate classification can significantly impact patient outcomes. This project utilizes EfficientNet V2S for its balance of performance and efficiency, providing a robust solution for brain tumor classification.

Dataset:
The dataset used in this project consists of MRI scans labeled into four categories:
->Glioma
->Meningioma
->Pituitary
->No Tumor
The dataset is preprocessed to ensure uniformity in image dimensions and quality. Data augmentation techniques are applied to enhance the diversity of the training set and improve model generalization.

Model Architecture:
EfficientNet V2S is a highly efficient convolutional neural network architecture that scales depth, width, and resolution to optimize both performance and computational efficiency.
Key features include:
->Compound scaling: Simultaneously scales network depth, width, and resolution.
->Improved training speed: Faster training times with higher accuracy.
->Enhanced regularization: Techniques like stochastic depth and better augmentation strategies.
The architecture has been fine-tuned for this specific classification task, leveraging transfer learning from pre-trained weights.

Results:
The model achieves the following performance metrics on the test set:
->Accuracy: 98.95%
->Precision: 99%
->Recall: 98.80%

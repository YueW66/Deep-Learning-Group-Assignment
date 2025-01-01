**Brain Tumor Classification Using Convolutional Neural Networks (CNNs)**

This project focuses on classifying brain tumor MRI images into four categories: glioma, meningioma, pituitary tumor, and no tumor. Using Convolutional Neural Networks (CNNs), we implemented and improved models to tackle this multi-class classification problem.


*Key Features*
- Baseline CNN Model: Developed a simple CNN to establish a performance benchmark.
- Improved Model: Integrated techniques like SMOTE (Synthetic Minority Oversampling Technique) and focal loss to address class imbalances and enhance classification accuracy.
- Hyperparameter Tuning: Leveraged Optuna, an automated optimization library, to determine the best hyperparameter configuration for the CNN model.
- Performance: Achieved an accuracy of 88.71%, significantly improving over the baseline model.


*Dataset*
- The project utilized a publicly available MRI dataset, with images preprocessed to grayscale and a resolution of 30x30 pixels. Challenges included class imbalance and mislabeled samples.
- Training dataset: https://drive.google.com/drive/folders/1HqZPNfp8YoHn_-lLIFTOC4Zj8NeJ2x67?usp=sharing
- Testing dataset: https://drive.google.com/drive/folders/1gG7ZOPfwltTEGG2SPlCTcayvXwTJYBjJ?usp=sharing


*Tools and Techniques*
- Programming: Python (TensorFlow, Keras)
- Optimization: Optuna for hyperparameter tuning
- Addressing Imbalance: SMOTE and focal loss
- Transfer Learning: Explored pre-trained models like VGG16, ResNet50, and DenseNet121 for comparison.

  
*Results*
- Validation accuracy improved from 75.29% (baseline) to 88.71% (improved model).
- Enhanced precision, recall, and F1-scores for all classes, especially for minority classes like glioma and meningioma.

  
This project earned 10/10 in the university evaluation.

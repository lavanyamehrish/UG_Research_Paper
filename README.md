Transfer Learning for Nanomaterial Classification Using SEM Images
Abstract

Nanomaterials play a significant role in modern manufacturing industries by enhancing material strength, weight efficiency, and surface properties such as corrosion resistance and durability. Accurate classification of nanomaterials from Scanning Electron Microscope (SEM) images is essential for research and industrial applications. This project applies transfer learning techniques to classify nanomaterials using SEM image datasets and presents a comparative study between two pretrained convolutional neural network architectures: VGG16 and ResNet50.

Methodology

Pretrained models (VGG16 and ResNet50) were fine-tuned on a labeled SEM image dataset. The final classification layers were modified to suit the nanomaterial categories. Model performance was evaluated using standard metrics including accuracy, precision, recall, and F1-score.

Results

Both models achieved strong classification performance. VGG16 outperformed ResNet50 in terms of validation accuracy and overall consistency, demonstrating its effectiveness for SEM-based nanomaterial classification. The use of transfer learning significantly reduced training time while maintaining high accuracy.

Technologies Used

Python

TensorFlow / Keras

NumPy

Scikit-learn

Matplotlib

Dataset Link: https://drive.google.com/drive/folders/1WhoVEiGNEvVrxyg8qg-9xZBfZ7comTyb?usp=sharing

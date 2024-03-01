# concrete-craked-classification

# Dataset Overview
The dataset with all the images used in this project was downloaded from Mendeley.
Source: https://data.mendeley.com/datasets/5y9wdsg2zt/2

Content: It consist of two main classes (positive and negative). The positive mean the image of concrete surface with craks while negative mean the image of concrete without crakcs.

Size: The dataset contains a total of 4000] images, with 2 clases (positive and negative).

Image Characteristics: Images are captured under different lighting conditions, angles, and perspectives to simulate real-world scenarios.

# Description of the project
The "Concrete Crack Classification" dataset is a collection of images representing concrete surfaces with and without cracks. Cracks in concrete structures can indicate potential structural weaknesses, and early detection is crucial for maintenance and safety purposes. This dataset aims to facilitate the development and evaluation of machine learning models, particularly Convolutional Neural Networks (CNNs), for automated crack detection in concrete surfaces.

# Objective
The objective of this project is to develop a CNN-based classification model capable of accurately identifying cracks in concrete surfaces. By leveraging deep learning techniques, we aim to achieve high precision and recall in crack detection, enabling early detection and preventive maintenance strategies for concrete structures.

# Proposed Methodology
Data Preprocessing: Images undergo preprocessing steps such as resizing, normalization, and augmentation to enhance model robustness and generalization.

Model Architecture: A CNN architecture is designed, comprising convolutional layers, pooling layers, and fully connected layers.

![Model Architecture Flow](https://github.com/aimandnsh/concrete-craked-classification/assets/150990001/2f8d497a-a325-4e15-88a8-1a301d4b7d69)

![Model Architecture](https://github.com/aimandnsh/concrete-craked-classification/assets/150990001/62381dec-6383-4ca8-aafc-f872c3d9350a)

Training: The model is trained using the labeled dataset, optimizing for classification accuracy and minimizing loss through techniques Adam optimization.\

Evaluation: The trained model is evaluated on the validation set to assess performance metrics such as accuracy, precision, recall, and F1-score.

Testing: Finally, the model is tested on the unseen test set to evaluate its generalization capability and real-world performance.

# Result
![Accuracy](https://github.com/aimandnsh/concrete-craked-classification/assets/150990001/42f2d187-3f66-4ea8-8759-b568c0d8ba1a)

![Loss](https://github.com/aimandnsh/concrete-craked-classification/assets/150990001/a810b0d0-d7f7-4859-92de-a00953fa454d)

Testing model can refer in CrackDetection.ipynb file. The model tested with two outsource image which are for positive and negative.

# Save Model Deep Learning
https://drive.google.com/drive/folders/14p5SGon7I7Z8yKNnoGt7qJrddyXfKYBj?usp=sharing

you can download saved model from this link since the file bigger and can not upload. So, I attached the link to download the model.


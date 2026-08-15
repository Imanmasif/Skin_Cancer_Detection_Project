# Methodology

## Task

The project addressed binary skin lesion classification using deep learning and transfer learning. The experimental work focused on distinguishing melanoma from benign/non-melanoma cases.

## Data preparation

According to the original project report, the dataset was formed by combining publicly available skin cancer datasets. The existing notebooks include image loading, preprocessing and data augmentation steps. Because some image-count statements in the report are inconsistent, this document does not repeat a class distribution that cannot be verified from the surviving project files.

## Models explored

The project compared three transfer-learning architectures:

- MobileNetV2
- VGG16
- InceptionV3

An additional fine-tuning stage was applied to MobileNetV2 in the original project work.

The notebooks use TensorFlow/Keras for model development. The archived notebook environment records TensorFlow 2.7.0 for the updated MobileNetV2 implementation.

## Training and evaluation

The original work used model training and validation to compare the selected architectures. Accuracy and loss values were recorded as part of the experimental comparison. Fine-tuning was explored to improve the MobileNetV2 result.

For exact implementation details, the notebooks in the repository should be treated as the primary record of the code used in the original experiments.

## Mobile application prototype

The original project also included a prototype Android application. The project report describes the use of Android Studio, Firebase Cloud Storage and TensorFlow Lite for model integration. The full Android application source is not currently included in this repository, so this documentation does not imply that the application can be rebuilt directly from the files published here.

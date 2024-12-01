# Intel_image_classification
This project aims to classify natural scenes into six categories by applying Convolutional Neural Network (CNN), transfer learning, and experiment tracking. The dataset used is the [Intel Image Classification dataset]( https://www.kaggle.com/datasets/puneet6060/intel-image-classification?resource=download), which includes 25k+ images of various types of landscapes and environments.

## Features
* Data Preprocessing: Includes resizing, normalization, and data augmentation to improve model performance.

* CNN Architecture: Applies transfering on the pretrained model, ResNet18.

* Experiment Tracking: Using TensorBoard to track training loss and accuracy.

## Dataset
The dataset is sourced from Intel Image Classification Dataset. It contains the following categories:

* Buildings
* Forest
* Glacier
* Mountain
* Sea
* Street

## Results:
* Accuracy: Achieved an accuracy of 90% on the test set after 5 training epochs (Only trained for 5 epochs due to hardware limitations).

* Loss and accuracy plot:
  
  <img width="800" alt="Screenshot 2024-11-26 at 13 36 58" src="https://github.com/user-attachments/assets/3f14f23c-acdc-4dc6-9f3a-3fb9754c5363">
  
  <img width="800" alt="Screenshot 2024-11-26 at 13 37 16" src="https://github.com/user-attachments/assets/f6364b4e-d370-4403-91da-9990099bee9e">

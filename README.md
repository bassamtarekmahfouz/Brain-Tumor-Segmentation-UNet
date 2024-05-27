# Project-Semantic-Segmentation-for-Brain Tumor

**In this notebook, I implement an image segmentation model on a brain tumor image dataset: Kaggle Semantic Segmentation**

Semantic segmentation for brain tumors is a deep learning project that aims to identify and classify tumors in MRI images of the brain. This project involves using advanced image segmentation techniques to partition the image into different regions based on specific characteristics.

The notebook includes data preprocessing, model training, and evaluation steps. Below is a detailed explanation of the content and how to use it.

# Contents

**Import Libraries**
Necessary libraries such as numpy, pandas, matplotlib, cv2, and PyTorch are imported.

**Data Preparation**
Load and preprocess the dataset for training and validation. This includes loading images and their corresponding masks.

**Custom Dataset Class**
A custom dataset class, CustomDataset_General, is defined to handle image and mask loading.

**Transformations**
Define transformations to be applied to the images and masks, such as resizing, normalization, and converting to tensors.

**Model Definition** 
Determine the structure of the Attention U-Net semantic segmentation model

**Training the Model**
Train the model using the training dataset. The training loop, loss calculation, and optimization steps are included.

**Evaluating the Model**
Evaluate the model on the validation dataset to check its performance.

**Inference**
Perform inference on new images to see the model's segmentation results.


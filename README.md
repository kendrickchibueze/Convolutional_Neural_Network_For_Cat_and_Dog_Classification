# Convolutional_Neural_Network_For_Cat_and_Dog_Classification

## Project Overview
This project builds a deep learning model to classify images of cats and dogs using Convolutional Neural Networks (CNNs). The dataset contains labeled images of both animals, and the goal is to train a model that can accurately distinguish between them.

## Key Steps

1. **Data Exploration and Analysis**: 
   - Analyzed the dimensions of images in the training set to understand their consistency.
   - Plotted the distributions of image widths and heights for both cats and dogs.

2. **Dataset Split**: 
   - The dataset was split into training and validation sets, with 20% allocated for validation.
   - Images were resized to 150x150 pixels and normalized to a [0, 1] range.

3. **Class Distribution**: 
   - Ensured the training, validation, and test sets were balanced between cats and dogs.

4. **Image Augmentation**: 
   - Applied augmentation techniques (rotation, shifting, flipping, zoom) to enhance the model’s generalization ability and prevent overfitting.

5. **Color Channel Analysis**: 
   - Analyzed the mean and standard deviation of pixel values for each color channel (RGB) to assess potential color-based differences between cats and dogs.

6. **Model Training**: 
   - Trained a CNN model for 25 epochs using the preprocessed dataset.
   - Validated the model’s performance after each epoch to track its learning progress.

## Results
The model was successfully trained to classify images of cats and dogs, demonstrating the effectiveness of data augmentation, image preprocessing, and a balanced dataset in training a robust CNN model for binary classification.

## Conclusion
This project illustrates the process of using deep learning techniques for image classification, focusing on cats vs dogs, and showcases how data exploration, augmentation, and model validation contribute to building an effective machine learning model.

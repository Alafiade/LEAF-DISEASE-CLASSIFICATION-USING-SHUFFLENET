# LEAF-DISEASE-CLASSIFICATION-USING-SHUFFLENET

# Project Overview
This project aims to classify rice leaf diseases using a deep learning model.The dataset, sourced from Kaggle, consists of images categorized into three distinct disease classes.

# Methodology
1. Data Acquisition:
   * The 'Rice Leaf Diseases' dataset was downloaded from kaggle.
   * The dataste was then imported into my Google Colab notebook for further processing.
2. Data Preprocessing:
   * The images were preprocessed to ensure consistence in size and format.
   * Different Data augmentation techniques were applied to increase the diversity of the training data.
3. Model Architecture:
   * A pretrained ShuffleNet V2 model was utilized to train the dataset.
4. Training Process;
   * The model wwas trained using the Stochastic Gradient Descent optimizer with a learning rate of 0.001 and a weight decay of 0.01.
   * A  StepLR scheduler was employed to adjust the learning rate every 5 epochs.
   * A dropout layer with a probability of 50% was included to prevent overfitting.
   * The model was trained on the preprocessed dataset, and the training and validation loss and accuracy were monitored.
  
# Results
The model achieved the following results:
* Training Loss: 0.027
* Training Accuracy: 1.0000
* Validation Loss: 0.1814
* Validation Accuracy: 0.9444
The model demonstrated strong performance on the validation set, indicating good generalization ability and minimal overfitting.

# Visulization
A visualization of the training process, including the evolution of training and validation loss and accuracy was created using Matplotlib. This visualization provides isights into the models learning behavior.

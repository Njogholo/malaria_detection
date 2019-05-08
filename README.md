# Malaria Detection
Malaria detection using the FastAI deep learning library

[FastAI](https://www.fast.ai/) basically democratised deep learning. Anyone can do it!

**Workflow:**
* Load the data into Google Colab (GPU speeds up analysis)
* Data Augmentation and Preparation
* Use pre-trained ResNet34 to create a CNN Learner that classifies the images as either *Parasitized* or *Uninfected*
* Achieved **97% accuracy** after just 5 epochs
* Evaluate how the model performed using a confusion matrix and other tools

Data is publicly available in [Kaggle](https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria)

# Malaria-Detection-with-Deep-Learning
## Introduction:

Malaria caused by the Plasmodium parasites, is a blood disorder, which is transmitted through the bite of a woman Anopheles mosquito. With almost 240 million cases mentioned each year, the sickness puts nearly forty percentage of the global populace at danger. Macroscopic usually take a look at thick and thin blood smears to identify a disease or a cause and figure it out what weakens them. However, the accuracy depends upon smear quality and awareness in classifying and counting parasite and non-parasite cells. Manual evaluation, which is the gold standard for diagnosis requires various steps to be performed. Moreover, this process leads to overdue and misguided analysis, even when it comes to the hands of expertise.

## Task:

In our project, we aim at building a robust, minimized reliance of humans, sensitive model for automated analysis of Malaria. A category of deep learning models, namely Convolutional Neural Networks, helps with end-to-cease attribute extraction and categorization of parasitic and non-parasitic cells.

## Dataset:

This Dataset is taken from the official NIH Website: https://ceb.nlm.nih.gov/repositories/malaria-datasets/. The dataset has a total of 27,558 images. The dataset has a variety of Parasite and Non-Parasite pictures of blood samples.

## Approach:
1.	Extracted data from the website.
2.	Used ImageDataGenerator to resize, rotate and scale the image.
3.	Created a model using Convolutional Neural Network
4.	Performed image augmentation using image_gen.flow_from_directory
5.	Trained the model using CNN. Set early stop to increase efficiency.
6.	Evaluated the model with confusion matrix and classification report.
7.	Accuracy of 94% is obtained.
8.	Deployed the model in Streamlit.

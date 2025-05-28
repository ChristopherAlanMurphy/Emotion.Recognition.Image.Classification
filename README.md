# Emotion.Recognition.Image.Classification

# Project Overview:
The primary goal in this analysis is to design a model that accurately classifies images into its
corresponding emotion class. Through the integration of convolutional neural networks (CNNs)
and preprocessing techniques, this study aims to address issues regarding imbalanced data sets,
the variability of facial emotions, and the generalization of emotion recognition.

# Team Members:
John Zumel, Nishad Vinayek, Christopher Murphy

# Reason for Selecting this Topic:
The project offered an opportunity to first evaluate the performance of transfer learning when adapting existing pre-trained neural networks to new images.  Next, fine-tuning techniques were used to add additional layers to the pretrained neural network to drive model accuracy improvements when compared to transfer learning outcomes. 

# Background Information:
Preliminary models were built using the following pretrained neural network models available in the Keras framework: VGG16, VGG19, ResNet50, and InceptionV3.  InceptionV3 was chosen as the subject of the report to measure the affect of transfer learning and fine-tuning on a single pretrained model and image data set. 

# Questions We Hope to Answer with the Data:
1.) Does the base model generalize well to a new facial emotion image data set leveraging basic transfer learning techniques?

2.) How does model accuracy improve with the addition of new layers using fine-tuning techniques?

3.) What data pre-preparation steps should be taken to handle class imbalances?

# Description of Data Sources:
The FER-2013 (Facial Expression Recognition 2013) data set is a publicly available dataset
introduced during the ICML 2013 Challenges in Representation Learning. It was found and
downloaded from Kaggle. This data set contains a total of 35,887 images, each at 48x48 pixels.
These images are organized in separate folders each representing one of the differing seven
emotion classes: (0 = Anger, 1 = Disgust, 2 = Fear, 3 = Happiness, 4 = Sadness, 5 = Surprise,
and 6 = Neutral)

# Technologies Used:
Google Colab Notebook, Google Drive, Python and Libraries: Tensorflow, Sklearn

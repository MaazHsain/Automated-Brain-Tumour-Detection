# Automated-Brain-Tumour-Detection

This repository is based on Automated Brain Tumour Detection. It contains the codes which were implemented during this project. This project was carried on Kaggle platform due to it providing the necessary tools and powerful GPUs and CPUs, which were important to run the model training efficiently. The dataset and model files are too huge to put up on github, thus, I have uploaded them on google drive. You can request access to them by contacting me through my email.

The 'final_prototype.ipynb' is my overall system implemented during this project. It showcases both the classification and segmentation stages, the integration of these two stages, and lastly the results of the overall system in detecting and segmenting the MRI scans. The system is capable of detecting both a single MRI image and multiple MRI images, as shown in this ipynb file. This file integrates the codes from 'classification_pipeline.ipynb' and 'final_results_of_segmentaton.ipynb'. 

The 'final_results_of_segmentaton.ipynb' file shows the segmentation pipeline and how the visual results were generated. The 'classification_pipeline.ipynb' file consists of code used to train and evaluate the three CNN models. It also shows the classification pipeline in the end.

The files under 'Data Preparation' show the code for data structuring, image preprocessing for CNN, and creation of segmentation masks for U-Net model.  The 'segmentation.ipynb' file consists of code used to train and evaluate the U-Net models, one over 10 epochs and the other over 202 epochs. The results are shown at the end of the file. The 'vgg-16.ipynb' file shows the implementation of vgg16 in my project. It consists of the training and fine-tuning process, along with the evaluation. 

# InceptionV3
Video categorization using the InceptionV3 library

## Index
1. [What is InceptionV3](#what-si-inceptionv3)
2. [How to run the code](#how-to-run-the-code)

## What is InceptionV3
IncpetionV3 is a Neural Network which permise to classify a video with a model created after a traning or using a pre-trained model with weights already calculated

## How to run the code
For simplicity and to avoid collision with different versions of libraries, run the code on the Google Colab platform.
1. First, upload the dataset you want to use on Google Drive and create two subfolders, one for the training-set and one for the test-set.
2. Upload the .ipynb code to Google Colab
3. Both in the training-set folders and in the test-set folder, you will need to create two other subfolders containing the 2 categories contained in the dataset.
4. Always on google drive, create folders that must contain all the frames extracted from the videos, you need to create subfolders to distinguish the frames extracted from the videos in the training-set and in the test-set, naturally also within them there must be the subdivision by video categories
5. Run the training code and test code twice, once for each category
6. In the paths "path1" and "path2" insert respectively the paths of the folders containing the frames of the training-set and the frames of the test-set. I recommend, reversing the paths would lead to training on a 30% and testing on a 70%
7. Execute each section of the code one by one
8. See the results

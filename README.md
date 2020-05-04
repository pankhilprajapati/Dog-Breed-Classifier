[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Keras Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"

# Udacity's Data Scientist Nanodegree Capstone Project: Dog Breed Classifier
## Project Overview

Udacity Capstone project in the Data Scientist Nanodegree! In this project, Explain how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images.  Given an image of a dog, your algorithm will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  

![Sample Output][image1]

Along with exploring state-of-the-art CNN models for classification Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.

* [Step 0](#step0): Import Datasets
* [Step 1](#step1): Detect Humans
* [Step 2](#step2): Detect Dogs
* [Step 3](#step3): Create a CNN to Classify Dog Breeds (from Scratch)
* [Step 4](#step4): Use a CNN to Classify Dog Breeds (using Transfer Learning)
* [Step 5](#step5): Create a CNN to Classify Dog Breeds (using Transfer Learning)
* [Step 6](#step6): Write your Algorithm
* [Step 7](#step7): Test Your Algorithm

## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
```	
git clone https://github.com/udacity/dog-project.git
cd dog-project
```


2. Download the [dog dataset]()

3. Download the [human dataset]().

4. Donwload the [VGG-16 bottleneck features]()

5. Libraries
   ```
   Keras
   OpenCV
   Matplotlib
   Numpy
   Tensorflow
   tqdm
   
   ```
6. File descriptions
   ```
   dog_app.ipynb: Jupyter notebook containing the main algorithm, findings and results.
   dog_app.html: A copy of dog_app.ipynb in html format.
   Haarcascades folder: contain the opencv haarcascade XML file for face detection.
   images: few images for the testing prediction algorithm.
   
   
   ```
7. Findings
    
   - The model achieved a test accuracy of 83.4928%.
   - Data is not augmented some of the breeds have similar colors and shapes but differ in size, so some of the pic where unclassified
   - The model could use some improvements on its ability to classify pictures with data augmentation and using the other trained model 

8. Open the notebook.
```
jupyter notebook dog_app.ipynb
```
## Conclusion
  
  Detailed Discussion and Result of the project are in the article in medium [Dog Breed classifier](https://medium.com/@puruprajapati8/dog-breed-classifier-using-transfer-learning-in-cnn-d09606432ffe?sk=122b66678ccd5f13e027a0eb1e398529)



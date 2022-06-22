# MNIST Digit Recognition with Non-Linear Classification

## **Introduction**
The goal of this project is to design some Non-Linear Classifiers from scratch to use for classifying/recognizing digits "0,1,2,...,9". 

<U>We will be implementing the following algorithms</u>:
1. Linear Regression with Closed Form Solution.
2. Support Vector Machine.
3. Multinomial (Softmax) Regression and Gradient Descent.
4. Classification Using Manually Crafted Features: 
   - Dimentionality Reduction (PCA).
   - Cubic Features
5. Kernel Methods:
   - Polynomial Kernel
   - RBF Kernel
       


## **About Data**
The MNIST database contains binary images of handwritten digits commonly used to train image processing systems. The digits were collected from among Census Bureau employees and high school students. The database contains 60,000 training digits and 10,000 testing digits, all of which have been size-normalized and centered in a fixed-size image of 28 × 28 pixels. Many methods have been tested with this dataset and in this project, you will get a chance to experiment with the task of classifying these images into the correct digit using some of the methods you have learned so far.


<p align="center">
  <img src="https://courses.edx.org/assets/courseware/v1/03f49ce9ab37fa92d84b0c9e70542014/asset-v1:MITx+6.86x+2T2022+type@asset+block/images_6.png" width="100" />
  <img src="https://courses.edx.org/assets/courseware/v1/e7123412da031f62e082afb10bdfa655/asset-v1:MITx+6.86x+2T2022+type@asset+block/images_8.png" width="100" /> 
  <img src="https://courses.edx.org/assets/courseware/v1/b56e40dfe8c00d6c9b54956f21e04f92/asset-v1:MITx+6.86x+2T2022+type@asset+block/images_6-2.png" width="100" />
  <img src="https://courses.edx.org/assets/courseware/v1/280748cc6f7447b43db835bf0c1700d8/asset-v1:MITx+6.86x+2T2022+type@asset+block/images_x.png" width="100" />
</p>


## **Setup Details:**

For this project we will be using Python 3 with some additional libraries such as:
- NumPy
- Matplotlib
- Scikit-Learn

<u>Files in this project</u>:
- **linear_regression.py** where we will implement linear regression.
- **svm.py** where we will implement support vector machine.
- **softmax.py** where we will implement multinomial regression.
- **features.py** where we will implement principal component analysis (PCA) dimensionality reduction.
- **kernel.py** where we will implement polynomial and Gaussian RBF kernels.
- **main.py** where we will use the code you write for this part of the project.


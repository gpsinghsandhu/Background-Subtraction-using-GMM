Background-Subtraction-using-GMM
================================
REQUIREMENTS:
  + Any C++ compiler (originally developed in visual studio, thus remove conio.h and _getch to be able work on other enviroment)
  + OpenCV 2.2 or above (originally developed on OpenCV 2.3.1)

This project is the C++ implementation of Background Subtraction using adaptive GMM models as discussed by Zoran Zivkovic in his paper "Improved Adaptive Gaussian Mixture Model for Background Subtraction".

This project was developed as a part of learning about the computer vision and thus gives (though very basic) an efficient and accurate implementation of the above mentioned algorithm.
It uses OpenCV just for the data acquisition and preprocessing and its 'Mat' object for susequent processing. Following which is an implementation for the GMM models as discussed in the paper.

The testing data has also been provided with the project. It is a part of the PETS 2009 dataset.

Note: This project was developed on the basis of my undrstanding of the paper and thus must not considered an exact implementation of the project.

Check out the result video - http://youtu.be/QwmX3U78K6A

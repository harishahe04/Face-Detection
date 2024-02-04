# Face-Detection

Face Detection is widely used in various applications for detecting human faces in a captured image. This repository deals with 3 widely used face detecting models. 


## Topics Covered

- HAAR Cascade Classifer using OpenCV
- Histogram of Oriented Gradients (HOG) with Dlib and Linear SVM
- Dlib with CNN
- Face Detection from WebCam

## Installations 

OpenCV and Dlib C++ Toolkit for Python is required to successfully run these models. 
```
pip install opencv-python
pip install dlib
```

Installation of Dlib can be unsuccessful with errors. If error occurs, then one call install it manually by following the steps mentioned in this installation guide: https://medium.com/@vinuvish/install-dlib-python-windows-77e9349e6cfc

## Tutorials

The basic intuition behind the classifiers can be understood from the below links:
##### HAAR Cascade

https://towardsdatascience.com/face-detection-with-haar-cascade-727f68dafd08
##### HOG Feature Extractor

https://www.analyticsvidhya.com/blog/2019/09/feature-engineering-images-introduction-hog-feature-descriptor/

##### Dlib with CNN

Dlib with CNN applied pre-trained Convolutional Neural Networks (CNN) for face detection trained on millions of image datasets. Detailed explanation of CNN can be found from below Stanford lecture notes:

https://cs231n.github.io/convolutional-networks/












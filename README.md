Lab Title 

Image Segmentation Using Thresholding and Clustering Techniques

Objectives of the Lab 

The objectives of this lab task are:

To understand the concept of image segmentation in digital image processing.

To apply global thresholding for separating foreground and background.

To implement local and adaptive thresholding techniques.

To perform K-means clustering based image segmentation.

To understand Mean Shift segmentation.

To visually compare the results of different segmentation methods.

To analyze the advantages and limitations of each technique.

To gain practical experience using Python and OpenCV.

Software and Tools Used 

Google Colab / Jupyter Notebook

Python 3

OpenCV (cv2)

NumPy

Matplotlib

Theory (Easy & Short) 

Image segmentation is the process of dividing an image into different regions so that meaningful information can be extracted easily. Each region contains pixels that have similar characteristics such as intensity or color.

Segmentation is an important step in image analysis and is widely used in medical imaging, object detection, and computer vision applications.

Techniques Used in This Lab 1. Global Thresholding 

A single threshold value is applied to the whole image to separate objects from the background.

2. Local Thresholding 

Different threshold values are applied to different regions of the image based on local neighborhood information.

3. Adaptive Thresholding 

Threshold value changes automatically according to illumination conditions of the image.

4. K-Means Segmentation 

Pixels are grouped into k clusters based on similarity. Different values of k give different segmentation results.

5. Mean Shift Segmentation 

A region-based method that groups pixels based on density and color similarity.

Procedure / Steps 

Load the input image.

Convert the image to grayscale.

Apply global thresholding.

Apply local and adaptive thresholding.

Perform K-means clustering with different k values.

Apply Mean Shift segmentation.

Display and compare the results.

Results and Observations 

Global thresholding is fast but sensitive to lighting.

Adaptive thresholding performs better under uneven lighting.

K-means provides clear segmentation for color images.

Mean Shift gives smooth and natural segmentation results.

Advantages 

Simple implementation using OpenCV.

Useful for object extraction.

Helps in understanding different segmentation strategies.

Limitations 

Thresholding methods are affected by noise.

K-means requires manual selection of cluster value.

Mean Shift is computationally expensive.

Applications 

Medical image analysis

Object detection

Face recognition

Satellite image processing

Autonomous vehicles

Conclusion 

In this lab, different image segmentation techniques were implemented successfully. Each technique showed different performance depending on image conditions. The lab provided a clear understanding of how segmentation methods work and where they are best applied.


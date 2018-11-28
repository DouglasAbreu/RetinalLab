# RetinalLab
New version: 28/11/2018

OBS.: This application was developed with MatLab 2017b. To install and use, you must install MatLab Runtime compatible with version R2017b, available [here](https://www.mathworks.com/products/compiler/matlab-runtime.html).

The Retinal Lab is a graphical interface that allows the application of image processing methods in retinal fundus images, verifying the effect of each method, based on an order of application for the segmentation of the vessels to aid in the detection of retinopathies.

RGB separation, green channel extraction, Hough Circular Transform, CLAHE, and complement operation composes the preprocessing phase. The 2D Gabor Wavelet, the Closing Operation and Morphological Reconstruction composes the segmentation phase.

The user can choose between segmentation only or performance evaluation, which will require a selected image manually marked by a specialist. At the end, the performance evaluation aims to validate the proposed method, through the calculations of specificity, sensitivity and accuracy.

The interface also allows the user to edit some specific parameters in the Edit Parameters button.



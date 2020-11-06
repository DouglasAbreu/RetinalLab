# RetinalLab

If you use this work, please cite this article:
da Rocha, D.A., Barbosa, A.B.L., Guimarães, D.S. et al. An unsupervised approach to improve contrast and segmentation of blood vessels in retinal images using CLAHE, 2D Gabor wavelet, and morphological operations. Res. Biomed. Eng. 36, 67–75 (2020). https://doi.org/10.1007/s42600-019-00032-z
Also available in https://github.com/GEPSIN/RetinalLab

New version: 21/07/2019

OBS.: This application was developed with MatLab 2017a. To install and use, you must install MatLab Runtime compatible with release R2017a (9.2 version), available [here](https://www.mathworks.com/products/compiler/matlab-runtime.html).

The Retinal Lab is a graphical interface that allows the application of image processing methods in retinal fundus images, verifying the effect of each method, based on an order of application for contrast enhancement and segmentation of the vessels.

RGB Separation, Green Channel Extraction, Complement Operation, Retina Edge Removal, CLAHE and Suppression of Vessels Background composes the preprocessing phase. The 2D Gabor Wavelet, the Closing Operation and Morphological Reconstruction composes the segmentation phase.

The user can choose between segmentation only or performance evaluation, which will require a selected image manually marked by a specialist. At the end, the performance evaluation aims to validate the proposed method, through the calculations of accuracy, specificity, sensitivity and balanced-accuracy.

The interface also allows the user to edit some specific parameters in the Edit Parameters button.

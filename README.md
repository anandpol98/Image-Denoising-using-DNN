# Image-Denoising-using-DNN


Traditional Image Denoising focused on extracting latent clean image from Noisy Images. This method denoises image using Residual Learning and Batch Normalization technique.

Residual Learning has following merits:
> Residual network explicitly learns a residual mapping for a few stacked layers. 
> With such a residual learning strategy, extremely deep CNN can be easily trained and improved accuracy has been achieved for image classification and object detection.


Batch Normalization has following merits:
> It helps to deal with Internal Covariate Shift problem.
> Provides fast training and better performance.


3 .ipynb files are attached.
1) Denoising Images in which Noise of Level 15 is added.
2) Denoising Images in which Noise of Level 25 is added.
3) Denoising Images in which Noise of Level 50 is added.



Please find attached some images after denoising using DnCNN model. 


Train400.zip contains 400 Training Images.
Model is trained for over 50 epochs.

Test.zip has 2 dataset for Testing
1) BSD68 - which has 68 images.
2) Set12 - popular 12 images used in Image processing. 


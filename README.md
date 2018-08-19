# U-NET Convolutional Network for Medical Image Segmentation 

The model is implemented according to the architecture present in the paper, as following:

![alt text](https://cdn-images-1.medium.com/max/1600/1*TXfEPqTbFBPCbXYh2bstlA.png)

The datased used was downloaded from the [ISBI Challenge](https://stackoverflow.com/questions/14494747/add-images-to-readme-md-on-github) website, which includes 30 images for the training set as their respective masks. The test set comprises 30 new images.

The images and masks are pre-processed in order to be ready for feeding the implemented model.
Since the dataset is of a small amount, data augmentation is used to implement a more accurate and reliable model.

The model is trained for 5 epochs, with 100 steps per epoch.

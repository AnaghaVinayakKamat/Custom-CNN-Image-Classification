# Customized Convolutional Neural Network (CNN) for Alpaca Image Classification:
In this project we will be proposing a modified version of Conv2D layer of a CNN to perform image classification for Alpaca animal. Our aim is to improve the performance of the algorithm by making it more flexible and adaptable in capturing features from imput data.

# Dataset:
2 folders containing one image of Alpaca and other folder with other animals is used. We will load the folders in the notebook and create a dataframe with them. 

# Preprocess Data:
For preprocessing the data we have converted the images from RGB to Gray scale and normalized them between 0 to 1. 

# Traditional vs Custom CNN:
The key difference between traditional and custom CNN is that, the proposed CNN dynamically uses a weight matrix and for each operation a locally positioned Kernel is used to calculate the weighted sum. 

**Refer the image below for a better understanding**
![alt text](https://github.com/AnaghaVinayakKamat/Custom-CNN-Image-Classification/blob/8c894c832376b490b36ee6ec228868fb13894c35/img/working.png)

# Outcome of the Experiment:
It seemed that the output results obtained from this model were very weak and would require a lot more improvisations. Plus, this model takes a lot more time than traditional CNN to give results. When tried using for multi-layered approach, it was not successful. As a result, this model is tested only on single layer CNN.


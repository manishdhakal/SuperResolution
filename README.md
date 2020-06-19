# SRGAN

### Keywords
    GAN, SRGAN, VGG19, Keras, Transfer Learning

### Overview
This is the code implemented in Keras API of python with GAN(Generative Adversial Network). In this program, we can upscale the pixel quality of the image from 25x25 to 100x100.

### Dataset
For this program, a dataset has been synthesized from given 3000 100x100 images by downscaling it to 25x25 from *create dataset.ipynb*. The link to the dataset can be found [here](https://drive.google.com/file/d/1aYM-TV1EpiHpmCBt2OfyCcde6k4EKWMD/view?usp=sharing).

### Background
The reference to the research paper for this program can be found [here](https://arxiv.org/pdf/1609.04802). GAN is a class of machine learning frameworks designed by Ian Goodfellow and his colleagues in 2014.

### Program
The file *main.ipynb* is used to train the model for initial step. Later on the file *retrain.ipynb* is used to train by updating the model from pretrained weights. The VGG19 model is used to extract features from the high resolution images while training.

### Parameters
The trained weights for some specific epochs can be found [here](https://drive.google.com/drive/folders/1v6Edo-bagGPPJ51_txVktGFZXWyHvert?usp=sharing)
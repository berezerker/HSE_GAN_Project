# HSE_GAN_Project

This project contains Jupyter notebook for implementation of training process for Pix2Pix and CycleGAN models.
For pix2pix this [article](https://machinelearningmastery.com/how-to-implement-pix2pix-gan-models-from-scratch-with-keras/) was used as in inspiration.
For CycleGAN we used the same idea with, but implemented differently, since Pix2Pix and CycleGAN take different inputs, Yet discriminator structure is the same.
Commentaries and outputs have been provided inside the notebook.

# Running the project
In order to run the project, please place the dataset from our course inside the repository folder, so that jupyter notebook and folder "facades" is in the same folder.

# Drawbacks
Unfortunately, I didn't have enough resources to train CycleGAN long enough, So I outputted the results of the models after 1 epoch, contrary to Pix2Pix, where I managed to train 100 epochs overnight.(For reference, 1 epoch for cycleGAN was training for 1 hour on my computer). Thank you for understanding.

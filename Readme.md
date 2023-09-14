# USING CONVULUTIONAL AUTOENCODER ARCHITECTURE AS AN APPLICATION FOR DENOISING IMAGES

# CONVULUTIONAL AUTO ENCODER

Convolutional autoencoders (CAEs) are unsupervised dimensionality reduction models composed by convolutional layers capable of creating compressed image representations

# DATASET FOR THE PROJECT 

For this particular project, I am using the Ciphar 100, which is already available with labels in keras framework inside the datasets module

# METHODLOGY

* Noisify the dataset by adding gaussian noise to the images inside ciphar 100 dataset
* Design a convulutional auto-encoder architecture that takes in a noisy image as input and gives back a denoised image.

# TRAINING THE NETWORK

* To train the network, we supply the noisy images as input to the system.
* The output produced by the autoencoder is compared with the denoisy image with an appropriate loss function.

# CelebA-Gan
This code is for google colab notebook.


# what is GAN?

  GAN stands for Generative Adversarial Network. GAN is a deep neural network that consists of two neural networks, the generator network, and the discriminator network. The generator network is trained to produce fake images and the discriminator is trained to distinguish between fake images and real images. They interact with each other so that the generator can produce real-like fake images and the discriminator can distinguish whether the image is fake or real.

  # How GAN works
  
  <img src="https://developers.google.com/static/machine-learning/gan/images/gan_diagram.svg" width = "600" height="400">
  
  1. Latent space (array of random values) into Generator
  2. Generator makes fake images
  3. label fake images as 0 and real images as 1
  4. Goal of generator = deceive discriminator by making better fake images that looks like real(i.e. discriminator output for fake image = 1)
  
     Goal of discriminator = discriminate all images correctly
     
    
  


# Check-point link

https://drive.google.com/drive/folders/1FqQLGNPzLViKRUZcfpdqNnbMQb9_2EKA?usp=sharing


# Progress

![15 (1)](https://user-images.githubusercontent.com/111392592/185004297-8a50027e-82dc-4a1f-a917-813854ab81a3.png)


# Reference links
  #Data
  
    https://www.kaggle.com/datasets/jessicali9530/celeba-dataset
    
  #Code
  
    https://keras.io/examples/generative/dcgan_overriding_train_step/
    https://www.udemy.com/course/deep-learning-tensorflow-2/
    https://machinelearningmastery.com/how-to-train-a-progressive-growing-gan-in-keras-for-synthesizing-faces/
    
  #Images
  
    https://developers.google.com/machine-learning/gan/gan_structure

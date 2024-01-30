# Audio Augmentation using Generative Adversarial Networks for speech emotion datasets

- Built Deep Convolutional GAN in the PyTorch framework to generate new spectrograms to solve data imbalances in speech emotion datasets

- Converted the audio dataset (.wav format) into spectrograms via Short Term Fourier Transform and classified the newly generated spectrograms using transfer learning of the ResNet50 and VCG16 models.

- Obtained validation accuracies of 73.9\% and 79.3\% on the original and augmented spectrograms, respectively, with the half-freeze VGG-16 network.
  

![Screenshot (60)](https://github.com/MNikhilBharath/Audio_Augmentation-using-GANs/assets/67653205/87843c5a-27e3-41e1-a941-200814b68a93)
 

![Screenshot (64)](https://github.com/MNikhilBharath/Audio_Augmentation-using-GANs/assets/67653205/dbe89e32-a183-447c-a631-fb23e404878c)


![Screenshot (66)](https://github.com/MNikhilBharath/Audio_Augmentation-using-GANs/assets/67653205/d3e5ecbb-9655-4b90-986c-25f3fea84243)


![Screenshot (67)](https://github.com/MNikhilBharath/Audio_Augmentation-using-GANs/assets/67653205/a4d90eff-3b15-46cd-bc01-49d54d2e8a30)

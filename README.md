# Audio Augmentation using Generative Adversarial Networks for speech emotion datasets

- Built Deep Convolutional GAN in the PyTorch framework to generate new audio logarithmic spectrograms to solve data inadequacy issues for training speech emotion datasets

- Converted the audio dataset (.wav format) into spectrograms via Short Term Fourier Transform and classified the newly generated spectrograms using transfer learning of the ResNet50 and VCG16 models.

- Obtained validation accuracies of 73.9\% and 79.3\% on the original and augmented spectrograms, respectively, with the half-freeze VGG-16 network.

# mnist-GANs

### Generative Adversarial Networks

These are one of the most interesting ideas in the field of Machine learning and Computer vision today. The architecture is like two models called the generator and discriminator are trained in an adversarial process. As the training progresses the generator becomes better at making images that lookk real and discriminator gets better at telling the fake ones from real ones. The progression reaches an equllibrium when discriminator can no longer distinguish fake images from real ones.

Here, I use the Fashion and Handwritten-digits MNIST datasets to train the DCGAN (Deep Convolutional Generative Adversarial Networks) models to generate fake samples that look similar to the samples in the dataset.

### Results

- Generated samples for Fashion MNIST as the training progresses,
![](https://github.com/tusharparimi/mnist-GANs/blob/main/fashion_dcgan.gif)

- Generated samples for handwritten digits MNIST as the training progresses,
![](https://github.com/tusharparimi/mnist-GANs/blob/main/digits_dcgan.gif)

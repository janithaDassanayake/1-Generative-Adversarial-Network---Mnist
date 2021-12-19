# **Generative Adversarial Nets (GANs)**

---
## There are two major components within GANs: the generator and the discriminator

**Discriminator** network and is usually a convolutional neural network (since GANs are mainly used for image tasks) which assigns a probability that the image is real.

The **generative network**, and is also typically a convolutional neural network (with deconvolution layers). This network takes some noise vector and outputs an image. When training the generative network, it learns which areas of the image to improve/change so that the discriminator would have a harder time differentiating its generated images from the real ones.


#### *The generative network keeps producing images that are closer in appearance to the real images while the discriminative network is trying to determine the differences between real and fake images. The ultimate goal is to have a generative network that can produce images which are indistinguishable from the real ones.*

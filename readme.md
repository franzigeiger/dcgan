**Fork of Pre-trained GANs for CIFAR10**

Original source [here](https://github.com/csinva/pytorch-gan-pretrained)
- includes model class definitions + training scripts
- includes notebooks showing how to load pretrained nets / use them
- tested with pytorch 1.0, python 3
- generates images the same size as the dataset images
- based on the official [pytorch examples repo](https://github.com/pytorch/examples/tree/master/dcgan) with modifications to generate the appropriate size

### cifar10

The cifar10 gan is from the [pytorch examples repo](https://github.com/pytorch/examples/tree/master/dcgan) and implements the [DCGAN paper](http://arxiv.org/abs/1511.06434). It required only minor alterations to generate images the size of the cifar10 dataset (32x32x3). Trained for 200 epochs. Weights [here](https://github.com/csinva/pytorch_gan_pretrained/tree/master/cifar10_dcgan/weights).

| generated samples                                            | data samples                                           |
| ------------------------------------------------------------ | ------------------------------------------------------ |
| ![fake_images-300](cifar100_dcgan_grayscale/samples/fake_samples_epoch_299.png) | ![real_images](cifar100_dcgan_grayscale/samples/real_samples.png) |

### reference

- feel free to use/share this code openly

- here's a citation if you want to reference it: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2778737.svg)](https://doi.org/10.5281/zenodo.2778737)

```
@misc{singh2019gan,
  author       = {Chandan Singh},
  title        = {Pretrained GANs in pytorch for MNIST/CIFAR.},
  month        = {May},
  year         = {2019},
  doi          = {10.5281/zenodo.2778737},
  version      = {1.0.0},
  publisher    = {Zenodo},
  url          = {https://doi.org/10.5281/zenodo.2778737}
}
```

- for similar projects, see some other repos: (e.g. [acd](https://github.com/csinva/acd)) or website ([csinva.github.io](https://csinva.github.io/))

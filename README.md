# GAN for Abstract Art

Build and train Generative Adversarial Network for creating abstract art images on demand.

Trying out various GAN implementations (ex. DCGAN [[1]](#1)), training parameters and data preprocessing to create usable network for art generation. Training dataset consists of images of abstract painings [[2]](#2)


## Features

- testing different GAN implementaions
    - building generator, discriminator
    - calculating combined loss of the network
- data augmentation with ImageDataGenerator
- image data preprocessing
- training results visualisation
- cool results though unlike trainig data so far

## Technologies

- Python
    - sklearn
    - numpy
    - pandas
    - matplotlib, seaborn
- Tensorflow Keras API
- Jupyter Notebook

## Demo

During network training a batch of output images are generated at certain stages. They are saved to show how training progresses.



## Getting started

Browse attached Jupyter Notebooks.

## Misc

<a id="1">[1]</a> Following this implementation: https://github.com/mitchelljy/DCGAN-Keras

<a id="2">[2]</a> Abstract Art Gallery: https://www.kaggle.com/datasets/bryanb/abstract-art-gallery
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/transfer-learning-based-few-shot/few-shot-image-classification-on-cifar-fs-5)](https://paperswithcode.com/sota/few-shot-image-classification-on-cifar-fs-5?p=transfer-learning-based-few-shot)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/transfer-learning-based-few-shot/few-shot-image-classification-on-cifar-fs-5-1)](https://paperswithcode.com/sota/few-shot-image-classification-on-cifar-fs-5-1?p=transfer-learning-based-few-shot)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/transfer-learning-based-few-shot/few-shot-image-classification-on-cub-200-5-1)](https://paperswithcode.com/sota/few-shot-image-classification-on-cub-200-5-1?p=transfer-learning-based-few-shot)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/transfer-learning-based-few-shot/few-shot-image-classification-on-cub-200-5)](https://paperswithcode.com/sota/few-shot-image-classification-on-cub-200-5?p=transfer-learning-based-few-shot)

# Transfer learning based few-shot classification using optimal transport mapping from preprocessed latent space of backbone neural network

This is the official repository for the Transfer learning based few-shot classification using optimal transport mapping from preprocessed latent space of backbone neural network papers introducting the Latent Space Transform algorithm for preproccesing backbone-extracted feature vectors to resemble Gaussian-like distributions. 

https://arxiv.org/abs/2102.05176

![Model overview](https://raw.githubusercontent.com/ctom2/latent-space-transform/main/model_overview.png)

## Training

We use the same backbone network and training strategies as 'S2M2_R'. For more information about the backbone training, please refer to https://github.com/nupurkmr9/S2M2_fewshot.

## Pre-trained models

The trained models at miniImageNet, CIFAR-FS and CUB can be found on the following link: https://drive.google.com/file/d/1-DM1GSVpjQhjEbHvNdDq9oKc-DnNlt8i/view?usp=sharing.

The archive needs to be extracted in `/checkpoints` directory in the repository (you need to make the directory by yourself).

Please adjust the paths accordingly before running the model. 

Execute the model by running the following command:
```
python3 LST_run.py
```

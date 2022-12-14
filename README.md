## CSTP
Pytorch implementation for "Cascaded Compressed Sensing Networks".

## Dependencies
NVIDIA GPU + CUDA (may CuDNN) and corresponding PyTorch framework (version 1.8.0)

Python 3.7

## Datasets
We use CIFAR10 and MNIST datasets in our experiments. For the CIFAR10 dataset, it has been given as a .npz type file [Here](./data/). For the MNIST dataset, you can download it from [Here](http://yann.lecun.com/exdb/mnist/).

## Training
To train CSTP on the CIFAR10 dataset with Default Parameters, you can just run [train.py](./train.py). The network size and other hyperparameters can be modified [Here](./train.py#L128).

## Noise Evaluation
You can evaluate pre-trained CSTP and BP models in the presence of [Masking Noise](./Masking_Noise.py) or [Gaussian Noise](./Gussian_Noise.py). The pre-trained CSTP and BP models have been given [Here](./model/).

## Contact
If you have any problems about our code, feel free to contact
- mrchen@mail.sdu.edu.cn

or describe your problem in Issues.

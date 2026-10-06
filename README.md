# TensorFlow MNIST DCGAN

A deep convolutional GAN trained to generate handwritten-digit images from random noise.

## Run

Use Python 3.10 with the pinned dependencies:

```bash
python -m pip install -r requirements.txt
python dcgan.py
```

Keras downloads MNIST on first run. Training runs for 20,000 steps and displays generated samples afterward; expect a substantial training workload.

## Attribution

The notebook credits Aymeric Damien and the [TensorFlow-Examples project](https://github.com/aymericdamien/TensorFlow-Examples/). The notebook also cites Radford, Metz, and Chintala's [DCGAN paper](https://arxiv.org/abs/1511.06434).
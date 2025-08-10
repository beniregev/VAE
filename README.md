# Variational Autoencoder
Example of vanilla VAE for face image generation at resolution 128x128.

Auto-Encoding Variational Bayes: https://arxiv.org/abs/1312.6114

Generation:
<div>
	<img src='/sample_generation.jpg'>
</div>

Original Faces vs. Reconstructed Faces:

<div>
	<img src='/sample_reconstraction.jpg'>
</div>

## How to Run
You need to have PyTorch >= v0.4.1 and CUDA/cuDNN drivers installed.

To install requirements:

```python
pip install -r requirements.txt
```

To download and prepare the dataset:
```python
python prepare_celeba.py
```

To train:
```python
python VAE.py
```

## Class Exercise

Could you check the code and write what the size of the latent space is, i.e., how many dimensions it has?)

Similarly, in our MNIST network, the size was 2.

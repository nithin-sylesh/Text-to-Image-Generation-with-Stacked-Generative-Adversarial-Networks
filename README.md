# Text-to-Image-Generation-with-Stacked-Generative-Adversarial-Networks


The model architecture of StackGAN consists of mainly the following components:
Embedding: Converts the input variable length text into a fixed length vector. we will be using a pre-trained character level embedding.
Conditioning Augmentation (CA)
Stage I Generator: Generates low resolution (64*64) images.
Stage I Discriminator
Residual Blocks
Stage II Generator: Generates high resolution (256*256) images.
Stage II Discriminator

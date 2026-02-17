# Autoencoders: Basic to Variational

- What is Autoencoder?
    - it is a type of neural network that is used to learn a compressed representation of the input data.
- What is Encoder and Decoder?
    - Encoder: it is the part of the autoencoder that takes the input data and compresses it into a lower-dimensional representation, called the latent space.
    - Decoder: it is the part of the autoencoder that takes the compressed representation from the latent space and reconstructs the original input data.
- Where are Autoencoders used?
    - Autoencoders are used in various applications, including:
        - Dimensionality reduction
          - Principal Component Analysis (PCA) is a linear dimensionality reduction technique, while autoencoders can capture non-linear relationships in the data.
          - Autoencoders can learn more complex representations of the data compared to PCA, which is limited to linear transformations.
        - Anomaly detection
          - Autoencoders can be trained on normal data, and then used to identify anomalies by measuring the reconstruction error. If the reconstruction error is high, it indicates that the input data is different from the normal data, which can be an anomaly.
        - Image denoising
          - Autoencoders can be trained to remove noise from images by learning to reconstruct clean images from noisy inputs.
        - Data compression
          - Autoencoders can be used to compress data by learning a compact representation in the latent space, which can be useful for storage and transmission.
        - Generative modeling (e.g., Variational Autoencoders)
          - Variational Autoencoders (VAEs) are a type of autoencoder that can generate new data samples by sampling from the latent space, making them useful for tasks like image generation and data augmentation.
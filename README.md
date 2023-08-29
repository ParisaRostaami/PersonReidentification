<h1 align="center">
  Person Re-identification 
</h1>

<div align="center">


[![Contact](https://img.shields.io/badge/contact-Parisarostaamii@gmail.com%40example.com-yellow.svg)](mailto:Parisarostaamii@gmail.com)

</div>

<h2 align="center">Person Re-identification using Siamese Neural Networks</h2>

Welcome to the Person Re-identification project implemented using Siamese neural networks. This project focuses on the computer vision task of identifying individuals across different camera views.

## Project Overview

Person re-identification is a challenging task that involves recognizing individuals in different scenarios. Here are the key aspects of this project:

1. **Siamese Neural Networks**
    - Siamese networks are used to learn image embeddings that capture unique features of individuals.
    - The network architecture employs two branches that share weights, processing image pairs.
    - Embeddings are generated in a way that ensures similar individuals have closer embeddings.

2. **Data Preprocessing and Setup**
    - Python libraries like NumPy, OpenCV, and Keras are used for data handling.
    - Data setup involves file downloads, Google Drive mounting, and package installation.

3. **Data Sampling and Handling**
    - The `DataSampler` class handles data loading and preprocessing.
    - Positive pairs are extracted for training and testing based on specific criteria.
    - Datasets like Market1501 are utilized, performing train-test splits and extracting positive pairs.

4. **Model Architecture**
    - A Siamese neural network is constructed using Keras.
    - A pre-trained ResNet50 base model extracts features from images.
    - Dense layers process concatenated embeddings from the Siamese branches.
    - Different optimizers like SGD and Nadam are employed, using binary cross-entropy loss.

5. **Training and Evaluation**
    - A data generator feeds training and testing data batches to the model.
    - Training progress is monitored using validation accuracy and loss.
    - Matplotlib is used to visualize training and validation accuracy, and loss curves.

6. **Inference and Similarity Scoring**
    - The model inference is demonstrated on image pairs using the trained Siamese network.
    - Images are preprocessed, dimensions expanded, and similarity scores predicted.
    - Similarity scores indicate the likeness between input image pairs.

7. **Project Conclusion**
    - The project successfully implements a person reidentification system using Siamese neural networks.
    - Model performance is evaluated on test data, highlighting binary accuracy and other metrics.
    - This project serves as a foundational step towards developing advanced person reidentification systems.

**Contact**: [Parisa.rostaamii@gmail.com](mailto:Parisa.rostaamii@gmail.com)

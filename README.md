<a target="_blank" href="https://colab.research.google.com/github/JulienDelavande/Compression_DNN/blob/main/Compression_de_r%C3%A9seaux_de_neurones_profonds.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

# Compression of Deep Neural Networks

This repository contains an educational notebook created during a Deep Learning module in my final year at ISAE-Supaero. The notebook serves as a reference and example for understanding and applying various compression techniques to deep neural networks. 

All techniques presented here are adapted from the paper **"Compression of Deep Neural Networks"**. Full credit goes to the original authors.  
[Paper link](https://arxiv.org/abs/1510.00149)

## Table of Contents

0. [Introduction](#introduction)
1. [Model Training and Testing](#1-model-training-and-testing)
2. [Pruning](#2-pruning)
3. [Quantization via Weight Sharing](#3-quantization-via-weight-sharing)
4. [Huffman Coding](#4-huffman-coding)
5. [New Compression Perspectives](#5-new-compression-perspectives)
6. [Conclusion](#6-conclusion)

## 0. Introduction

This section provides an overview of the context and objectives of deep neural network compression, discussing why compression is important and its practical benefits.

## 1. Model Training and Testing

We detail the initial training and evaluation of the neural network model before applying any compression techniques.

## 2. Pruning

Pruning is a compression method that removes less significant weights in a neural network to reduce its size while maintaining acceptable performance.

## 3. Quantization via Weight Sharing

Weight sharing reduces the size of the model by limiting the distinct values weights can take, grouping them into clusters of similar values.

## 4. Huffman Coding

Huffman coding is a lossless compression technique that can be applied to the weights of neural networks to further decrease their size.

## 5. New Compression Perspectives

This section explores advanced and emerging compression techniques such as knowledge distillation, GAN-based compression, dynamic quantization, tensor coding, and dynamically sparsified networks.

## 6. Conclusion

A summary of the main compression techniques, their impacts, and potential use cases is provided here.

## How to Use This Notebook

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/compression-of-deep-neural-networks.git
   cd compression-of-deep-neural-networks
   ```

2. **Install dependencies:**
   Ensure you have Python and pip installed, then run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook:**
   Launch Jupyter Notebook or Jupyter Lab:
   ```bash
   jupyter notebook
   ```
   Open `compression_of_deep_neural_networks.ipynb` to explore the different compression techniques.

**Alternatively, you can execute the notebook directly on Google Colab using the badge above.**

## Contributions

Contributions are welcome! If you have suggestions, improvements, or corrections, feel free to submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

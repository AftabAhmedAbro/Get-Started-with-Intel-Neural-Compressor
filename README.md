# Get-Started-with-Intel-Neural-Compressor

## Introduction
The Intel Neural Compressor is a deep learning-based compression tool developed by Intel. It is designed to reduce the size of deep neural networks by compressing them without significantly reducing their accuracy.

The neural compressor uses a combination of techniques, including pruning, quantization, and Huffman coding, to compress deep neural networks. Pruning involves removing unnecessary connections or neurons from the network, while quantization involves reducing the precision of weights and activations to use fewer bits to represent them. Huffman coding is a lossless compression technique that further reduces the size of the compressed model.

The Intel Neural Compressor is useful for deploying deep learning models in resource-constrained environments, such as mobile devices or embedded systems, where storage and computation resources are limited. It can also help reduce the bandwidth required for transmitting models over the internet.

### To install Inet Neural Compressor on your sytem use this command:
```
pip install intel-neural-compressor
```

# Experiments for Medical Image Streaming Toolkit (MIST)

This repository provides source code to recreate the experimental design from our paper. The implementation of MIST is open-source and available [here](https://github.com/UM2ii/MIST).

**Note:** This repository is currently a work in progress. Please contact us for more details [here](mailto:pkulkarni@som.umaryland.edu,vparekh@som.umaryland.edu).

## One Copy Is All You Need: Resource-Efficient Streaming of Medical Imaging Data at Scale

### Pranav Kulkarni, Adway Kanhere, Eliot Siegel, Paul H. Yi, Vishwa S. Parekh*

Large-scale medical imaging datasets have accelerated development of artificial intelligence tools for clinical decision support. However, the large size of these datasets is a bottleneck for users with limited storage and bandwidth. Many users may not even require such large datasets as AI models are often trained on lower resolution images. If users could directly download at their desired resolution, storage and bandwidth requirements would significantly decrease. However, it is impossible to anticipate every users' requirements and impractical to store the data at multiple resolutions. What if we could store images at a single resolution but send them at different ones? We propose MIST, an open-source framework to operationalize progressive resolution for streaming medical images at multiple resolutions from a single high-resolution copy. We demonstrate that MIST can dramatically reduce imaging infrastructure inefficiencies for hosting and streaming medical images by >90%, while maintaining diagnostic quality for deep learning applications.

You can read our paper on MIST [here](https://arxiv.org/abs/2307.00438)!

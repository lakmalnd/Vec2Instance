# Vec2Instance

This repository provides an implementation of Vec2Instance over the SpaceNet challenge AOI 2 (Vegas) building footprint dataset. And this is published in [arXiv](#).

### Introduction

Vec2Instance provides a framework for parametrization of instances, allowing convolutional neural networks to efficiently estimate the complex shapes of instances around their centroids. We demonstrate the feasibility of the proposed architecture with respect to instance segmentation tasks on satellite images, which have a wide range of applications. Moreover, we demonstrate the usefulness of the new method for extracting building foot-prints from satellite images. Vec2Instance is an alternative approach to complex instance segmentation pipelines, offering simplicity and intuitiveness.

### Libraries used

* numpy
* matplotlib
* tensorflow v1.15 (keras)

### Content

Proposed new neural network architecture for the instance segmentation task comprising two CNNs. The first CNN estimates centroids of instances, and the second CNN preforms instance segmentation around each centroid. So there are 3 notebooks in this repository. First 2 notebooks are for training of Centroid Estimation CNN and Instance Segmentation CNN. And the third notebook is for the prediction process, combining the results of Centroid Estimation CNN and Instance Segmentation CNN.

* Notebook I: Training the Centroid Estimation CNN
* Notebook II: Training the Instance Segmentation CNN
* Notebook III: Prediction
* Notebook IV: Face Reconstruction with Vec2Instance

### Citation

Cite our paper

### Sample data source

* SpaceNet. (2018). Spacenet on Amazon Web Services (AWS). ”Datasets.” The SpaceNet Catalog. https://spacenetchallenge.github.io/datasets/datasetHomePage.html.

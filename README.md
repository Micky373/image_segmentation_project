# Image_segmentation_project

**Table of content**

- [Overview](#overview)
- [Install](#install)
- [Methodology](#Methodology)
- [Data](#data)
- [Notebooks](#notebooks)
- [Scripts](#scripts)
- [Test](#test)

## Overview

> In this project I have tried to work on image segmentation of more than 1000 ultrasound images.
> The purpose of this project is to do binary image segmentation.

## Install

```
git clone https://github.com/Micky373/image_segmentation_project.git
cd image_segmentation

```
## Methodology (Still working on it)

> The first thing I did was to go through the data and find out the image and their coresponding masks
> After I saw the image and masks are of equal sizes and their was no missing image with its mask the next thing I did was to choose the modeling path
> In the modeling path I was having of two methods the deep learning and machine learning path
> While using the Machine learning path I found out that using the RandomForestClassifier works best for such kind of image segmentations
> While using the Deep learning path I found out that the Unet modeling structure works best
> The next thing I did was to choose of the two types, given the fact that I have more than thousand images using the Deep learning path works best
> So I trained a Unet model and resized all the images used the masks as a target
> After finishing the training and prediction the next thing that I tried to do was to find out the losses
> Due to some reasons for now all the validation losses are given a `nan` value
> I am plannig to do the Dice and IOU for my modelling part after fixing this error

## Data

Data can be found [here](https://drive.google.com/drive/folders/18TTRBZA9OqlJrvt3PAjYBtahKYI3KuTs?usp=sharing)

## Notebooks

> All the analysis and examples of implementation will be here in the form of .ipynb file

## Author

👤 **Michael Tamirie**

- GitHub: [Michael Tamirie](https://github.com/Micky373)
- LinkedIn: [Michael Tamirie](https://www.linkedin.com/in/michaeltamirie/)

## Show your support

Feel free to check the [issue page](https://github.com/Micky373/image_segmentation_project/issues)
Give a ⭐ if you like this project!
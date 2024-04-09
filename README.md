# Image-Processing-Project-IIP
A Technique based on morphology and connected components to count the number of disks in an image using Python Libraries.
#### Libraries Used: `Numpy`, `skimage`, `morphology` and `matplotlib`**(Using Pyplot)**.

> #### Question: You are given a binary image with some disks and squares, some of which overlap. For each question provide an algorithm that uses morphological and logical operations to answer the questions. The answers may be in the form of pseudocode with a block diagram. For extra credit, you may submit an Python program that implements the algorithms. Assume all disks are the same size and all squares are the same size.

> + (a) Develop a technique based on morphology and connected components to count the number of disks in the above image. 
> + (b) Develop a technique based on morphology and logic to count the boundary pixels in the above image. 
> + (c) Develop a technique based on morphology and logic to count the pixels that are common to two or more objects.

##### `Image Processing Assignment/Project University of Central Punjab`

## How to Use:
> Run using [Jupyter NoteBook](https://jupyter.org/) or any Python IDE.  



## Installation:

#### ***PIL (Python Imaging Library) :***
> Pillow (Python Imaging Library): Pillow is used for image manipulation tasks like opening, saving, and modifying images.
```bash
pip install Pillow
```
#### ***Requests :***
> Requests library is used for making HTTP requests to download images from URLs. (It will be used in V1.1)
```bash
pip install requests
```
#### ***IO (Input/Output) :***
> This module provides facilities for working with various types of I/O (input/output) in Python.
---
> In the `V1.1` code, BytesIO from the io module is used to convert the response content from the requests library into a file-like object that PIL can work with.

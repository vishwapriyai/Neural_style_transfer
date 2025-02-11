# Neural Style Transfer

## Overview
This project implements a Neural Style Transfer algorithm using TensorFlow and TensorFlow Hub. The goal is to combine the content of one image with the style of another image, creating a new stylized image. Users can upload their own content and style images to generate unique artistic representations.

## Technologies Used
- Python
- TensorFlow
- TensorFlow Hub
- NumPy
- Matplotlib
- PIL (Python Imaging Library)

## Setup
To set up the environment, import the necessary libraries:

```python
import os
import tensorflow as tf
import IPython.display as display
import matplotlib.pyplot as plt
import numpy as np
import PIL.Image
```

## Usage
- **Upload Images**: Users can upload their content and style images.
- **Load and Visualize Images**: The uploaded images are loaded and displayed.
- **Perform Style Transfer**: The project uses a pre-trained model from TensorFlow Hub to apply the style of one image to the content of another.
- **Save and Download**: The resulting stylized image can be saved and downloaded.

## Conclusion
This project demonstrates the implementation of Neural Style Transfer, allowing users to create unique stylized images by combining different content and style images.

![Screenshot of the Application](Screenshot%202025-02-11%20142010.png)


![Screenshot of the Application](Screenshot%202025-02-11%20142023.png)

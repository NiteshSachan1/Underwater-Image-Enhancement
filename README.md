# Underwater-Image-Enhancement
This is a machine learning based project which aims to enhance the underwater / deep-sea images
This repository contains code and resources for enhancing the quality of underwater images. Underwater images often suffer from issues such as color distortion, low contrast, and blurriness due to the absorption and scattering of light in water. This project aims to address these challenges and improve the visual quality of underwater images.

## Table of Contents
[
* [<a name="Introduction"></a>Introduction
* Features
* Installation
* Usage
* Contributing]

## Introduction
Underwater Image Enhancement is crucial for various applications such as marine biology, underwater robotics, and underwater photography. This project implements several techniques to enhance underwater images, making them clearer and more visually appealing.

## Features
Color correction to address color distortions.
Contrast enhancement to improve visibility.
Dehazing to reduce blurriness caused by water particles.
Noise reduction to remove unwanted artifacts.
Support for multiple image formats.
## Installation
### Prerequisites
Python 3.6 or higher
pip (Python package installer)
### Steps
Clone the repository:
https://github.com/Abhish-akp/UnderWater-Image-Enhancement-.git
cd underwater-image-enhancement
## Usage
### Command Line Interface
You can use the command line interface to enhance underwater images. Run the following command to see the available options:

Underwater_Image_Enhancement(Project).ipynb --help
### Script

You can also use the provided Python script in your own projects. Here is an example:

from enhancement import enhance_image

input_image = "path/to/your/image.jpg"
output_image = "path/to/save/enhanced_image.jpg"

enhance_image(input_image, output_image)

https://github.com/Abhish-akp/UnderWater-Image-Enhancement-.git
cd underwater-image-enhancement

from enhancement import enhance_image

input_image = "path/to/your/image.jpg"
output_image = "path/to/save/enhanced_image.jpg"

enhance_image(input_image, output_image)



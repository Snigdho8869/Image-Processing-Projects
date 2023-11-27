# Image Compression and Format Conversion

## Overview
This repository contains the code for compressing and converting images in a specified directory. This allows you to adjust compression quality, output format (JPEG or PNG), and optionally resize images. The graphical user interface (GUI) version is also available for easy interaction.


## Features

- Compress images with adjustable quality.
- Convert images to JPEG or PNG format.
- Option to resize images while processing.
- User-friendly interface with Jupyter Notebook widgets.

## Requirements

- Python 
- Pillow library 
- Jupyter Notebook (for widget-based interface)


## Configuration

- **input_dir**: Path to the directory containing the input images.
- **output_dir**: Path to the directory where compressed images will be saved.
- **compression_quality**: Enter compression quality in the range of 0 to 100.
- **use_original_dimensions**: Choose whether to use the original dimensions of the images.
- **target_width and target_height**: Specify the target width and height if resizing images.
- **output_format**: Choose between 'JPEG' and 'PNG' for the output format.
- **png_quality**: Set the PNG quality as 'High' or 'Low' (applicable if output format is PNG).



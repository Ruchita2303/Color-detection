
# Color Detection Project

This project uses OpenCV and Pandas to detect and display the name of the color of any pixel in an image. The program reads an image, and upon double-clicking on any part of the image, it shows the name of the color along with its RGB values.

## Table of Contents
1. Features
2. Installation
3. Usage

## Features
- Detects and displays the color name and RGB values of any pixel in the image.
- Uses a pre-defined CSV file containing color names and their corresponding RGB values.
- Interactive UI that shows color information upon double-clicking on the image.

## Installation
To run this project, you will need to have Python installed along with the following libraries:
- OpenCV
- NumPy
- Pandas

You can install the required libraries using pip:
```bash
pip install opencv-python numpy pandas
```
##  Usage
-Clone this repository to your local machine.
-Ensure you have the colors.csv file in the same directory as your script.
-Run the script using the following command:
```bash
python color_detection.py -i <path_to_your_image>
```







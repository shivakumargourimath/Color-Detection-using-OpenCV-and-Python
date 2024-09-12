# Color-Detection-using-OpenCV-and-Python
This project demonstrates how to detect colors in an image using the OpenCV library in Python. It allows users to click on any part of an image and get the name of the color along with its RGB values.
The project utilizes a dataset ('colors.csv') that maps RGB values to color names, providing a foundation for accurate color recognition.

# How to interact:
Click anywhere on the image, and the script will display the color name and RGB values both on the image window and in the terminal.
Press Esc to exit the program.

# How It Works
1.Loading the Image: OpenCV reads the input image and displays it in a window.
2.Color Data: The colors.csv file contains color names and their corresponding RGB values. This file helps the program match the clicked pixel to its closest color name.
3.Mouse Callback: OpenCV captures the mouse click events, extracting the RGB values of the clicked pixel.
4.Color Matching: The program compares the pixel's RGB values with the colors in colors.csv to find the nearest color name.
5.Result Display: The detected color and its RGB values are displayed on the image and printed in the terminal

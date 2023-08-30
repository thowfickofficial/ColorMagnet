# ColorMagnet

## Overview

ColorMagnet is a Python script that uses computer vision to recognize the dominant color in the camera feed and display its name along with the RGB values in real-time. This script is a fun way to explore and learn about different colors and their representations in RGB.

## Features

- **Real-Time Color Recognition**: ColorMagnet captures the camera feed and continuously recognizes the dominant color, displaying its name on the user interface.

- **Color Name and RGB Values**: The script not only displays the recognized color name but also provides the RGB values of the detected color.

- **Closest Color Matching**: ColorMagnet matches the captured color with a predefined dictionary of color names and their RGB values to find the closest match.

- **User-Friendly GUI**: The script offers a simple and user-friendly graphical user interface (GUI) to view the camera feed and color information.

- **Exit Button**: An "Exit" button is provided to close the camera and exit the application gracefully.

## Prerequisites

- Python 3.x
- OpenCV (`cv2` module) for capturing and processing the camera feed.
- NumPy for mathematical operations.
- `webcolors` for color name recognition.
- tkinter for creating the graphical user interface.
- Pillow (`PIL`) for image handling.

## Usage

1. Run the script by executing `python ColorMagnet.py` in your terminal.

2. The script will open a GUI window displaying the camera feed.

3. Point the camera at an object with a dominant color, and ColorMagnet will continuously recognize and display the closest color name along with its RGB values.

4. To exit the application, click the "Exit" button.

## Customization

You can customize the list of recognized colors and their RGB values by modifying the `color_names_rgb` dictionary in the script. Add or remove color entries as desired.

## Disclaimer

ColorMagnet is designed for educational and entertainment purposes. The accuracy of color recognition may vary based on lighting conditions and the camera's capabilities.


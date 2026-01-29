# Intelligent-Traffic-Sign-Detection-System

# 📌 Project Overview

* The Intelligent Traffic Sign Detection System is a computer vision–based application that detects and identifies common traffic signs and signals from images.
It uses OpenCV for image processing, NumPy for pixel analysis, and Gradio to provide an interactive web interface.

* The system is rule-based and detects traffic signs by combining color detection (HSV color space) and shape detection (contours) techniques.

# 🎯 Features

* 🚥 Traffic Signal Detection (Red, Yellow, Green)

* 🛑 Stop Sign Detection

* ⛔ No Entry Sign Detection

* 🚫 Speed Limit Sign Detection

* 🚸 Pedestrian Crossing Detection

* 🌐 Simple and interactive web UI using Gradio

* ⚡ Real-time image processing

# 🛠️ Technologies Used

* Python

* OpenCV (cv2)

* NumPy

* Gradio

* Computer Vision Techniques

# 🧠 Working Principle

1. Image Preprocessing

  * Convert image from RGB to BGR and HSV

  * Convert image to grayscale for edge detection

2. Color Detection

  * Detect Red, Yellow, Green, and Blue regions using HSV color ranges

  * Count color pixels to determine dominant colors

3. Shape Detection

  * Apply Gaussian Blur and Canny Edge Detection

  * Detect contours and approximate shapes

  * Identify shapes like circles and octagons

4. Rule-Based Classification

  * Combine color dominance and shape features

  * Classify traffic signs accordingly

5. Result Display

  * Show detected traffic sign using Gradio interface

# 📂 Project Structure
📁 Traffic-Sign-Detection
│── app.py                  # Main application file
│── README.md               # Project documentation
│── requirements.txt        # Required libraries

# 🖼️ Sample Output

* 🟢 GREEN SIGNAL – GO

* 🔴 RED SIGNAL – STOP

* 🛑 STOP SIGN

* ⛔ NO ENTRY SIGN

* 🚸 PEDESTRIAN CROSSING

# 🚀 Future Enhancements

* Use Deep Learning (CNN) for higher accuracy

* Add bounding boxes around detected signs

* Support video and real-time camera feed

* Expand dataset for more traffic sign types

* Deploy as a mobile or web application

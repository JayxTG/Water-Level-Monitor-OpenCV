# Water Level Detection

## Project Description

This project aims to develop a real-time water level detection system using a webcam and computer vision techniques. The system captures video frames, processes each frame to detect water levels, and displays the water level on the frame. It uses simple image processing techniques like grayscale conversion, thresholding, and contour detection to identify and highlight the water level in the video feed.

## 🎯 Objective

The objective of this project is to create an automated system that can detect water levels in real-time, providing a potential tool for monitoring water levels in tanks, reservoirs, or other relevant applications.

## 🔑 Key Features

- 🎥 Real-time water level detection using a webcam
- 🌊 Drawing contours around detected water levels
- 🛠️ Simple thresholding and contour detection algorithm
- 🚨 Displaying visual feedback when water levels are detected

## 🛠️ Hardware and Software Requirements

### Hardware:
- Webcam

### Software:
- OpenCV
- ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
- NumPy


## 📸 Sample Usage
**Detecting Falls**
Run the application, and it will start the webcam feed. The system will detect humans in the frame, draw stick figures around them, and display an alert if a fall is detected.

## Dependencies
- OpenCV
- NumPy

## 🎛️ How to Use

1. **Clone the Repository**

   Clone the repository to your local machine:
   ```bash
   git clone https://github.com/JayxTG/Water-Level-Monitor-OpenCV.git
    ```
2. **Install Dependencies**
 Navigate to the project directory and install the required dependencies:

   ```bash
   pip install -r requirements.txt

    ```
3. **Run the Application**
  Execute the main script to start the fall detection system:

   ```bash
   python src/fall_detection.py
   
    ```

## 🏢 Acknowledgments
- OpenCV community for the computer vision tools
- NumPy community for the numerical computation tools
  
## License

Author: Jayamadu Gammune

Permission is hereby granted, free of charge, to any person obtaining a copy of 
this software and associated documentation files (the "Software"), to deal in 
the Software without restriction, including without limitation the rights to 
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies 
of the Software, and to permit persons to whom the Software is furnished to do 
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all 
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR 
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, 
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE 
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER 
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, 
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE 
SOFTWARE.

**DISCLAIMER:**
This code is provided for educational and informational purposes only. It is 
still under development and may contain bugs or inaccuracies. The authors are 
not responsible for any damage or loss resulting from the use of this code. Use 
at your own risk.

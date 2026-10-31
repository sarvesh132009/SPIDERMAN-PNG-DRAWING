# SPIDERMAN-PNG-DRAWING
# 🕷️ Spider-Man Image to Art – Python Turtle Graphics

A Python project that transforms an image into a drawing using **OpenCV** and **Turtle Graphics**. It detects the outlines and shapes in an image, processes them into contours, and automatically recreates the image through an animated drawing process.

## 🚀 Project Overview

This project demonstrates how Python can combine computer vision and graphics to create an automated drawing animation.

Using OpenCV, the program processes an input image, detects its contours, filters unwanted noise, and converts the detected coordinates into Turtle Graphics movements.

The Turtle module then draws the processed image on the screen, creating a hand-drawn animation effect.

## ✨ Features

- 🖼️ **Image Processing:** Reads and processes images using OpenCV.
- 🎨 **Grayscale Conversion:** Converts the original image into grayscale.
- 🔍 **Contour Detection:** Identifies the outlines and shapes within the image.
- 🧹 **Noise Filtering:** Removes small unwanted contours.
- 📐 **Image Resizing:** Adjusts the image dimensions while maintaining its aspect ratio.
- 🐢 **Turtle Graphics:** Recreates the image using Python Turtle.
- ⚡ **Animated Drawing:** Displays the drawing progressively to create an animation effect.

## 🛠️ Technologies Used

- Python
- OpenCV (`cv2`)
- Turtle Graphics
- NumPy (used internally by OpenCV)

## 📁 Project Structure

```text
Image-to-Art/
│
├── time.py
├── spiderman.png
└── README.md
```

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Navigate to the Project Folder

```bash
cd YOUR-REPOSITORY
```

### 3. Install Dependencies

```bash
pip install opencv-python
```

### 4. Add Your Image

Place your image in the project folder and name it:

```text
spiderman.png
```

Make sure the image filename matches the filename specified in the Python code.

## ▶️ How to Run

Execute the following command:

```bash
python time.py
```

A Turtle Graphics window will open, and the program will start drawing the image automatically.

## 🧠 How It Works

The project follows these steps:

1. **Image Loading:** OpenCV reads the input image.
2. **Resizing:** The image is resized to a fixed height while maintaining its aspect ratio.
3. **Grayscale Conversion:** The image is converted into grayscale.
4. **Thresholding:** A binary image is created to distinguish foreground shapes from the background.
5. **Contour Detection:** OpenCV identifies the external contours.
6. **Noise Removal:** Tiny contours are filtered out.
7. **Contour Sorting:** Larger shapes are drawn first.
8. **Coordinate Mapping:** Image pixel coordinates are converted into Turtle Graphics coordinates.
9. **Drawing Animation:** Turtle follows the detected contours and recreates the image.

## 🎯 Learning Outcomes

Through this project, I explored:

- Image processing using OpenCV.
- Computer vision fundamentals.
- Contour detection and image segmentation.
- Coordinate transformation.
- Python Turtle Graphics.
- Animation and graphical rendering.
- Combining multiple Python libraries into one application.

## 🔮 Future Improvements

- Support for multiple image formats.
- Customizable drawing speed.
- Adjustable drawing colors.
- Better edge detection and image processing.
- Interactive image selection.
- Support for more complex images.

## 👨‍💻 Author

SARVESH

Created as a Python programming and computer vision project.

---

⭐ If you find this project interesting, consider giving the repository a star!

# 🛣️ Lane Detection with OpenCV 
This project demonstrates how to detect lane lines on roads using OpenCV and Python. Each step is explained with visual outputs and documentation.


## 🚀 How It Works

1. Load an image
2. Convert to grayscale
3. Apply Gaussian Blur
4. Detect edges using Canny
5. Focus on road area (Region of Interest)
6. Detect lane lines using Hough Transform
7. Overlay lines on original image

## 📁 File Structure

- `lane_detection.ipynb` - Jupyter Notebook 
- `test_frame.jpg` - Sample road image
- `output_images/` - Output folder with plots
- `requirements.txt` - List of Python libraries to install

## 📦 Installation

```bash
pip install -r requirements.txt

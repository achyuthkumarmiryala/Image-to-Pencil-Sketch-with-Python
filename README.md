# 🖼️ Image to Pencil Sketch with Python

This project demonstrates how to convert a colored image into a pencil sketch using Python and OpenCV. The transformation leverages fundamental image processing techniques to achieve a realistic sketch effect.

---

## 📁 Repository Contents

- `Untitled6.ipynb`: Jupyter Notebook containing the implementation of the pencil sketch conversion.
- `README.md`: Project documentation and overview.

---

## 🎯 Objectives

- Convert colored images to pencil sketches using OpenCV.
- Understand the step-by-step image processing involved in the transformation.
- Provide a simple and interactive interface for users to experiment with different images.

---

## 🛠️ Tools & Libraries

- **Python 3.x**
- **OpenCV (`cv2`)**: Image processing library.
- **NumPy**: Numerical computing.
- **Jupyter Notebook**: Interactive computing environment.

---

## 📊 Methodology

1. **Read the Image**: Load the original colored image using OpenCV.
2. **Convert to Grayscale**: Simplify the image by removing color information.
3. **Invert the Grayscale Image**: Create a negative of the grayscale image.
4. **Apply Gaussian Blur**: Smooth the inverted image to reduce noise and detail.
5. **Blend Images**: Combine the grayscale image with the blurred inverted image using a color dodge technique to highlight the sketch effect.

---

## 🚀 Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/achyuthkumarmiryala/Image-to-Pencil-Sketch-with-Python.git
   cd Image-to-Pencil-Sketch-with-Python
   ```

2. **Install Dependencies**:
   Ensure you have the required libraries installed:
   ```bash
   pip install opencv-python numpy
   ```

3. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook "Untitled6.ipynb"
   ```

4. **Run the Notebook**:
   Follow the instructions within the notebook to convert your desired image into a pencil sketch.

---

## ✅ Results

The final output is a pencil sketch version of the original image, showcasing the effectiveness of basic image processing techniques in creating artistic effects.

---

## 📌 Notes

- Ensure that the image you want to convert is placed in the appropriate directory and the path is correctly specified in the notebook.
- Experiment with different images to observe varying sketch effects.

---

## 👤 Author

**Achyuth Kumar Miryala**  
Master’s in Data Science | University of North Texas  
📍 Denton, TX  
📫 [achyuthkumar286@gmail.com](mailto:achyuthkumar286@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/achyuthkumarmiryala/) | [GitHub](https://github.com/achyuthkumarmiryala)

---

## 📄 License

This project is intended for academic and educational purposes. For any other use, please contact the author.

---

If you find this project insightful, feel free to ⭐ the repository or connect on [LinkedIn](https://www.linkedin.com/in/achyuthkumarmiryala/)!

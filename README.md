

# **Image Processing Lab**

This repository hosts a Jupyter Notebook showcasing a variety of image processing techniques. These techniques are widely used for manipulating, enhancing, and analyzing digital images using Python and associated libraries.



## **Features**

This lab covers the following key concepts:
- **Image Manipulation**: Operations like resizing, cropping, and geometric transformations.
- **Image Enhancement**: Adjusting brightness, contrast, and applying filters to enhance image quality.
- **Image Analysis**: Techniques for detecting edges, finding contours, and analyzing image structures.
- **Color Space Conversions**: Working with RGB, grayscale, and other color models.
- **Noise Reduction**: Applying filters (e.g., Gaussian and median) to reduce noise in images.



## **Prerequisites**

Before running the notebook, ensure that the following tools and libraries are installed:

- **Python 3.8 or higher**
- **Jupyter Notebook**
- **Required Python Libraries**:
  - [OpenCV](https://opencv.org/)
  - [NumPy](https://numpy.org/)
  - [Matplotlib](https://matplotlib.org/)

Install the dependencies using pip:

```bash
pip install opencv-python numpy matplotlib
```



## **How to Use**

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/ashithapallath/Image-Processing.git
   cd Image-Processing
   ```

2. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook Image_Processing.ipynb
   ```

3. Follow the step-by-step explanations in the notebook, executing the cells to explore the various image processing tasks.



## **Examples**

### **1. Grayscale Conversion**
Convert an image to grayscale for simplicity in analysis:
```python
gray_image = cv2.cvtColor(image, cv2.COLOR_BGR2GRAY)
plt.imshow(gray_image, cmap='gray')
```

### **2. Edge Detection**
Detect edges using the Canny algorithm:
```python
edges = cv2.Canny(image, threshold1=50, threshold2=150)
plt.imshow(edges, cmap='gray')
```



## **Contribution Guidelines**

We welcome contributions to enhance the repository!  
- **Fork the repository** to make changes.
- Create a **pull request** with detailed explanations for your updates.
- Ensure all contributions adhere to clean coding practices.



## **License**

This project is distributed under the **MIT License**. Feel free to use, modify, and distribute this code with proper attribution. See the [LICENSE](LICENSE) file for more details.



## **Acknowledgments**

We extend our gratitude to the open-source community for tools like:
- **OpenCV** for efficient image processing.
- **NumPy** for numerical computing.
- **Matplotlib** for robust data visualization.


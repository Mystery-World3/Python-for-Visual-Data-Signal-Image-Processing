# Python for Visual Data: Signal & Image Processing

Welcome to this hands-on Jupyter Notebook demonstrating fundamental operations on signals and images using Python. This project serves as a practical introduction to signal and image processing, showcasing how to perform arithmetic operations like addition on both 1D signals and 2D images.

## 🌟 Key Features

-   **1D Signal Operations**: Learn how to generate and combine one-dimensional signals, such as a sine wave and a unit step signal.
-   **2D Image Arithmetic**: Understand how to load and perform pixel-wise addition on two separate images.
-   **Core Libraries in Action**: See how popular Python libraries like NumPy, Matplotlib, and OpenCV are used for visual data manipulation.
-   **Clear Visualizations**: All operations are accompanied by plots and image displays to clearly illustrate the results.

## 📖 Notebook Content

The `image.ipynb` notebook is structured into two main parts:

1.  **1D Signal Addition**:
    * Generation of a sine wave (`sin(0.5πn)`).
    * Generation of a unit step signal.
    * Addition of the two signals and plotting the original and resulting signals using `matplotlib`.

2.  **2D Image Addition**:
    * Loading two images (`lena.png` and `baboon.png`) using OpenCV (`cv2`).
    * Performing pixel-wise addition between the two images.
    * Displaying the original images and the final blended image.

## 🛠️ Tech Stack & Dependencies

To run this notebook, you will need the following Python libraries installed:

-   `numpy`
-   `matplotlib`
-   `opencv-python`
-   `jupyter`

You can install them via pip:

```bash
pip install numpy matplotlib opencv-python jupyterlab
```

## 🚀 How to Run

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/Mystery-World3/Python-for-Visual-Data-Signal-Image-Processing.git
    cd Python-for-Visual-Data-Signal-Image-Processing
    ```
2.  **Add Images**: Make sure you have the `lena.png` and `baboon.png` image files in the same directory as the notebook.

3.  **Launch Jupyter Notebook**:
    ```bash
    jupyter-lab
    ```
    Then, open the `image.ipynb` file and run the cells.

*Created by Mystery-World3*

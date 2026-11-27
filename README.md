# Edge Detection Using OpenCV

## 🎯 Aim

To perform edge detection using Sobel, Roberts, Prewitt, Laplacian, and Canny edge detection techniques using OpenCV.

## 🛠️ Software Required

- Anaconda – Python 3.7
- Jupyter Notebook / VS Code
- OpenCV (`cv2`)
- NumPy
- Matplotlib

## ⚙️ Algorithm

**Step 1:** Import all the necessary modules for the program.

**Step 2:** Load an image using `cv2.imread()`.

**Step 3:** Convert the input image into grayscale.

**Step 4:** Apply the **Sobel operator** using OpenCV to detect edges.

**Step 5:** Apply the **Prewitt operator** using custom kernels.

**Step 6:** Apply the **Roberts operator** using custom kernels.

**Step 7:** Apply the **Laplacian operator** using OpenCV.

**Step 8:** Apply the **Canny edge detector** using OpenCV.

**Step 9:** Display all edge-detected images for comparison.

## 👨‍💻 Developed By

- **Name:** ______________________________
- **Register No:** ________________________

## 📸 Output

### 1. Sobel Edge Detector

- Detects edges in horizontal and vertical directions.
- Produces a gradient-based edge map.

### 2. Prewitt Edge Detector

- Uses simpler kernels compared to Sobel.
- Detects directional edges.

### 3. Roberts Edge Detector

- Detects edges using diagonal gradients.
- Sensitive to noise.

### 4. Laplacian Edge Detector

- Detects edges using second-order derivatives.
- Highlights rapid intensity changes.

### 5. Canny Edge Detector

- Uses a multi-stage edge detection process.
- Produces clean and thin edges.

## ✅ Result

Thus, edges were successfully detected using Sobel, Prewitt, Roberts, Laplacian, and Canny edge detection techniques. Each method highlights edges differently based on gradient and intensity variations, improving feature extraction and image analysis.

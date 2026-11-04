# Image Smoothing and Sharpening Using OpenCV

# Aim
To write a Python program using OpenCV to apply different smoothing filters (Averaging, Weighted Averaging, Gaussian, Median) and sharpening filters (Laplacian Kernel and Laplacian Operator) for image enhancement, and display each result separately along with the original image for comparison.

The program performs the following operations:
Read and display an input image
Apply Averaging filter
Apply Weighted Averaging filter
Apply Gaussian filter
Apply Median filter
Apply Laplacian sharpening using kernel
Apply Laplacian operator
Display all outputs for comparison

# Software Used
Anaconda – Python 3.7
Jupyter Notebook / VS Code
OpenCV (cv2)
NumPy
Matplotlib

# Algorithm

Step 1:
Import the required libraries: OpenCV, NumPy, and Matplotlib.

Step 2:
Read the input image (e.g., image.jpg).

Step 3:
Convert the image from BGR to RGB format for display.

Step 4:
Apply Averaging Filter using cv2.blur().

Step 5:
Apply Weighted Averaging Filter using a custom kernel with cv2.filter2D().

Step 6:
Apply Gaussian Filter using cv2.GaussianBlur().

Step 7:
Apply Median Filter using cv2.medianBlur().

Step 8:
Apply Laplacian Sharpening using Kernel with cv2.filter2D().

Step 9:
Convert image to grayscale and apply Laplacian Operator using cv2.Laplacian().

Step 10:
Display all filtered images using a grid layout for comparison.

Developed By
Name: _YUUVASRI R______________________
Register No: ____212225230313__________________

# Output
Smoothing Filters
Averaging filter produces blurred image
<img width="958" height="352" alt="Screenshot 2026-11-04 082722" src="https://github.com/user-attachments/assets/9a030e8c-07e3-46be-9886-741baaa6166e" />

Weighted averaging provides smoother result with less distortion
<img width="726" height="460" alt="Screenshot 2026-11-04 082734" src="https://github.com/user-attachments/assets/ededf5b6-7713-4c15-b9a1-22bf5bd61eee" />

Gaussian filter preserves edges better while reducing noise
<img width="660" height="463" alt="Screenshot 2026-11-04 082741" src="https://github.com/user-attachments/assets/20c9a903-acca-4e9c-93ab-710d29e9984e" />

Median filter removes salt-and-pepper noise effectively
<img width="598" height="447" alt="Screenshot 2026-11-04 082752" src="https://github.com/user-attachments/assets/f487d5b7-8b4e-40e5-b200-a1037408e828" />

Laplacian kernel enhances edges and fine details
<img width="610" height="465" alt="Screenshot 2026-11-04 082758" src="https://github.com/user-attachments/assets/65595096-35a6-45d6-99d9-9c2874c2ecbe" />

Laplacian operator detects edges clearly in grayscale
<img width="653" height="450" alt="Screenshot 2026-11-04 082805" src="https://github.com/user-attachments/assets/54296f3f-748b-4251-a95b-af960ec36563" />


# Result
Thus, smoothing filters and sharpening filters are successfully implemented using OpenCV.

The smoothing filters reduce noise and improve image quality, while sharpening filters enhance edges and details for better feature extraction.

# Canny-Edge-Detection

# Aim

To write a Python program using OpenCV to perform **Canny Edge Detection** on images without applying Gaussian Blur.

# Software Required

- Anaconda - Python 3.7 or above  
- OpenCV library (`opencv-python`)  
- NumPy library (`numpy`)  
- Matplotlib library (`matplotlib`)  
- Jupyter Notebook or any Python IDE (e.g., VS Code, PyCharm)

# Algorithm

I) Load and Display the Image  

**Step 1:** Import necessary libraries: `cv2`, `numpy`, and `matplotlib.pyplot`  
**Step 2:** Read the input image using `cv2.imread()`  
**Step 3:** Convert the image to grayscale using `cv2.cvtColor()`  
**Step 4:** Display the grayscale image using `plt.imshow()` with `cmap='gray'`



II) Perform Canny Edge Detection  

**Step 1:** Use `cv2.Canny()` function to detect edges in the grayscale image  
**Step 2:** Set two threshold values (e.g., 100 and 200) for detecting strong and weak edges  
**Step 3:** Display the edge-detected image using `plt.imshow()` with `cmap='gray'`



III) Display and Compare Results  

**Step 1:** Display both the original and edge-detected images using Matplotlib subplots  
**Step 2:** Label each subplot for clarity  
**Step 3:** Use `plt.show()` to display the results

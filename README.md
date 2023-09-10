# 1. Python Library 
### opencv-python
https://pypi.org/project/opencv-python/#history
> pip install opencv-python==4.2.0.34
### numpy
https://pypi.org/project/numpy/#history 
>pip install numpy==1.18.1
### imutils (Boosting FPS)
> pip install imutils

# 2. Steps for Scanning Method 
- First, get original colored frame images
- Second, transform the colored images into grayscale images
- Third, apply an algorithm to detect edges from the grayscale images
# 3. Steps for Finding Document 
- Apply countours to the grayscale images
- Find the countours with the biggest area
- Warp Perspective to get the full frame of the document
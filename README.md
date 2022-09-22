# Air-Canvas
Computer vision project implemented with OpenCV

Here Colour Detection and tracking is used in order to achieve the objective. The colour marker in detected and a mask is produced. It includes the further steps of morphological operations on the mask produced which are Erosion and Dilation. Erosion reduces the impurities present in the mask and dilation further restores the eroded main mask.

# Algorithm

1. Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection)
2. Prepare the canvas frame and put the respective ink buttons on it.
3.. Adjust the trackbar values for finding the mask of coloured marker.
4. Preprocess the mask with morphological operations.(Erotion and dilation)
5. Detect the contours, find the center coordinates of largest contour and keep storing them in the array for successive frames .(Arrays for drawing points on canvas)
6. Finally draw the points stored in array on the frames and canvas .

**P.S Make sure to have plain background while setting up your contour (your air stylus/air pen etc..) and have your contour in Red/Blue/Green primary color for better perfomance**

Requirements: python3 , numpy , opencv installed on your system.

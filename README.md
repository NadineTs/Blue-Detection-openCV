# Blue Color Detection with OpenCV

## Overview

This project uses OpenCV to detect blue areas in an uploaded image and draw green rectangles around them. The process involves converting the image to the HSV color space, applying a color mask, and finding contours to highlight the detected areas.


## Code Explanation

- **Import Libraries**: The necessary libraries (`cv2`, `numpy`, and `files` from `google.colab`) are imported.

- **Image Upload**: The user is prompted to upload an image file using `files.upload()`.

- **Image Processing**:
  - The uploaded image is read and converted from BGR to HSV color space.
  - A mask is created to isolate blue colors based on defined HSV ranges.
  - Contours are detected in the mask.
  - Rectangles are drawn around the detected blue areas using the bounding rectangles of the contours.

- **Display Results**: The final image with rectangles is displayed using `cv2_imshow()`.


## Example Result
Here is an example of an image processed by the code:

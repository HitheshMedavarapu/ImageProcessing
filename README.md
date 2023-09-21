# ImageProcessing
This project is completed under the guidance of Prof. Michael Curry. The main objective of this project is to create a model with different filters. Each key corresponds to each filter.

## Filters used
GrayScale filter (press G) <br>
Threshold filter (press T) <br>
Skin Detection (press S) <br>
Edge Detection (press E) <br>
Blurring using kernel (press B) <br>
Sharpening using kernel (press X) <br>
Face Detection using haar-cascade (press F) <br>
Contour Tracking (press O) <br>

### Note:
For face detection, you have to change the path of python libraries as the opencv libraries may have located in a different loacation in your device.
For the location, run the following commands and replace the path. <br>
import site
print(site.getsitepackages())

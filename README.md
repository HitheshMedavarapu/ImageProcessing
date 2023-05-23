# ImageProcessing
This project is completed under the guidance of Prof. Michael Curry. The main objective of this project is to create a model with different filters. Each key corresponds to each filter.

## Filters used
GrayScale filter (press G)
Threshold filter (press T)
Skin Detection (press S)
Edge Detection (press E)
Blurring using kernel (press B)
Sharpening using kernel (press X)
Face Detection using haar-cascade (press F)
Contour Tracking (press O)

### Note:
For face detection, you have to change the path of python libraries as the opencv libraries may have located in a different loacation in your device.
FOr the location, run the following commands and replace the path.
import site
print(site.getsitepackages())

# VRPaint
USES:
* OpenCV,
* Mediapipe libraries

The main idea is:   
* Detect hands using mediapipe
* Detect wheither the index and middle fingers are up
* Detect fingers' tip location
* Draw a line when only the index finger is up and make a sellection when both index and middle fingers are up
* Draw on a black canvas then mask it with actual frame   

# Installation
There are some prerequisites that are needed to be done to be able to run this project.
It's needed to install the required libraries by running the following commend in the project's directory:
```bash
pip install -r requirements
```
now you can run the project directly from your terminal:
```bash
python main.py
```
If everything has gone right, a window will  pop up as in the below figure:


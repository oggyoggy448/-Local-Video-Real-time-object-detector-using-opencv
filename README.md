# (Local Video) Real-Time-Object-Detector-using-Opencv
A real time object detector using opencv 4.1.1.26 

## Important Note 
you need to place a video in this project folder 
and replace the name of that file with "v.mp4" in a main.py file. 
It is a line number 35. 

## Requirement
1. python 3.7 
2. Anaconda (recommended)
3. opencv-python 
4. imutils 

## Run the project 
1. Install Anaconda and create a virtual environment
2. Install all libraries mentioned in requirement.txt file
3. Run the main.py file using the following command 

`python main.py \
	--prototxt MobileNetSSD_deploy.prototxt.txt \
	--model MobileNetSSD_deploy.caffemodel`
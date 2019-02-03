# motiondetector_opencv
Detect any moving object in camera and mark it on the frame and record its in and out time and plot a graph, using opencv and python.

We often come to a problem where we need to detect moving objects from a camera. 

What all you need ?
Python — Installed in Windows
PIP Installer (Mostly come along with Python installation package)
OpenCv — Python : For reading video/frames from camera 
NumPy : For converting pixels captured from OpenCV into Numpy Array
Pandas : For creating data frames and Loggin the timing into a .csv file
Bokeh : For plotting the graphing using data frames created by Pandas
And it the end of course we need a Python IDE, well I am using PyCharm for this.

So how we are going to achieve it ?
All we need is to detect moving objects in a video stream(source being camera here).
What is a video ? It’s nothing but multiple images or frames which are displayed very quickly.
So using OpenCV, we will capture the frames and will loop through each frame so that it appears like a video.
To detect the moving objects, we will store the first image as the base frame and then with each further frames 
we will keep on substracting the frames, so that if at any point of time there is a difference b/w the two frames 
it means there is a new object in our frame.


For Complete explanation go to this link : 
https://medium.com/@anshurajlive/creating-motion-object-detector-using-opencv-and-python-on-windows-38a15b23f468


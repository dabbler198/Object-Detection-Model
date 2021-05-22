# Object-Detection
This program takes the very first frame as a refernce frame then it detects an object by taking the difference between new frame (takes new frame in every 1 milisecond) and the initial frame. 
Whenever an object of size greater than size 1000 pixels (to reduce noise) comes into the camera's frame it detects the object and stores the object's entrance and exit time in a file.
The motive of this model is to reduce the efforts and time of finding useful information from a normal CCTV camera.
With this model we can simply go to the timestamps stored in the 'times' file and check who entered the frame and when instead of traditional method of going through the entire footage. 
This will reduce our time of doing this process by manifold fractions.

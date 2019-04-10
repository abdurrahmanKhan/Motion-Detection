# Motion-Detection
Computer Vision intrigues me, thus after the face detection project, I decided to make something for security reasons.

This project is about Motion Detection. In this project, the presence of an object is recorded and saved to a file which is plotted on a graph so that it can be viewed later.
This find its uses in various security reasons.

----------------------
How it is implemented
----------------------
The approach I followed to achieve this is simple.

The idea is to fix and record the first frame and pixel values and then check for any change in them by calculating the difference.
And for the intensity of pixel I set a threshold so that after a crtain point it recognizes that something is moving inside the frame and detects and it starts recording the time and date and as soon as the object is gone from the frame it stops. 
And the time and date is saved into a CSV file which can be viewed later. And also the data is plotted on an interactive graph which can be viewed.

This has many uses in security and keeping track of things.

# Game_Control-master
This is a mini project on Python &amp; OpenCV. It simulates a real life like steering wheel control for Car racing games on Windows.
Experience the fun of playing racing games using a self draw/made steering wheel.

#### Requirements
* python 3.x
* imutils
* numpy
* opencv-python
* Colorful hand drawn steering wheel

I have created a program to detect Blue objects in a frame. Logically divided the frame into four regions. The upper left region is used for turning the vehicle left and upper right region is used for turning right.
The lower region is divided into "UP" and "DOWN" which are used for acceleration and break respectively.

This is a simple concept of controlling W,A,S,D keyboard keys and can be used for other keys as well as other games.

![Screen Shot of Gameplay](/images/Screenshot1.png)

The color detected can be modified by changing the HSV range values in controlling_steer.py. 
color.py can be used to find the hsv values of any color object you wish to use .

Below is the youtube link of the demonstration of this entire project. Please have a look !
[Youtube Link](https://www.youtube.com/watch?v=NyeHKRjW5a0&t "Computer Vision: Game Control")

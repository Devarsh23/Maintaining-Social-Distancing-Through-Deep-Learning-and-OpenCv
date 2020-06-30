# Maintaining-Social-Distancing-Through-Deep-Learning-and-OpenCv
# This project is done by <a href="https://github.com/Devarsh23 ">Devarsh Patel</a>  And <a href="https://github.com/pruthvi03 ">Pruthvi Hingu</a>
## Table of content
[1. Demo](#demo-of-the-output) <br />
[2.The overview of this repository](#the-overview-of-this-repository) <br />
[3.Motivation behind the project](#motivation-behind-the-project) <br />
[4.To Do](#to-do) <br />
[5.Directory structure](#directory-structure) <br />
[6.Detailed Description of code](#detailed-description-of-code) <br />
[7.Special Thanks](#special-thanks) <br />



# Demo Of the output
Click here for <a href="https://youtu.be/KdOGJzS0kFA"> DEMO </a>
# The overview of this repository
Describes about the usefulness of deep learning and opencv in  maintaining social distancing in the current ongoing pandemic event where the unlock phase is executing <br />
# Motivation behind the project:
In the current ongoing pandemic event where the government is planning to start the unlocking phase. So, now some activities which were completely prohibited are now starting to do work to retain their previous working state. <br />
So, in such situation by using the technology like deep learning and open cv we can help the people in certain public area to maintain the social distancing. Hence the aim of this project is the maintain the social distancing among the people. Our system notifies with the alert message where the social distancing is not followed. <br />
# To do 
Basically, you can run the SocialDisatancing.ipynb file after cloning this GitHub repository. To test the performance of this file on the vtest.avi video file.If you wish you could add your own video and also use webcam. <br /> 
If you want to incorporate this with the outer camera the you can add the url + “/video” in the VideoCapture argument to use it on any mobile with ipwebcam or cctv camera. <br />
# Directory Structure
The directory structure here is very simple you just only need to put all the above listed files under one directory 
# Detailed Description of code
Here we have firstly trained ssd model which can detect 15 items which are present in label file. After that detecting person and filtering it as a class id of 15 we based on the focal length of the camera calculate the depth of the person detected. The depth of a person is detected with the help of triangulate similarity. considering the depth as a parameter euclidian distance between two detcted person is calculated and if distance falls below thresholf limit the red bounding box with the alert message is displayed.
# Special Thanks
We would like to thanks krish naik and shubhiksha for encouraging us to do such a lovely project




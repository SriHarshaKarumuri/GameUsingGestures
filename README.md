# GameUsingGestures

Hi All,
Please Read Whole File

Introduction

    This is a program to control our movements with the help of object tracking.This can be used to control any game with a set of keys we want to use.
    In This Program there are only 4movements like ( up,down,right,left )only ,you can add/Change the program with your customized movements.

Description :

      We used mainly 3 packages from python 
      1) OpenCV  - for object tracking
      2) PyAutoGui - for keypress or binding
      3) Time

      There are various trackers available in opencv to track the movement :
          BOOSTING Tracker
          KCF Tracker
          MIL Tracker
          TLD Tracker
          MEDIANFLOW Tracker
          GOTURN tracker
          MOSSE tracker
          CSRT tracker
      Every tracker has its own functionality , advantages,disadvantages you can know them in python documentation section.
      In this program we used **CSRT Tracker** it supports low frames but it detects object movements accurately.
      Note: This Trackers have been moved to another package called OpenCvLegacy so if you use you will get a error that **cv2.TrackerCSRT_create() has no attribute         tracker**
      So the solution is mentioned on line 


How to Use
      1)Firstly make sure that you install all the above mentioned 3 packages in your local system.
      2)For Problem Mentioned In Line 29 - Goto Path of your Python Scripts Folder like (C:\Program Files\Python310\Scripts)-Path may be differ in your local system         and depends on where you store but this will be a common subpath-(Python310\Scripts) and Run/Start A Command Prompt there and type the following code:
      pip install opencv-contrib-python==4.5.5.62  it will install packages.
      3)A photo will be clicked from your webcam 
        Select the area in the image clicked that  you wish to track
        Click enter now and a live webcam video window is opened which tracks you and prints the movements on shell according to your postion coordinates
        You can press 'q' to stop the program.
Example:
1)Run Program 
2)Open Cascade Windows and open chrome and enter  https://www.kiloo.com/subway-surfers/
See the Magic .......!!!!!!

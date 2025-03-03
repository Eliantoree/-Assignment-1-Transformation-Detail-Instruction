# -Assignment-1-Transformation-Detail-Instruction
 Assignment 1 – Transformation Detail Instruction

Download  Link :https://programming.engineering/product/assignment-1-transformation-detail-instruction/

Description
5/5 – (2 votes)
Goal

Interact with five model (independently)

Control the camera

Implement transformation, viewing, and projection matrices (MVP)

Switch between 5 models

Switch between solid and wireframe mode

Finish all the TODO in main.cpp and vertex shader

Keep scene ratio when window reshaped

Add floor plane in world scene

◆ …

2


Assignment 1

Announce date:

Late work will be penalized by 20/week.

Copy & paste others’code will get 0.

Hand in your homework to eeclass in the following form (-5 for penalty)

studentID_HW1.zip

studentID_HW1_Report.pdf


In studentID_HW1.zip

Depend on your device

x64 資料夾可以不用上傳

For Windows For Mac


Submission Guide

◆Please submit to course webpage at NTHU eeclass system

Notice: E-mail submission will not be accepted

◆Submission should include

Source codes (including solution and project files)

Executable binary (can be run on PC/windows)

Documentation (explain how you did it and how to operate it)

Notice: please do not submit any 3D models to save the disk space

◆Contact with TAs if you have problem in submission

5


Key Mapping

Please follow the spec bellow, or you would not get the score of item.

You must make sure your key mapping is exactly same to ours.

W: switch between solid and wireframe mode

Z/X: switch the model

O: switch to Orthogonal projection

P: switch to NDC Perspective projection

T: switch to translation mode

S: switch to scale mode

◆ R: switch to rotation mode

6


Key Mapping

E: switch to translate eye position mode

C: switch to translate viewing center position mode

U: switch to translate camera up vector position mode

I: print information

Translation Matrix, Rotation Matrix, Scaling Matrix, Viewing Matrix, Projection Matrix


Key Mapping

If you switch mode by T, S, R, E, C, and U

Apply change on Z axis when scroll the wheel

Apply change on X axis when mouse drag horizontally

Apply change on Y axis when mouse drag vertically

Only rotation should apply X axis when mouse drag vertically, and Y axis when mouse drag horizontally


Report

Some screen shot

Description of your program control instructions

Other special things you have done


Grading Policy

Item

Score

Correctly render model in Orthogonal projection

10%

Correctly render model in NDC perspective

5%

Translation, Rotation, Scaling models

30%

Camera Control

30%

Switch models (5 models in Line 566 of main.cpp)

5%

render quad

5%

Switch between solid and wireframe mode

5%

Print information

5%

Window resize

5%

Report

5%

Total

105%

10

Reference

Event handlings

Tinyobj loader

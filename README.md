# Pedestrian-and-Lane-Detection-Image-processing

## ABSTRACT

Self Driving cars have continued to be in the limelight for a couple of 
years and even now when technology giants like Uber, Lyft, Apple 
and manufacturing giants like Volvo, Toyota invest heavily they must 
be worth a huge treasure. Self driving cars can solve a lot of 
problems we face on roads. Delay due to traffic, vehicle collision 
which ultimately leads to road rage as we experience and the ever 
growing noise pollution. 
Self driving cars could provide us with the ultimate freedom to drive. 
Imagine not having to worry about which route to take to reach our 
destination faster, and above all with the supreme experience to sit 
back and be free or continue with our work. Time efficiency if we take 
into account could free us from the necessary task of having to drive 
and could reduce the time we waste in commuting. 
Apart from all the good the Self Driving vehicles boast of there is still 
a question about pedestrian safety. How and what better technologies 
can be equipped to ensure pedestrian safety remains the need of the 
hour. This project aims to be solving this problem by adopting use of 
several transformation techniques for providing a finite lane path for 
smooth commute of the self driving cars.

## INTRODUCTION

Traffic accidents have become one of the most serious problems in 
today's world. Roads are the mostly chosen modes of transportation 
and provide the finest connections among all modes. Most frequently 
occurring traffic problem is the negligence of the drivers and it has 
become more and more serious with the increase of vehicles. 
Increasing the safety and saving lives of human beings is one of the 
basic function of Intelligent Transportation System (ITS). 
There are still questions about the safety of pedestrians traveling or 
crossing the road or how would a Self Driving Car perform a smooth 
commute from 2 different points. These road accidents can be 
reduced with the help of road lanes or white markers that assist the 
driver to identify the road area and non-road area and also detecting 
the pedestrians crossing the roads.
In this project we are going to solve this problem of pedestrian and 
road lane detection for self-driving cars using various image 
processing techniques. 
We will be using HOG (Histogram of Oriented Gradients) for the 
detection and Kalman Filter for tracking and prediction of pedestrians. 
For lane detection, Bilateral filter will be used for reducing noise 
followed by edge detection and mapping of these edge points in finite 
lines for lane detection using thresholding and Hough transform .

## ARCHITECTURE DIAGRAM

![image](https://user-images.githubusercontent.com/58622363/178473814-29af57ee-c206-4259-bd47-f9fb371abc3e.png)

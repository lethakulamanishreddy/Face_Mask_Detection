# Face-Mask-Detection
This repository contains Face Mask Detection project made with python and basic imageprocessing

## DEMO

https://www.instagram.com/p/CCxj2m5jtE1/?utm_source=ig_web_copy_link


https://youtu.be/0C0iogC7n5Q


## Requirements
1.OpenCV\
2.Numpy\
3.Haarcascade files

In this project we will use basic opencv and haarcascades file to detect wether a person is wearing a mask or not.

## Working
If a person is not wearing mask then we can find his face as well as we can detect his mouth.\
if a person is wearing a mask then we can find his face but we cannot detect his mouth.
  
  | Face | Mouth |Mask|
  | --- | --- | --- |
  | 1 | 0 | YES |
  | 1 | 1 | No |
  
Using this logic we can determine if a person is wearing  mask or not.

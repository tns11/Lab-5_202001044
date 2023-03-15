# Lab 5 - Static Analysis


Name: Soni Tarang Nileshkumar

Student ID: 202001044

Course: IT314 - Software Engineering

Lab: 5 

Title: Static Analysis

---------------------------------------------------------------------------------------------





Selected Tool: Pylint

Reason → Has many features over other tools.


<h1>Errors in file: </h1>

Source:  https://github.com/MSTC-DA-IICT/Hacktoberfest22-Python-2


import numpy as np
-> from tkinter import *
from PIL import Image


ITERATIVE = 0
A_STAR = 1


 Error displayed: Wildcard import tkinter
-> This error is a valid error. The developer imported the whole library rather than just the required modules, which would unnecessarily increase the time of execution and size of project.




References:
  1.https://www.geeksforgeeks.org/pylint-module-in-python/

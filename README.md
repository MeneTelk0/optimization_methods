# Optimization_Methods
<p float="left">
<img src="https://img.shields.io/badge/Language-Jupyter notebook-blue" alt="alt text">
<img src="https://img.shields.io/badge/license-MIT-green" alt="alt text">
</p>

Course taught at MIPT devoted to the study of optimization methods.

## Overview
Here you can find implementation of __Projected Gradient Decrease__ method. You can use it to find the minimum of parabolic functions of two variables with linear constraints.

Minimization problem taken as an example for this program:

<img src="https://github.com/MeneTelk0/optimization_methods/blob/master/gitfiles/min.png" width="400">

## Results 
The results of program work are shown on the contour plots. Depending on how far the points were from the minimum of the function, we can see different patterns of movement to a minimum.  Moreover, this movement always occurs along the boundary of the admissible region of the function, which corresponds to the work of the projected gradient method.
- First picture - __[2,2]__ -> __[1,4]__ -> __[1,4.5]__ -> __[1.33, 4.66]__ 
- Second picture shows case with start point __[2,3]__ -> __[2.2,3.8]__ -> __[1.33, 4.66]__ 

<p float="left">
<img src="https://github.com/MeneTelk0/optimization_methods/blob/master/gitfiles/first.png" width="400">

<img src="https://github.com/MeneTelk0/optimization_methods/blob/master/gitfiles/second.png" width="400"> 
</p>

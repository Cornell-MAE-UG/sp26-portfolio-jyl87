---
layout: project
title: OLHW 5a 
description: Nutcracker Design Problem
technologies: [MATLAB, python]
image: /assets/images/function-graph.png
---
1. The problem statement and objective ("Find")
Design Problem: Imagine you have a macadamia nut that you want to crack open by hand using a simple lever nut cracker.
Design a nutcracker to make this task feasible, assuming simple geometry.

2. Constraints and Input parameters ("Given")
Assumed values:
Wp = vertical distance from pin to force from contact with nut = 1.5 in.
Fh = max human hand grip strength = 539 N
Lm = horizontal distance from pin to point of contact with nut = 1 in. 
Ny = avg load to crack macadamia nut = 2177.364 N 

5. Your approach to the problem (e.g. calculations, assumptions made, your thought process, etc.)
Assumptions: 
- Only force from the nut is in the vertical direction, same with the force from the hand (Fh)
- L = 2Lm 
- Force from hand is applied some distance from the edge of the handle (more realistic) 
- The two halves of the nutcracker is attached by a simple pin that creates reaction forces in x and y directions 
- 2D equilibrium 
- The nut is a sphere with one point of contact with the nutcracker on either side 

Thought Process: 
Thought Process: 
The moments between the force from the hand and the force from the nut will give a ratio between their respective distances from the pin. This ratio, after assuming a reasonable value for Lm, can be used to calculate the longer length of the nutcracker. 

Calculations:
![Solution](assets/olhw5image1.png)

6. A diagram of your nut cracker design. This doesn't need to be fancy, but should be intelligible.


7. Discussion on usability of design.
The original design would have been too small for the average human to hold and still crack open the nut. In the redesign, using a larger force, there will be a longer handle to improve usability. 

Additional Work Shown Below: 


```python
    some code = 10;
    plot();
```
![Reflection](assets/olhw5image2.png)




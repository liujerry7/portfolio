# Jerry Liu
![Profile](jerry.jpg)
I am a sophomore majoring in Electrical Engineering with a minor in entrepreneurship at University of Michigan. Some of my previous projects were related to robotics, embedded systems, and machine learning. I am currently interested in learning more about embedded systems.

## Education
University of Michigan, B.S.E in Electrical Engineering

## Projects
### Dual Axis Solar Tracker Fall 2017
![Solar Tracker](solartracker.jpg)

I made a dual axis solar tracker using Arduino components. Our team 3D printed a cross to use shadows as a way to track light by placing four photodiodes in each section of the cross. If the difference in light received from the photodiodes exceeds a threshold, the horizontal axis or vertical axis servo would spin in the appropriate direction. I specifically worked on power optimization. Instead of incrementing the servo movement 3 degrees every loop, I changed the code to move proportional to the difference in light. The farther the solar tracker was from light, the farther the solar tracker would move. 

| Before Power Optimization | After Power Optimization |
| --- | --- |
| ![Solar Tracker Before Optimization](solartrackerbefore.gif =300x1000) | ![Solar Tracker After Optimization](solartrackerafter.gif=300x1000) |

### Mars Rover Motor Controller

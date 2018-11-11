---
layout: post
title:  "Sailbots: Optimizing Hull for Scale Testing"
tags:
  Sailbots
  3D-Printing
hero: https://source.unsplash.com/collection/145103/
overlay: orange
published: true
---

Over the last couple of weeks, I have been working with the rudder foil subteam to finalize the rudder foil and skeg design.  In order to verify our design, we have decided to use UBC's Parkinson Wind Tunnel to test our design. We are going to find our drag and life coefficents, our Reynold's number for each of our designs and flow visualizations. We are doing intensive testing on our design in order to prevent unwanted vortexes and flow which will lower the effectiveness of our rudder.  

I am going to recieve training to use the Parkinson's Wind Tunnel at [UBC's Areolab](http://mech.ubc.ca/aerolab/facilities/) this Thursday.  

Of course, no testing would be complete -or accurate- without some calculations before hand.

**Testing Scale and Wind Speeds**

In order to calculate our model size and wind speed needed, we equated two Reynolds numbers - for air and for ocean water - and found what we need for our fluid simulation.  

We used the following formula to calculate our Reynold's number:

> Reynold's number in the ocean = ρvL/μ = Reynold's number in air (with scale model)
>
> Where:
> ρ = density of ocean water
> v = estimated velocity of the sailboat
> L = actual chord length of rudder foil
> μ = dynamic velocity of ocean water 

We established a proportionality with velocity at a set scale with different "ρ" values to determine the wind speeds we need to achieve. 
At 20% scale and the maximum wind speeds of 30 km/h of the Parkinson Wind Tunnel, we can only simulate near stalling speeds.  In order to find our Reynold's number at realistic sailing speeds, we will find our drag and lift coefficents (since they are linear up until the stalling point) and extrapolate our Reynold's numbers on there.  

In addition to real-life testing, I will test our designs on ANSYS to compliment and add on to our real-life testing.  

**3D Printing the Scale Model**

3D printing the scale model is a challenge itself.  Given that the largest print I have ever done was 12 hours long, this project will take up 4 times as long! Such a large print -even if it is in pieces- has a very high failure rate.  In order to reduce the fail rate of the print, I will eliminate overhangs and potentially remove support material from the model. Additionally, print times will be reduced through thin shells and low desity prints.  

To relate the scale model design to my MECH 260 course, the hull shell will be thicker with a thin shell and low density infill to maximize our moment of inertia to minimize the bending of the boat while testing.  



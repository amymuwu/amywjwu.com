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

Over the last couple of weeks, I have been working with the rudder foil subteam to finalize the rudder foil and skeg design.  In order to verify our design, we have decided to use UBC's Parkinson Wind Tunnel to test our design. We are going to find our drag and life coefficents, our Reynold's number for each of our rudder foil and skeg designs and flow visualizations. 

I am going to recieve training to use the Parkinson's Wind Tunnel at [UBC's Areolab](http://mech.ubc.ca/aerolab/facilities/) this Thursday.  

Of course, no testing would be complete -or accurate- without some calculations before hand.

## Testing Scale and Wind Speeds
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

# Autonomously Following Forest Paths with a Mobile Robot using Semantic Segmentation

This project is [Pieter Fiers](https://pfiers.net) and
 [Simon Germeau](https://github.com/GermeauSimon)'s professional bachelor's thesis for [UCLL](https://www.ucll.be/)'s [Aplied Informatics degree](http://onderwijsaanbod.leuven.ucll.be/opleidingen/n/SC_52335187.htm).

We created a rover that is capable of autonomously following forest paths. 

We used a Semantic Segmentation CNN, as opposed to the classification CNN 
used by Giusti et al.[^1] and Smolyanskiy et al.[^2]. We believe this enables 
interesting future expansions, like higher-level decision making about path 
intersections, and the mapping of road geometries.

<video width="100%" controls>
    <source src="intro.webm" type="video/webm">
</video>

## Repository structure

The repository is structured according to the four main stages of our project:

[Dataprep](dataprep) - Documentation about, and the scripts we used for, the processing and labelling 
of data used for training.

[Model](model) - This folder contains the machine learning process we used to train our CNN.

[Rover](rover) - Documentation regarding the hardware aspect of our rover.

[ROS](ros) - All documentation, ROS nodes, and extra files needed to make the rover drive
itself.

ROS is the "[Robot Operating System](https://www.ros.org/)". See 
"[About ROS](ros/about-ros)" for more about why *we* use ROS.

<br>

[^1]: Smolyanskiy et al., “Toward Low-Flying Autonomous MAV Trail Navigation using DeepNeural Networks for Environmental Awareness” May 2017.  
[^2]: Giusti et al., “A Machine Learning Approach to Visual Perception of Forest Trails for Mobile Robots” Dec 2015. 
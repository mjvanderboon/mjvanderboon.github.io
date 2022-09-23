---
title: "System Identification for an autonomous drone"
excerpt: "For my bachelor's thesis, my project group performed system identification for an autonomous drone<br/><img src='/images/drone_resized.png'>"
collection: portfolio
---

My bachelor thesis was focused on system identification for an autonomous drone. I was responsible for running the data acquisition experiments and processing pipeline. The experiments took place in the motion capture facility of the Delft Center for Systems and Control. Using a ROS stack we recorded input commands and output pose of the drone. The captured data was processed using MATLAB to perform system identification. 

This project was a good first introduction for me to ROS and data capture & processing at scale. The video below shows a nice visualisation of our final results. The white drone represents the actual, captured data. The coloured drones are various model orders we fit. I rendered this video from our captured data using the Blender Python API.

<video width="640" height="480" controls>
    <source src="/images/drone.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
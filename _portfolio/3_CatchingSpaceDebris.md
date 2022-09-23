---
title: "Catching Space Debris using Reinforcement Learning"
excerpt: "During my master's, I worked on a project involving reinforcement learning and catching space debris.<br/><img src='/images/space_debris_resized.png'>"
collection: portfolio
---

This project was performend in the Robotic Systems Lab at ETH Zurich. The project revolves around the problem of cleaning up space debris. Over the years, massive amounts of debris have accumulated in space, greatly increasing the risk of collisions occuring. 

Earlier work by ESA already proposed using a chaser satellite with a robotic arm to capture delirict satellites and push them back to earth to burn up in the atmosphere. However, the project was defunded partly due to expected difficulties in desinging a controller for the capturing phase.

In this project I trained a reinforcement learning policy that is capable of tracking a rotating target satellite. The video below shows the policy performing on four example targets. The policy was trained in IsaacGym using PPO.

<video width="640" height="480" controls>
    <source src="/images/space_debris.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
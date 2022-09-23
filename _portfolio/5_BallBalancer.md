---
title: "Ball balancer"
excerpt: "A project during my bachelor where I was responsible for perception and control.<br/><img src='/images/ballbalancer_resized.png'>"
collection: portfolio
---

In this project my group and I designed a ball balancing structure. The structure consists of a platform actuated using linkages to two servos. The platform is filmed using a camera connected to a Raspberry pi. I was in charge of perception and control. Specifically, I wrote a python application that tracks the ball position on the plate using OpenCV. The ball is localized with respect to the platform using coloured stickers on the corners of the platform. The tracked position is sent to an Arduino which is used to control the servos. The control scheme is a hand-tuned PID. 

Looking back on this project, I think it's great to see how many things I would do differently. For example, the tracking solution depended on configuring the RGB color of the calibration stickers exactly. This means that under different lighting conditions, the tracking would fail completely. Now, I would most likely use a ROS stack combined with redundant apriltags on the platform.

The video below shows the ball balancer in action. Over the years, compression unfortunately took its toll on the video quality.

<video width="640" height="480" controls>
    <source src="/images/ballbalancer.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
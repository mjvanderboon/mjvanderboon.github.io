---
title: "Deep Learning Augmented Avatars"
excerpt: "At TNO, I worked on deep learning augmented avatars for VR applications. My work was published to the ACM Conference on Interactive Media Experiences (IMX 22).<br/><img src='/images/style_transferred_eyes_resized.png'>"
collection: portfolio
---

During my internship at TNO, the Netherlands Organisation for Applied Scientific Research, I worked on deep learning augmented avatars for VR applications. I gained experience developing deep learning models from scratch and integrating them for inference in real-time pipelines. A paper describing the pipeline was published to the ACM Conference on Interactive Media Experiences (IMX 22). I presented the paper on the conference in Aveiro, Portugal in June 2022.

<img src='/images/rendering_overview.png'>

My work consists of a GAN based VR headset removal system for teleconferencing applications. The pipeline consists of a blendshape-based avatar combined with two deep learning improvements. The first improvement module runs ofine and improves the texture map of the base avatar. The second module runs inference in real-time at the rendering stage and performs a style transfer to the avatar’s eyes.

The style transfer module is integrated into Unity using the Unity Barracuda package. The deep learning models were all written in PyTorch.

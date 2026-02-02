---
title: Automated Optical Produce Grader
date: 2025-09-01
---

The latest project I worked on was an automated optical produce grader for a local potato farm. The goal was to assist in finding defects on the potatoes as they were travelling down the production line and automatically track and kick them out of the line for seperate processing. The system used industrial machine-vision cameras to send high volume data back to a computer running our custom software.

We used various types of machine-vision algorithms and machine-leaning models to detect the defects on the potatoes. Given a large amount of training data from cameras placed above the line, we were able to create custom training datasets and use them to train our models on powerful local hardware. Once a defect was found we needed to track the potato accross the camera and kick it as it was falling through the air. I was lucky enough to be able to work with a brilliant team of engineers to bring this project from and idea into reality and it is currently in production.

![Potato Grader](/potato/IMG_2385.jpg)

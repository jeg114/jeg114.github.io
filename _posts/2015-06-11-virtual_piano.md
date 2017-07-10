---
layout: post
section-type: post
title: FPGA Virtual Piano
category: University
tags: [ '2017', 'FPGA', 'CV' ]
---
As part of my first year at Electronic and Information Engineering we had to complete in pairs a year project which was as fascinating as challenging. The most interesting aspect of this project was that we had to design the project on our own. The only constraints given were that demonstrate knowledge of pipelining and parallelism using a Terasic DE0 board with a Cyclone III FPGA, a camera extension for it and a VGA controlled screen. We were also given as tools the programs Quartus and Calypso Catapult. 

Since both my partner and I had studied music during high school and we both wanted to develop something we felt identified with, we decided to create a virtual piano. The camera would be placed perpendicular to a paper sheet placed on a table with a printed keyboard. Through the FPGA circuit we would then identify the keyboard and fingers to be placed on it through edge detection. Finally we would display the same image captured by the camera but changing the color of the key being played and using a loudspeaker to play the appropriate note.

During the actual implementation we faced many challenges. We had to totally discard a first approach using colored keys which made us lose a lot of time. Producing the sound was also a great challenge, and we had to look into a second year course and lab information to use an ADC extension we asked for in labs. This also involved learning Verilog on our own. Nonetheless we managed to overcome all the challenges and achieve our goals, which was very satisfying. Moreover we received great feedback from our supervisor who encouraged us to submit a video describing the problem for reference for future students which can be found here: 

**Video Explanation and Demo**
<iframe width="560" height="315" src="https://www.youtube.com/embed/T1z6UT_jo7w" frameborder="0" allowfullscreen></iframe>

**Quick Demo**
<iframe width="560" height="315" src="https://www.youtube.com/embed/Pd8RWCv_f2U" frameborder="0" allowfullscreen></iframe>

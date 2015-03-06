ROBOPET
==============

Originally written for Build18 2015 - this code defines Interaction States based on emotional and physical cues from a user.

Built off demo code for the Kinect, but adapted to include more information and make inferences about whoever is interacting with it. 

Additionally, the states are encoded to single character strings serially output to a laptop or other connected device. 

STATES
---------------
1 - ATTENTION

2 - MOVE FORWARD

3 - MOVE BACKWARD

4 - MOVE LEFT

5 - MOVE RIGHT

6 - HAPPY

7 - DO A TRICK

0 - IDLE

GETTING STATE INFO
-----------------------

The state encoding is output via the Kinect serial port to a laptop. The laptop can pass that information on to any device, which can choose its own method of response. I specifically chose to leave the output as independent as possible so the code could be adaptable to future projects. 

We opted to simply use the laptop as an interface that directly talked to Arduino code running on the laptop. The robot was controlled wirelessly via RF transciever. 

# Sainsmart-Instabot-V2
Contains the documentation and source code for the Sainsmart Instabot V2 kit.

According to the one instructional video, the values for the PID controller algorithm are likely to be around:
https://www.youtube.com/watch?v=pD8i5554cuc&feature=youtu.be

kp = 17
kd = 840
ki = .1

Unlike the video, the latest software supports three potentiometers allowing for each value to be adjusted on the fly.

# Tips and tricks
* If your robot falls violently over, reverse the polarity of the drive motors so that the rotate in the opposite direction to counter the topple.
* If your robot wheels rotate in opposite directions, reverse the polarity of one of the motors
* If the kp, kd and ki parameters don't respond to the potentiometers:
** Solder thicker legs to the potentiometers so they make better contact with the shield.
** Verify that the ARef pin on the shield isn't shorted to ground.  On the shield I got the ARef and GND pin seemed to be reversed so I snipped them off.

# Future improvements
* Self calibration of the PID control values
* Adjustment of the PID control values from the remote

# 2018-FRC-Robot-Code

### What is this Repository?
This repository contains code that I wrote during the [First Robotics Competition](https://en.wikipedia.org/wiki/FIRST_Robotics_Competition) 2018 season working with team 6934. Over six weeks I was tasked with learning the WPILIB 
and the CTRE libraries to program CAN motors, PWM motors, and Pneumatic Cylinders for the competition. Although the
initial creation of this code was created under extreme time limitations, I have gone back to document the code with Javadoc. I 
hope that this code will assist any future members of team 6934, looking back for inspiration. Additionally, as I continue to
become a more knowledgable software engineer, I hope to document my growth and lessons learned on my first forray into the world
of robotics.

### What was the purpose of the robot?

FRC presents a new challenge each year, with 2018's game being "Power-Up". Each alliance is made of three different teams who work 
together to score more points than the other team. The first 15 seconds of each match involves the robots being controlled 
completely autonomously. Then the robots were controlled by the team (I controlled the grabbing mechanism!). The field has two 
smaller "switches" which would give you points per second if you had more cubes on your side than the opponents did on their side. 
Additionally, your robot could pass the cube through a hole on your team's side of the field and be redeemed for "power-ups" that
would grant your alliance some bonus during the match. At the end of the match, the alliance with more points wins.

![Robot Gif](https://media.giphy.com/media/Ll3TO0z1O7oCRtXcaC/giphy.gif)

### What does each part of the robot do?
The base of the robot is the drive train which used TALON SRX motor controllers with CIM motors to allow the robot to move around
the field. To score points, motors were used to rotate the arm up and down to allow the robot to lift boxes up into the switch.
To improve its ability to grab boxes, the robot had a "gripper" powered by pneumatic cylinders that would switch the intake 
between a wide-open form to approach boxes and a tight grip to hold onto boxes. At the end of the gripper were two intake wheels
which spun in or out to further imrpove intake and to allow the box to be shot out of the gripper. 

### Take-aways
Despite team 6934's rookie-status, we managed to place 9th individually at the event, awarding us the Highest Rookie Seed Award.
Competing in FRC taught me how to collaberate effectively with a team in a technical setting. My amazing experience with FRC
has led me to give back by mentoring students that are currently participating in FRC through team 6934. Ultimately, my
participation in FRC granted me hands-on experience in robotics and accelerated my learning and passion for robots.

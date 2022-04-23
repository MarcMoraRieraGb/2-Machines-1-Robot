# Robotic

This program is made with RobotStudio and has 2 machines that keep making piece, one of them every 30 seconds in a synchronous and the other asynchronous and detect de pieces with a sensor. The robot has to pick all the pieces in the most efficient way and put them in the convoyer belt and every 1min and 30sec the robot has to put the next piece on the tbale in front of the convoyer belt, after 10 seconds he has to pick it up from the table and put it in the convoyer.

For the creation of the WOrkobjects it reads the txt file called "Coordenades" which has de coordinates for the creation of 4 Workobjects, with quaternions, 2 for the machines, 1 for the transfer and 1 for the test table.

Every action is controlled by Timers that activates different Traps which makes the robot do different operations depending on which Interrupcion is activated.

 

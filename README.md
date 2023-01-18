# HelloRobot_mobile app
#### The main goal of the project is to create an android app to control mini-robot
###
#### In order to start application, you need a running SocketServer, which you can find at the link: [SocketServer](https://github.com/tora-ananas/Socket-chat-master)
## Demo

#### OUR ROBOT LOOK LOKE THAT-> 

![App Screenshot](https://github.com/tora-ananas/HelloRobot_mobile/blob/main/robot1.jpg)
###
![App Screenshot](https://github.com/tora-ananas/HelloRobot_mobile/blob/main/robot2.jpg)
###
![App Screenshot](https://github.com/tora-ananas/HelloRobot_mobile/blob/main/robotVSrobot.jpg)
###
#### When you open HelloRobot app you can see start screen where you should write IPv4-address to create a socket connection 
##### To understand which address is needed, type `ipconfig` into `command line` and check `Wireless LAN Adapter Wi-Fi: IPv4-address` 
(in my local network it is `192.168.0.16`)
###
![App Screenshot](https://github.com/tora-ananas/HelloRobot_mobile/blob/main/start_screen.jpg)
###
#### Then if the connection to the server via socket is established, you will be taken to the robot control screen. 
##### The up\down\right\left control buttons are available and a window that display the camera from the robot
![App Screenshot](https://github.com/tora-ananas/HelloRobot_mobile/blob/main/control_screen.jpg)
###
#### There are two sockets in my android app. First socket responsible for transferring commands, second one responsible for transferring images in bytes. 
#### I use Bitmap to create image from bytes and then update ImageView
###
### Author
#### [tora_ananas](https://github.com/tora-ananas) control robot app developer
#### [YuriRyzhenko](https://www.youtube.com/user/YuriRyzhenko) owner and creator of robot

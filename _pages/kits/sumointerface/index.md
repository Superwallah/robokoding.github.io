---
layout: page
title: SumoInterface
permalink: "/kits/sumorobot/sumointerface/"
---

Access the SumoRobot programming interface [here](http://sumo.robokoding.com).

## Control panel

Below is how the control panel looks like for the SumoInterface. Here you can add our SumoRobot ID that you can find in the SumoManager app when you connect your SumoRobot with the micro USB cable. It is a 8 character unique identifier for your SumoRobot. Once having entered the SumoRobot ID press GO! or hit the enter key on the keyboard. To come back to the control panel or close it, you can use the keyboard combination Alt + C.

![control_panel](/assets/img/sumorobot_interface_control_panel.png)

## Blockly interface

Once the SumoInterface is connected to the SumoRobot you can see the battery icon (up right corner) red, orange or green. This shows the battery charge status of your SumoRobot. Red means that the battery is pretty empty and it should be charged as soon as possible. Your SumoRobot can randomly reset at times when it has low battery. When your SumoRobot is not connected or disconnects from the SumoInterface the battery icon will be with a red cross. Then you can try to reset your SumoRobot by pressing the RESET button underneath the SumoRobot next to he micro USB port.

To program your SumoRobot move available blocks from the left toolbox (gray) to the right workspace (white) (see on the image below). You can delete code by dragging it to the trash bin or to the the left toolbox (gray). You can also observe the Python code on the right that is created using the blocks. Once **Start** is pressed the Python code on the right gets uploaded to the SumoRobot and the block highlight (bright) and Python code highlight (yellow) starts to work (see on the image below). The highlight shows how the SumoRobot is executing the code that you have made. The code is executed in a loop (unlimited times) from top to bottom.

if_do (green) control block is used to make conditions with opponent and/or line. This allows you to execute commands when a certain condition is true. For example when the robot sees something in front of it or it sees a line under it.
The first condition (if) has the highest priority, the SumoRobot checks all conditions from top to bottom. If they are true it executes the commands that are in the slot of that condition (see image below). When no condition is true the commands in the else slot are executed.

![control_panel](/assets/img/sumorobot_interface_blockly.png)
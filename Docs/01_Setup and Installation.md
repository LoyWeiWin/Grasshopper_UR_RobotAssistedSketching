## Getting Started

### Software Requirements
1. Download a trial version of [Rhino 8](https://www.rhino3d.com/download/).
2. Install the [Robots for Grasshopper](https://github.com/visose/Robots) plug-in by following [these](https://github.com/visose/Robots#install) instructions:

     - Install in Rhino using the `_PackageManager` command, search for `Robots`.
     - Restart Rhino and open Grasshopper. There should be a new tab in Grasshopper named Robots.
     - Install a robot library by clicking on the `Libraries` button of a `Load robot system` component.
       - The robots from the library should appear in a value list connected to a `Load robot system` component.

> For more detailed information on the Robots plug-in, I would recommend this great [YouTube playlist](https://www.youtube.com/watch?v=vAe47zN-d48&list=PLqtxhH1qb3Mw5A_YbvHDfrq4DNNfLtcW-) from  [@robin-gdwl](https://github.com/robin-gdwl).

3. Download the [Generation Plugin](https://www.food4rhino.com/en/app/generation) by following the instructions:

     - Install the installer from `foodfromrhino` website.
     - Make sure the zip file is `unblock`.
     - Upzip the file then drag the content to the Grasshopper canvas. 

### Hardware Requirements
1. Universal Robot, UR10 (as example).
2. [Robotiq Sanding Kit](https://robotiq.com/products/sanding-kit)

## Connecting to the Robot

> Begin by powering on and starting the robot.

1. Once the robot is fully powered on, connect an ethernet cable from your computer to the ethernet port in the robot's control box.

2. Set up a LAN with a [static IP address](https://pureinfotech.com/set-static-ip-address-windows-10/) on the same network as the UR robot.

    -  Here is [how to find](https://robodk.com/doc/en/Robots-Universal-Robots.html#UR-IP) the robot's IP address.

3. Do a [`ping` test](https://www.howtogeek.com/355664/how-to-use-ping-to-test-your-network/) to check your connectivity.

> `Windows Users`: if the ping test fails, your firewall is likely blocking incoming and/or outgoing connections. See troubleshouting tips [here](https://windowsreport.com/windows-10-unable-to-ping-other-computers/#:~:text=What%20can%20I%20do%20if%20I%20can%E2%80%99t%20ping%20other%20computers%20in%20Windows%2010%3F).

4. Once you get a response from the `ping`, you are ready to send a program to the robot.

## Environment
- The environment file should contain the following items
  - Robot Workcell
  - Example metal pieces
  - End effector - [Robotiq Sanding Kit](https://robotiq.com/products/sanding-kit)
 
> **Notes**: Given the limited storage capacity on GitHub, high-complexity geometries such as UR's [teach pendant](https://www.universal-robots.com/download/mechanical-e-series/teach-pendant/standard-teach-pendant-e-series-step-file/) and [control box](https://www.universal-robots.com/download/mechanical-e-series/control-box/control-box-step-file-cb51-e-series/) have been omitted from the .3dm file. Be aware that incorporating complex geometries may require significant computational power, which could reduce the efficiency of your workflow.



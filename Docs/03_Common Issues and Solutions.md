## Plugins
**Problem:**
Unable to install plugins on the workstation.

**Solution:**
1. **Right-click the downloaded ZIP file to access its properties.**  
   <img src="https://github.com/LoyWeiWin/Grasshopper_UR_RobotAssistedMetalPolishing/blob/main/Assets/Images/IMG_PluginIssue_HowTo.png" alt="Access File Properties" title="Access File Properties" width="300">

2. **In the file properties window, check the "Unblock" box (if present).**  
   <img src="https://github.com/LoyWeiWin/Grasshopper_UR_RobotAssistedMetalPolishing/blob/main/Assets/Images/IMG_PluginIssue_HowTo_01.png" alt="Unblock File" title="Unblock File" width="300">

## Robot Mesh
**Problem:**
The robot input appears as "missing."

**Solution:**
1. **Open the 'Libraries' tab in the application.**  
   <img src="https://github.com/LoyWeiWin/Grasshopper_UR_RobotAssistedMetalPolishing/blob/main/Assets/Images/IMG_MissingIssue_HowTo_01.png" alt="Libraries Tab" title="Libraries Tab" width="300">


2. **Select 'Universal Robot' and click the 'Download' button.**  
   <img src="https://github.com/LoyWeiWin/Grasshopper_UR_RobotAssistedMetalPolishing/blob/main/Assets/Images/IMG_MissingIssue_HowTo_02.png" alt="Download Universal Robot" title="Download Universal Robot" width="300">


3. **Set "UR10" as the robot input.**  
   <img src="https://github.com/LoyWeiWin/Grasshopper_UR_RobotAssistedMetalPolishing/blob/main/Assets/Images/IMG_MissingIssue_HowTo_03.png" alt="Select UR10" title="Select UR10" width="300">


## Communication Channel
**Problem:**
Unable to communicate or send commands to the physical robot.

**Potential Cause:**
The cobot and your workstation are not connected to the same network.

**Troubleshooting Procedure:**
1. **Use the `ping` command to test connectivity:**
   - Open Command Prompt by typing "command prompt" in the search bar.
   - Enter the `ping` command followed by the cobot's IP address.  
   <img src="https://github.com/LoyWeiWin/Grasshopper_UR_RobotAssistedMetalPolishing/blob/main/Assets/Images/IMG_PlugingIssue_Ping01.png" alt="Ping Command" title="Ping Command" width="500">

2. **Interpret the ping results:**
   - If the ping is successful, the cobot and workstation are on the same network.  
   <img src="https://github.com/LoyWeiWin/Grasshopper_UR_RobotAssistedMetalPolishing/blob/main/Assets/Images/IMG_PlugingIssue_Ping02.png" alt="Ping Successful" title="Ping Successful" width="500">


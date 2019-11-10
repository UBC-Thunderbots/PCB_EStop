# PCB_EStop Description
Github SVN repository for UBC Thunderbots PCB_EStop Altium project files. 

# How to link repository with Altium Designer
## Required software
1. git
2. github GUI (optional, I am using GitHub Desktop)
2. Altium Designer

## Instructions
1. Fork the repository in github.
1. Clone your fork of the repository UBC-Thunderbots/PCB_EStop to your PC (i.e. C:/Documents/GitHub/PCB_EStop)
2. In Altium Designer, navigate to **Preferences** -> **Data Management** -> **Version Control** and ensure *SVN - Subversion* is enabled and Version 1.9 is selected.
4. In Altium Designer, navigate to **Preferences** -> **Data Management** -> **Design Repositories**.
5. Within **Design Repositories** click on on *Connect To* -> *SVN*.
6. In the dialogue box that comes up, fill in the following information:

Field | Selection/Input
--- | ---
Name | PCB_EStop
Default Checkout Path | *location of the cloned UBC-Thunderbots/PCB_EStop repository (i.e. C:/Documents/GitHub/PCB_EStop)*
Method | https
Server | github.com
Server Port | Default
Repository Subfolder | /UBC-Thunderbots/PCB_EStop
User Name | *your github login username*
Password | *your github login password*

7. Click *Test* and pray.
8. Celebrate!

After your repository is connected, you can add or remove files like a regular Altium Project folder and then commit them from within Altium Designer by right-clicking on any project files in the **Projects** and hovering the mouse cursor over **Version Control**.

Reference page: https://forum.live.altium.com/#posts/235981/718003

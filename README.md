# FLL-2025-2026
Starter Code for  Pybricks/FLL

Github url: https://github.com/infiniteroboticsteam/FLL-2025-2026

# set up

1. download and install visual studio code
2. download and install python
3. follow this guide to set up vscode
4. install github
5. set up github, log in to github with your google account and create a github account.
6. in github cmd (windows), set up user.name and user.email like below: 
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com

7. in vscode, clone our team repo.
8. the code should be ready to use!



# code structure

1. the parameters for our driving base and sensor ports are in robot_config.py

2. Use run_demo.py as an example on how to write the code for a run.

    A run is defined as a procedure where the driving base with attachments installed starts from a launch area and returns to either a home area or a launch area. 

    A run can be programed to complete multiple missions.

3. Steps to write your code for a run.
    
    * For each mission, define a function to move the each attachment to complete a mission.
    * define a function to move the driving base, at approporiate waypoint (based on distance), add movements for attachments.
    * test the function for a run in your run.

4. At the end, we will use robot.py to add all runs to the program so that during the competition we run different runs by pressing buttons on the hub. Remember, laptop/ipad are not allowed in the game.

New starter code for Pybricks/FLL


Readme is work in progress. Code itself is well documented. 


How to use:


robot_config.py

Change these values to match your robot.




robot.py

This is the file you compile. All the robot runs are imported into this file and then compiled. 

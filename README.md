# Inverse-kinematic-modeling-using-robo-analyzer-

 
## AIM: 
To analyze the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given  input end effector position .


### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
### Inverse Kinematics
 

Inverse kinematics is the use of kinematic equations to determine the motion of a robot to reach a desired position. For example, to perform automated bin picking, a robotic arm used in a manufacturing line needs precise motion from an initial position to a desired position between bins and manufacturing machines. The grasping end of a robot arm is designated as the end-effector. The robot configuration is a list of joint positions that are within the position limits of the robot model and do not violate any constraints the robot has.

 Most industrial robots are constructed of several independently controllable articulated joints. Each joint is connected to one or more of the other joints, sometimes in complex configurations. The end effector is attached at the end of the entire “kinematic chain”. When you move any one joint, this will affect the end effector’s pose in various ways.

This means that there is no simple, direct relationship between the end effector position and any one particular joint.

For example, if you want the robot’s end effector to move 1 mm linearly along the Z-axis, you may need to move all of the joints by a different amount.

Finally, inverse kinematics algorithms calculate the exact position of each of the robot’s joints required to reach your desired end effector pose.

### solving inverse kinematic model 
![image](https://user-images.githubusercontent.com/36288975/170622829-3fe97ef7-8ef1-44af-afae-b0954871aa0c.png)


![image](https://user-images.githubusercontent.com/36288975/170622902-f48fd9c7-f2ec-4fd5-904b-ea51be8298c3.png)

![image](https://user-images.githubusercontent.com/36288975/170622934-a3fd7f77-7eb2-4408-b66d-d6e3adbd1f99.png)

![image](https://user-images.githubusercontent.com/36288975/170622982-9c4d8b23-1563-4e17-9616-87bcc4f4501d.png)
![image](https://user-images.githubusercontent.com/36288975/170623020-f27efc12-bb58-4f62-840d-af544ac6689e.png)

### PROCEDURE:

1. open the roboanalyzer software.
2. select the robot and its degrees of freedom.
3. change the values of X and Y wherever necessary.
4. simulate the model for inverse kinematics.
5. plot the graph between the joints.
6. update the DH parameters of the link configuration and end effector configuration.

### SIMULATION 
 
 #### RRP ROBOT:
<img width="603" alt="rrp 1" src="https://user-images.githubusercontent.com/77089276/170744649-a7497473-1de5-448e-a3b1-a200b26b437e.PNG">
<img width="834" alt="rrp2" src="https://user-images.githubusercontent.com/77089276/170744683-383c8fb1-81b5-46cd-8209-34496296d9f4.PNG">


  #### 3R ROBOT:
  
<img width="594" alt="3r1" src="https://user-images.githubusercontent.com/77089276/170743765-5d65684a-e0b6-4aa7-a793-3119dc94f5c1.PNG">

<img width="842" alt="3r2" src="https://user-images.githubusercontent.com/77089276/170743788-7154dce8-e650-4197-8ee5-4d7a1a8001cd.PNG">


 ### PLOT 
 
  #### RRP ROBOT:
  <img width="717" alt="rrp3" src="https://user-images.githubusercontent.com/77089276/170744571-2b071175-35bc-4069-b8e4-eb270bbf53c7.PNG">
 <img width="214" alt="rrp6" src="https://user-images.githubusercontent.com/77089276/170746800-db66ba09-58bc-4118-9d5d-7bed99d33fec.PNG">

 
  #### 3R ROBOT:
  <img width="714" alt="3r3" src="https://user-images.githubusercontent.com/77089276/170747341-ba9f158c-93bf-4d69-8f25-0ad0abcc24ff.PNG">
  <img width="215" alt="3r6" src="https://user-images.githubusercontent.com/77089276/170747394-4b097bac-94ac-402e-80d7-75e1b39c65fd.PNG">


### RESULTS :    

Thus,the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer is analysed and the graph of joint angle for a given  input end effector position is plotted.

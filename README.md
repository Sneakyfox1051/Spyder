### SPYDER

## AUTONOMOUS DELIVERY DRONE 

## Introduction 

1. Our concept revolves around the creation of autonomous delivery drones that
   are capable of performing deliveries without manual intervention.

2. The main purpose of this system is to facilitate fast, secure, and efficient
   transport of parcels from either a central hub or warehouse directly to the
   intended recipient.

## Requirements

1. `Autonomous Robot`
2. `Obstacle Avoidance Sensors`
3. `Weather Monitoring`
4. `Flight Controller`
5. `Predefined Missions`
6. `Flight path`

## Innovative technology used 

 # 1. Design:
• Our prototype consists of a 6-motored Hexacopter configuration with a
gripping mechanism attached to the bottom for holding the packages
securely.

# 2. Smart processing unit:
• An intelligent processing unit has been developed to establish secure
communication between various components of the drone
• Ensures smooth flight and secure delivery.

# 3. Machine learning algorithms:
• Allows the drone to learn from its surroundings and adapt in real time.
• a feature that sets our project apart as it moves beyond traditional
technologies that make use of preprogrammed instructions.

# 4. GPS mapping and Compass Technology:
• To accurately track and display the drone's location which is crucial for long-distance deliveries where human monitoring is
not feasible.
# 5. Sensors:
• We have incorporated a range of sensors, such as weather monitoring sensors that keep the drone updated with real-time
weather conditions.
• Obstacle avoidance technology by using LiDAR. The advantage of LiDAR lies in its ability to provide accurate positioning over
large areas at high speeds, making it an ideal choice for our prototype.
# 6. Camera:
• our drone makes use of a camera integrated at the bottom part of the drone that provides real-time footage of the drone's
activities.
# 7. Dual battery system:
• To provide sufficient flight time, our drone features a dual power system that allows the drone to rely on two sources: the
main battery as the primary source and the solar panels as the backup source.
• The secondary battery provides power to the drone in case the drone exhausts the primary battery or encounters any
battery-related issues during its flight.


### Identification of Tasks

1.Define the requirements and objectives: Determine the drone's purpose, including the 
intended application, performance metrics, and regulatory compliance.

2. Select the components: Select the necessary components that are specific to the 
intended application. These components may include the airframe, sensors, motors, 
cameras, and communication systems.

3.Develop the hardware: Design and build the drone hardware, including the propulsion 
system, airframe, and electrical components.

4. Develop the hardware: Design and build the drone hardware, including the propulsion 
system, airframe, and electrical components.

5• Develop the software: Develop the software required for the drone system, including 
the control software, navigation algorithms, and AI-based algorithms.

6• Integrate the components: Combine the hardware and software components to create a 
functional drone system.

7• Test the drone: Verify that the drone system works properly and is safe to use. This 
may include tests in simulations, controlled environments, or real-world scenarios.

8• Refine the design: Evaluate the test results and make the necessary changes to improve 
the drone system's performance and safety.

9• Deploy the drone: Launch the drone into the desired environment and continuously 
monitor and improve its performance over time.

### step-by-step instructions for using our prototype:

# Step 1: ' Connect the battery to the drone's power module and mount it on the drone as 
shown in the figure below ' 

# Step 2: ' Place the drone on a level surface ready for take-off. '

# Step 3: ' Establish a wireless connection between the laptop or ground station and the 
drone via the Wi-Fi network named Ardupilot. '

# Step 4: ' Once connection is established, open the mission planner on your laptop and 
click the connect button located in the upper right corner of the mission planner screen.'

# Step 5: ' To access the mission planner tab, click the Plan button '

# Step 6: ' Begin by assigning the takeoff instruction to the drone in the mission planner 
tab. Then, enter the desired waypoint for the drone to reach its destination. After 
completing the mission, use the RTL (Return to Launch) command to return the drone 
to its original takeoff point.'

# Step 7: ' After setting the waypoints, click the write button to send the data to the drone. '

# Step 8: ' Once the task has been assigned to the drone, go to the mission planner's data 
tab and click the Arm/Disarm button to give the drone permission to take off '

# Step 9: ' After the drone is Armed, click on the Do Action button to prompt the drone 
to execute the task assigned by the user. '

# Step 10: ' Once the task is complete, disarm the drone and repeat steps 1-8 whenever 
you want to assign another mission to it. '


## Implementation of Solution:

Based on the block diagram and flowchart, we constructed a prototype of our 
autonomous drone and conducted testing in real-world environments under various 
conditions. Here is an analysis of our testing:

1. Data Evaluation: Our drone was able to successfully update us with real-time data 
on parameters such as its location, current altitude at which it is flying, speed while 
maneuvering in the air, distance from its destination, battery percentage, etc. When 
compared to data from various apps, our drone's data proved to be highly accurate, 
with a deviation of only 0.1%.

2. Task Completion: Initially, there were some issues with task completion, but after 
adjusting certain parameters, the drone was able to successfully perform complex 
tasks with increased efficiency. Furthermore, the drone provides us with real-time 
footage of everything it captured.

3.Field Testing: We conducted rigorous testing of our drone in different climates to 
ensure its efficiency in diverse conditions. The drone proved to be capable of 
adapting to various terrains, weather conditions, and altitudes, maneuvering 
without difficulty.

4. Comparative Testing: We compared the performance of our autonomous drone 
with a manual drone. Based on the comparison, it was discovered that autonomous 
drones outperform manual drones as the field of vision in manual drones is limited 
to the person only, which means a drone can only travel as far as a person can see, 
whereas our drone can travel longer distances because it provides us with real-time 
updates of its location on our laptop. Additionally, operating our drone proved to 
be easier than the manual drone, as users only needed to provide tasks via a laptop 
or ground station, while manual drones require manual control and experience.

5. Iterative Improvement: We continuously analyzed the data from each flight and 
made improvements to align our drone with project objectives and requirements.

6. Safety and Regulatory Compliance: We ensured that our drone adhered to all 
safety and regulatory requirements, including aviation regulations and privacy 
considerations.




Following the successful development of the autonomous drone prototype, there are several 
areas that require further attention and improvement. Priority should be given to addressing 
the drone's limited flight time. This can be achieved by integrating alternative energy 
sources, such as solar panels, which would significantly increase the drone's flight time. 
Furthermore, the utilization of Lidars instead of ultrasonic sensors can enhance the drone's 
safety and reliability. Introducing more advanced algorithms will also enhance the drone's 
autonomous capabilities.

## Authors

1. Guladab Bawa /21BCS9345@cuchd.in
2. Gunmeet Singh /21BCS9331@cuchd.in
3. Harsh Chauhan /21BCS9288@cuchd.in
4. Abhisek Bag /21BCS9333@cuchd.in
5. Vinay Prakash /21BCS9329@cuchd.in
6. Aditi Mehra /21BCS9337@cuchd.in

## License

 AUTONOMOUS DELIVERY DRONE  licensed under the Apache 2.0 License. See the [`LICENSE`](LICENSE) file for more information.

   



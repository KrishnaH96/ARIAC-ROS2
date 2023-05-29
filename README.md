# ARIAC-ROS2
ARIAC Competition ROS2 Package

The Agile Robotics for Industrial Automation Competition (ARIAC) is a competition in the field of
robotics and automation, organized by the National Institute of Standards and Technology (NIST).
The simulation-based competition focuses on the development of agile robotics systems for industrial
automation. The aim of this challenge is to test the ability of a robot to perform a series of tasks in
a dynamic environment. The tasks are designed to test the robot’s ability to perform pick-and-place
operations, assembly, and kitting. The agility challenges include various unplanned circumstances
including robot failures, sensor failures, humans in the environment, etc., and the software system
should be robust enough to manage all these uncertainties and still be able to complete the task. //
The primary goal of this competition is to encourage robotics students to come up with new and
innovative approaches to solve challenges related to robotics and automation in manufacturing environments.
The competition environment is a simulation of an Assembly line shop floor that uses a
floor robot located on a rail parallel to the conveyor belt and a ceiling robot that is able to access
the complete shop floor. Both the robots have a UR10e arm and can be used to complete any of the
tasks. Four types of parts such as Battery, Pump, Sensor, and Regulator with five different colors will
be used in the tasks. Kitting trays are used to place kiting parts of a task. These trays have four
quadrants on which the parts are to be placed as per the order information. Each tray is marked with
a unique ARUCO standard fiducial marker. Automated guided vehicles (AGV) are used to transport
kitted parts to their destination. The Parts are located in the 8 bins or spawned on the conveyor belt
at the start of the competition. The Kit Tray/Tool Changer Stations have robot gripper changers and
accommodate up to 3 kitting trays on each station. The Part disposal bins are located at two ends
and near the center of the conveyor belt. These bins are used to dispose of faulty parts.
The challenges in the competition which were dealt with as part of this project are as follows:
1. Insufficiency challenge The insufficient parts challenge requires us to identify whether the
required parts to complete the given orders are available in the environment. In case, the parts
are not available, we have to submit the order with insufficient parts.
2. Priority order challenge This challenge checks for the agility of a robot system to complete
the high-priority orders before the other orders. The Competitor Control System (CCS) is
expected to complete higher-priority tasks as soon as it is announced. Once the priority order is
completed, it should then return to the abandoned task and complete it.
3. Faulty parts challenge This challenge simulates a realistic manufacturing environment, where
few parts are faulty. These faulty parts should be identified and discarded by the CCS and
replaced with a new part if available. In any case, the faulty parts cannot be used to complete
orders as they do not count for the points in the competition.
Through this project, the aim is to complete all the essential activities of robot control and motion
and address the above agility challenges of ARIAC.

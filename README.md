# Turtle_bot_controller
The "turtle_bot_controller" repository contains a ROS2 node that allows a turtle to create a snowman shape by spawning two turtles and controlling their movements.
Overview
This ROS2 node is designed to control a turtle in a simulated environment to create a snowman shape using the TurtleBot. The node utilizes the ROS2 ecosystem and the TurtleBot package to control the turtle's movement and spawn additional turtles to form the snowman.

Features
Snowman Shape Creation: The node orchestrates the movement of two turtles to create a snowman shape.
ROS2 Compatibility: Developed using ROS2 for compatibility with the latest ROS distribution.
Simple Control Interface: Provides an easy-to-use interface to control the turtle's movements and spawn additional turtles.
Installation
To use this node, follow these steps:

Clone the repository into your ROS2 workspace:
bash
Copy code
cd ros2_workspace/src
git clone https://github.com/yourusername/turtle_bot_controller.git
Build your ROS2 workspace:
bash
Copy code
cd ros2_workspace
colcon build
Usage
To run the node and create the snowman shape, use the following command:

bash
Copy code
ros2 run turtle_bot_controller turtle_bot_controller_node
This will start the node, which will then spawn two turtles and control their movements to form a snowman shape.

Additional Information
For more detailed information on the node's functionality, usage instructions, or any inquiries, please refer to the documentation or contact the project maintainers.

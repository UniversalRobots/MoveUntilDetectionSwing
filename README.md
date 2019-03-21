# MoveUntilDetectionSwing
URCap sample to demonstrate the usage of configuration builders for Direction and Until program nodes.

Move Until Detection Swing demonstrates how to work with the Distance and Until program nodes through the URCap API.

The program node contribution creates a Direction node that moves the robot downwards, until a sensor is triggered (through an input), or until a maximum distance is reached. If the sensor is triggered, a connected physical device (e.g. a gripper) is activated by setting an output high. If the maximum distance is travelled before the sensor is triggered, a popup is generated to display an error to the user. The user can specify the maximum distance through a text field in the Move Until Detection node.

Information:
* Available from:
  * URCap API version 1.6.0.
  * PolyScope version 3.9.0/5.3.0.

Main API interfaces: DirectionNode, DirectionNodeConfigBuilder, UntilNode, UntilNodeConfigFactory.

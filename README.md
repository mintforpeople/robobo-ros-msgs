# Robobo ROS Messages

This repository contains the definition of custom messages and services used by the Robobo educational robot.

## Dependencies

The Robobo ROS messages package depends on:

* std_msgs
* sensor_msgs
* opencv_apps

It is advised to install *aruco_msgs* and *vision_msgs* since it is used by some topics published by the Robobo educational robot.

## Documentation

Every message and service definition has commentaries at the beginning explaining what the definition is used for and a brief explanation of each field.

## Command messages

All messages ending on *"Command"* are a migration of the deprecated services (that will remain operational for backward compatibility) to the preferred topic messages.

# ros-embodiment README

an external directory meant to be built as a subdirectory of OpenCog

*very* minor changes to CMakeLists.txt in opencog/ subdirectory


see "ros-embodiment-testing" branch of my fork of OpenCog at:

  https://github.com/LucidBlue/opencog

for changes



Description:

This is an experimental embodiment module using ROS as a communication layer between components of the OpenCog embodiment system. I am currently working on a Minecraft-based embodiment module, the current state of which is a working Minecraft bot that can be controlled through messages sent in ROS. See: https://github.com/LucidBlue/ros-to-minecraft for details. At some point I will be combining these projects into one, and eventually merging with the current OpenCog embodiment project, but that will be far in the future. At this stage everything is experimental.

Current state:
I am able to use OpenCog libraries in my own code as if they exist in a relative directory, due to CMake build conditions. The directory ros-embodiment is built as a subdirectory of the OpenCog fork.

# TitanOS
This is my take on a Unix-like system that is POSIX compliant.


# Kernel options:
In the OS development space there are two types of kernels, monolithic and micro. I feel that a lot of projects tried to make a posix compliant micro kernel and failed in terms of getting other users on board with their project. My goal is to learn how these types of kernels deal with security and providing async out of the box much like Wayland does.

# Why POSIX?
This project uses posix as a form of ease as a developer. This means you can read up on the posix documentation and know exactly what you can and cannot modify. My aim is to be completely posix compliant and only adding security features as an obstraction layer seperate from the posix systems. This means that the structure of these applications will always function the correct way on any system.

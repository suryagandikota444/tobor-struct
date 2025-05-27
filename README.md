# Two-Link Robot Arm Physical Design

This repository contains all the physical design files for a two-link robot arm system.

## Design Overview

The robot arm consists of three main components with the following motion capabilities:

### Base
- **Rotation Range**: 270 degrees
- Provides the primary rotational movement for the entire arm assembly

### First Arm (Link 1)
- **Rotation Range**: 180 degrees from the base
- Connected to and rotates relative to the base

### Second Arm (Link 2)
- **Rotation Range**: 270 degrees from the first arm
- Connected to and rotates relative to the first arm, providing the end-effector positioning

## Repository Contents

This repository includes all necessary design files for manufacturing and assembling the physical robot arm, including:
- CAD models and drawings

## Motion Characteristics

The combination of these three degrees of freedom allows for versatile positioning within the robot's workspace:
- Base rotation: 270° range
- Shoulder joint: 180° range  
- Elbow joint: 270° range
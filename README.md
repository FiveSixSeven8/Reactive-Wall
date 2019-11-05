# Reactive Wall

## Overview
Developed by: Anna Henson and Lena Wolfe 

Contributing Files: https://github.com/satoshi-maemoto/Azure-Kinect-Unity-Body-Tracker

## Hardware Requirements
- Kinect for Azure
- Compatible computer (see https://docs.microsoft.com/en-us/azure/Kinect-dk/system-requirements)

## Environment
- Unity2019.2.x
- Azure Kinect SDK v1.3.0
- Azure Kinect Body Tracking SDK v0.9.4

## Installation
- Download and install Azure for Kinect SDK and Body Tracking SDK
- Download and set up Azure Kinect Unity Body Tracker (see above contributing files)

## Setup
Place the files from this GitHub repository into K4AUnityBT\Assets

Open K4A_Reactive_Wall.unity

## Code Breakdown

### K4A_reactive_wall.unity
Unity scene consisting of two live views, depth camera and joing tracking, and a virtual room. 

The virtual room has a reactive wall. When a body interacts with a set point on the reactive wall, the song begins. 

### k4a_interaction_controller.cs
Defines the body part to for the interaction control. (Left hand position)

### Singleton.cs
(FILL IN)

### SongCollider.cs
Play a song when specified body part collides with designated point on reactive wall. 





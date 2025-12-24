# Computer Vision for Autonomous Systems

Computer Vision for Autonomous Systems is a core field that enables machines (like self-driving cars, drones, and robots) to perceive, understand, and act based on visual data from the world.

Computer vision allows an autonomous system to:

* See the environment (via cameras, LiDAR, radar)
* Understand what’s there (objects, people, roads, obstacles)

Decide what to do next (navigate, stop, avoid, interact)

In short:
Perception → Understanding → Action


## Key Vision Tasks
Object Detection

Identifies and locates objects such as:

* Cars, pedestrians, cyclists
* Traffic signs and signals
* Obstacles and animals

Common models:

* YOLO
* Faster R-CNN
* SSD


## Lane & Road Detection

Used mainly in autonomous vehicles:

* Lane markings
* Road boundaries
* Crosswalks
  
Techniques:
* Edge detection
* Semantic segmentation (e.g., U-Net, DeepLab)


## Semantic & Instance Segmentation

Assigns labels to every pixel:
* Road, sidewalk, sky
* Vehicles vs pedestrians

This gives detailed scene understanding.


Localization & Mapping (Visual SLAM)

Helps the system know:

Where it is

What the environment looks like

Techniques:

Visual SLAM (ORB-SLAM)

Visual-Inertial Odometry

Structure from Motion (SfM)


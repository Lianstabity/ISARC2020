# ISARC 2020

This is the work log for ISARC 2020 Project.

* [ ] **Abstract**    [May. 1 – May. 7]

* [ ] **Introduction** [May. 1 – May. 7]
  * [x] Background [3D Printing + Construction ]
  * [x] Research Gap [Rely on manual adjustment]
  * [ ] Purpose a new approach ==> Need to highlisht main controbution 
       * [ ] Detection + Control
 
* [ ] **Related work**
  * [ ] Reference collection & Summary writing[Present – May. 7]
  * [ ] Topic 1: Construction 3D Printing [NTU 3D Printing] [Mention Material]
  * [ ] Topic 2: 3D Perception in civil [Point cloud, 3D reconstruction] [1-2 sentences]
  * [ ] Topic 3: Currently 3D Printing defect detection [Plastic] [Concert]
  * [ ] Summary novelty & difference with other method
  
* [ ] **Method** [May. 7 – May. 28]
  * [ ] Sensor Introduction
    * [ ] RGB-D: Microsoft Azure Kinect 
  * [ ] 3D Printing Platform 
    * [ ] UR10 + Printing Head + Material
    * [ ] ROS + Moveit!
  * [ ] **Defect Detection**
    * [ ] Model Deviation
      * [ ] Layer Deviation [Overfill & Underfill]
           * [ ] Compare layer contour with slice contour
      * [ ] Shape Error
           * [ ] Point cloud Distance between scan file and GT
  * [ ] Extruder Detection
    * [ ] Bubble
  * [ ] Feedback Control
    * [ ] Single Layer Compensation
    * [ ] Cumulative Error Compensation  Periodic Compensation
  
* [ ] **Experiments**
  * [ ] Task 1 : Static surface / layer Inspection [May. 7 – May. 21]
    * [ ] Subtask 1: Record a video for Bubble Detection
    * [ ] Subtask 2: Using mask for Model Deviation Test
  * [ ] Task 2 : 3D printing test [May. 14 – Jun. 4]
    * [ ] Subtask 1: Hand eye calibration
    * [ ] Subtask 2: Printing head + Material preparation
    * [ ] Subtask 3: Real time 3D printing  [square or circle or pyramid]
    * [ ] Adding noise on robot arm

* [ ] **Conclusions**

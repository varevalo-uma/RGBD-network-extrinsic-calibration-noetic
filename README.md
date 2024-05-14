---
This repository only contains the nodes related to the extrinsic calibration of four RGBD sensors. All other nodes have been removed. In addition, several changes have been made to the source files to adapt them to noetic ROS1. Most of the changes made in the code were aimed at correcting the errors produced by the use of libraries that have undergone important changes in their api, directory structure, etc. This was the case of the opencv library. I would like to thank the authors of the OpenPTrack source code for making their work available to the community :-).

---

open_ptrack
===========

http://openptrack.org/

Note: The recommended installation method to get up and running quickly is to use the Docker container.  Instructions are here: https://github.com/OpenPTrack/open_ptrack_v2/wiki/Docker-Images

OpenPTrack is an open source project launched in 2013 to create a scalable, multi-camera solution for person tracking that specifically aims to support applications in education, art, and culture.

With the advent of commercially available consumer depth sensors, and continued efforts in computer vision research to improve multi-modal image and point cloud processing, robust person tracking with the stability and responsiveness necessary to drive interactive applications is now possible at low cost.  But the results of such research are not easy to use for application developers. We believe that a disruptive project is needed to bridge these two worlds and enable artists and creators to work with real-time person tracking.   OpenPTrack aims to support “creative coders” in the arts, culture, and educational sectors who wish to experiment with real-time person tracking as an input for their applications.

The project contains numerous state-of-the-art algorithms for RGB and/or depth tracking, and has been created on top of a modular node based architecture, to support the addition and removal of different sensor streams online.

OpenPTrack is led by UCLA REMAP and Open Perception. Key collaborators include the University of Padova and Electroland. Code is available under a BSD license.  Portions of the work are supported by the National Science Foundation (IIS-1323767).
Note that the OpenPose library used in pose recognition does not allow commercial repackaging of OpenPTrack pose recognition capabilities; please contact the CMU OpenPose team for a license.

If you use this code, please cite:

[OpenPTrack v1]
M. Munaro, A. Horn, R. Illum, J. Burke and R. B. Rusu. OpenPTrack: People Tracking for Heterogeneous Networks of Color-Depth Cameras. In IAS-13 Workshop Proceedings: 1st Intl. Workshop on 3D Robot Perception with Point Cloud Library, pp. 235-247, Padova, Italy, 2014. 

M. Munaro and E. Menegatti. Fast RGB-D people tracking for service robots. Journal on Autonomous Robots, vol. 37(3), pp. 227-242, Springer, 2014. 

[PoseEstimation and PoseRecognition]
M. Carraro, M. Munaro, J. Burke and E. Menegatti. Real-time marker-less multi-person 3D pose estimation in RGB-Depth camera networks. arXiv preprint arXiv:1710.06235, 2017.

Z. Cao, T. Simon, S. E. Wei, and Y. Sheikh, 2016. Realtime multi-person 2d pose estimation using part affinity fields. arXiv preprint arXiv:1611.08050.

T. Simon, H. Joo, I. A. Matthews, and Y. Sheikh, 2017, July. Hand Keypoint Detection in Single Images Using Multiview Bootstrapping. In CVPR (Vol. 1, p. 2).

[ObjectTracking]
Y. Zhao, M. Carraro, M. Munaro and E. Menegatti, Fast Multiple Object Tracking in RGB-D Camera Networks, in Intelligent Robots and Systems (IROS), 2017 IEEE/RSJ International Conference on, IEEE, 2017.



Introduction
=============

The PiCar project is a miniature four-wheeled car powered by a Raspberry Pi 3
board. This lab-scale autonomous research platform is easy to build and modify.
A camera and LIDAR mounted on the car allows for complex computer vision
algorithms.

.. raw:: html

  <p align="middle">
  <a href="https://github.com/xz-group/PiCar" target="_blank"
  class="btn btn-neutral" title="Go to the PiCar Repo">
  <span class="icon icon-github"></span> PiCar GitHub</a>
  &nbsp;
  <a href="../index.html" target="_blank"
  class="btn btn-neutral" title="Go to the Table of Contents">
  <span class="fa fa-navicon"></span> Table of Contents</a></p>


The `PiCar GitHub Repository <https://github.com/xz-group/PiCar>`_ contains
all the software and hardware source files required to duplicate the car,
including:

  *  Chassis 3D printing, and CAD sources.
  *  Raspberry Pi 3 breakout PCB to connect peripherals and draw power from
     LiPo battery.
  *  Source code of the following software modules capable of:
  *  Acquire wheel RPM data using encoder.
  *  Acquire acceleration, angular velocity, and compass data from an I²C
     LSM9DS1 IMU.
  *  Acquire video data from a Raspberry Pi NoIR camera.
  *  Perform real-time computer vision using camera data.
  *  Control the speed of brushed DC/BLDC motor.

The purpose of this documentation is to create a full fledged, clear formal
guide for using the PiCar project. It will also serve as a place for showcasing
results.

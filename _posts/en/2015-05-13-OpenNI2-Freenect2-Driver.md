---
category: en
title: OpenNI2-Freenect2 Driver
lang: en
---
{% include JB/setup %}

I have written a OpenNI2-Freenect2 Driver and sent [pull request](https://github.com/occipital/OpenNI2/pull/46), though it is not merged yet. Details are written in [README](https://github.com/MasWag/OpenNI2/blob/libfreenect2/Source/Drivers/Libfreenect2/README.md).

FAQ
---

* My application does not work with Kinect v2. Why?
    * First, does libfreenect2's sample work well? Freenect2 uses OpenGL or OpenCL or CPU (by default OpenGL).You may have to configure your GPU or Freenect2's build option. 
    * If Freenect2 work fine,it may be my driver's problem. I have implemented some features, but not others. (ROI, Color recording, and so on) If you use these features, you can implement it! (actually, I do not have Kinect v2 now , so I might tell you where to change but I cannot test it...)
* Is this supprts human tracking, e.g. Nite?
    * I have tested it ,but does not work.Nite is not free so I could not debug well.Please tell me what is wrong.
* I want to change GPU driver
    * My driver uses default GPU driver.So you have to switch it at compile time. you can disable OpenGL and OpenCL when compiling libfreenect2 as

> cmake -DENABLE_OPENGL=OFF -DENABLE_OPENCL=OFF CMakeLists.txt

* Where is patched libusb?
    * When you build previous libfreenect2, it is generated in "depend" directry.

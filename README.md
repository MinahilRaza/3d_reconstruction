# 3D reconstruction using Intel RealSense Depth Camera

This repository contains code to recontruct the 3D model of an object by using an Intel RealSense Depth camera. Sample model files (.ply) files have been provided in the ./models folder.

## Installation
This code has been tested with Python 3.8. The environment can be setup using the provided requirements file.
~~~ sh
pip install -r requirements.txt
~~~

## How to Run the Code
- Connect the Intel RealSense camera to the computer
- After installing the dependencies, run the script "scan_rdbg.py"
~~~ sh
python scan_rgbd.py
~~~
- A snapshot (RGBD) can be captured by pressing 'e'
- The captured snapshot can be viewed by pressing 'v'

## Sample Models
As a sample, a mesh reconstruction of a bowl is provided in the models folder. 
![snapshot_front00](https://user-images.githubusercontent.com/30044227/221942667-a4083f1c-9739-4428-b6a4-235c27225ce0.png)

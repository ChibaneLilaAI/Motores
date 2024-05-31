# Anomaly Detection in Motor images

## Project Objective:
The objective is to identify the images that contain anomalies that could be:

✅  Missing part

✅  Wrong part

✅  Wrong part color

✅  Damaged part

✅  Poor cable fixing

✅  Lost object in the assembly
etc.

## Solution Overview

First, we manually segmented the images of the motors to extract the ground truth, indicating the anomaly's location. Next, we isolated the yellow top-bottom and the gray right pin, merging them into one image. Similarly, we grouped the gray button and the bottom buttons into another image. After resizing the motor image, we divided it into two parts: top and bottom. Subsequently, we trained four distinct models on each extracted image and combined their results to obtain the final prediction.

![image](https://github.com/ChibaneLilaAI/Motores/blob/main/image1.jpg)
&nbsp;
&nbsp;
![image](https://github.com/ChibaneLilaAI/Motores/blob/main/image2.jpg)
&nbsp;
&nbsp;
![image](https://github.com/ChibaneLilaAI/Motores/blob/main/image3.jpg)

#### Dependencies
- scikit-learn
- numpy
- pandas
  
## Final Best Result

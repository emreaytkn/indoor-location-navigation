# indoor-location-navigation
Identify the position of a smartphone in a shopping mall
	1. Indoor Location & Navigation

	- Identify accurate position of a smartphone in a shopping mall.


Task: For a given site-path file, predict the floor and waypoint locations.

Data
Source:
Android mobile phones, with explicit user permission

During the walk, an Android smartphone is held flat in front of the surveyors body, and a sensor data recording app is running on the device to collect IMU (accelerometer, gyroscope) and geomagnetic field (magnetometer) readings, as well as WiFi and Bluetooth iBeacon scanning results.

Data Structure

startTime:1574671052072
endTime:1574671062636
data/site1/B1/path_data_files/5ddb9302c5b77e0006b179a4.txt

![image](https://user-images.githubusercontent.com/3434091/156968245-cdeb038e-3be3-42d0-9415-e6d6e8174614.png)



Sponsors / Host
XYZ10 - Indoor positioning technology company based in China
Microsoft Research

Train
training path files, organized by site and floor; each path files contains the data of a single path on a single floor


Test
test path files, organized by site and floor; each path files contains the data of a single path on a single floor, but without the waypoint (x, y) data; the task of this competition is, for a given site-path file, predict the floor and waypoint locations at the timestamps given

Ground Truth


Improvement Fields
	- Position accuracy, particularly in multi-level buildings.
	- Current solutions generalize poorly to small datasets
	- Handling more granular sensor data

Application 
	- Improve location-based experince of customers
	

Resource [3]

Literature Research
[1] https://ieeexplore.ieee.org/ielx7/6287639/9312710/09531633.pdf?tp=&arnumber=9531633&isnumber=9312710&ref=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS50ci8=

[2] https://biblio.ugent.be/publication/8647948/file/8648624.pdf

[3] https://arxiv.org/pdf/1505.06125.pdf


Glossary
An Inertial Measurement Unit (IMU) is a device that typically consists of gyroscopes to measure and report angular rate and accelerometers to measure and report specific force
![image](https://user-images.githubusercontent.com/3434091/156968186-159fc2bc-c91b-4f03-942a-31b5e83fb779.png)

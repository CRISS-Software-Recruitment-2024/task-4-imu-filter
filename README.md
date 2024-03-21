# task-4-imu-filter
What are ```imu filters```? Why do we need to use imu filters ?
-> In ROS (Robot Operating System), IMU (Inertial Measurement Unit) filters are software components used to process and refine raw data from IMU sensors. IMUs typically consist of accelerometers, gyroscopes, and sometimes magnetometers, which measure various aspects of a robot's motion, including linear acceleration, angular velocity, and magnetic field orientation.

IMU filters play a crucial role in improving the quality and accuracy of IMU data by reducing noise, errors, and drift inherent in sensor measurements. They achieve this through various techniques such as sensor fusion, signal processing, and estimation algorithms.

TASK: 
Remember in the last task you had added an imu plugin for your robot. You also saw that it plublished imu data on the ```/imu``` topic.
Now you need to implement a simple imu filter. You yourslef will have to find how to do it by searching it online (it can be a ros package that you can install from the internet )
Its easy to find a package to do this task.

You need to filter the imu data and publish the filtered data on the topic ```/imu_filtered``` or ```/imu/data```.

SUBMISSION:(Publish the following on github)
1. You need to submit a screenshot of ```rostopic list``` and ```rostopic echo /insert_topic_name_for_filtered_imu_data```.
2. Also write a .txt explaining which ros package / python file / launch file you have used to perform the task.
3. Submit the launch file you are running.


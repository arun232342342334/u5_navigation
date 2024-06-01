### Clone the Repo
> git clone https://github.com/arun232342342334/u5_navigation.git

### Launching navigation.launch

Launch the navigation.launch file after connecting the Arduino microcontroller, Lidar and IMU sensor(MPU-6050) to your processor like Raspberrypi, here I'm using jetson nano.

Run master node in pc terminal

> roscore

Launch the following command in ssh terminal

> roslaunch u5_navigation navigation.launch

### Note: The code uploaded to Arduino should subscribe the topic /cmd_vel, the give cmd_vel_ardi.ino code can be used for uploading in the Arduino dev board


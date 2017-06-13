# RasPi-CPUInfo
A program showing CPU info on PCD8544 running on RasPi

### How to build and run
1. Download and setup [wiringPi](https://projects.drogon.net/raspberry-pi/wiringpi/):
```
git clone git://git.drogon.net/wiringPi
cd wiringPi
./build
```  
2. Clone this repository and run the following command to build:
```
gcc -lwiringPi -o cpuinfo pcd8544_rpi.c PCD8544.c
```
3. Run the program. You may want to run it within `screen` which let you run it background.
```
sudo ./cpu
```

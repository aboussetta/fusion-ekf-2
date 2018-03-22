# Fusion-EKF-2 

- Version 2 of https://github.com/mithi/fusion-ekf
- This doesn't use Udacity's starter code but has the same dependencies
  - https://github.com/udacity/CarND-Extended-Kalman-Filter-Project

# Changes
- The synthetic data input is different now 
- Relative Path and file name is hard-coded so that simulator can see it
- This means no need to specify the path to the file
- Udacity has provided a simulator now

# How to use (for Mac)

1. Install term 2 simulator from here:
  - https://github.com/udacity/self-driving-car-sim/releases
2. Clone repository
```
git clone https://github.com/mithi/fusion-ekf-2.git
```
3. Make scripts executable
```
$ chmod +x mac_install.sh
$ chmod +x run.sh
```
3. Install dependencies 
```
$ ./mac_install.sh
```
4. Make Build directory Compile and run
```
./run.sh
```

5. Open simulator and select `EKF and UKF` section 
6. Check the check box `data set 2` 
7. You should see some animation and stuff representing EKF




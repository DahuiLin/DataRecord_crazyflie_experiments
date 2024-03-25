# Data records crazyflie experiments

## Overview

This dataset contains trajectory data collected from a drone during two experiments (circle and eigh-shaped circuits). The dataset provides information about the flights, including spatial coordinates, linear velocity and linear acceleration. These trajectories were recorded with the mocap libraries and the Optitrack system.

## Content
The dataset includes the following files:

- **pmm_1_lap.csv**: Point Mass Model trajectory generated by our proposed algorithm.
- **ours_1_lap.csv**: CSV file containing the polynomial approximation trajectory to track.
- **state_1_lap.csv**: Recorded flight performed by the crazyflie.

## Data Format
The data is provided in a CSV format with the following columns:

- **Timestamp**: Timestamp of the recorded data, or the time of the trajectory planned.
- **Position (x,y,z)**: Tracking position or reference position.
- **Velocity (x,y,z)**: Linear velocity of the drone.
- **Acceleration (x,y,z)**: Linear acceleration of the drone.

## Eigh-shaped Circuit (Polynomial vs PMM)

![Eight](docs/fig/ApproximatedVsPmmEight.png)


## Circle Circuit (Polynomial vs PMM)

![Circle](docs/fig/ApproximatedVsPmmCircle.png)

## Videos

# Article Experiments

- [**Watch Online**](https://youtu.be/l7ZtUI-oYCA)
  
- [**Download Video**](docs/video/VideoExperiments.mp4)
<!-- <video controls>
    <source src="docs/video/VideoExperiments.mp4" type="video/mp4">
</video> -->


# Onboard planning

- [**Watch Online**](https://youtu.be/7BG9GC9CxUc) 

- [**Download Video**](docs/video/VideoExperiments.mp4)
<!-- <video controls>
    <source src="docs/video/real_time_planning.mp4" type="video/mp4">
</video> -->

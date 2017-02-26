# ed810593

Raw experimental results of the flight experiments.

[![DOI](https://zenodo.org/badge/20743/tudoetknjt/c20cb397.svg)](https://zenodo.org/badge/latestdoi/20743/tudoetknjt/c20cb397)

## Signal Parameters

| Parameter | Value | Unit |
| --------- | ----- | ---- |
| Channel | 5 | Index |
| Center Frequency | 6489.6 | MHz |
| Bandwidth | 499.2 | MHz |
| Mean PRF | 62.89 | MHz |
| Datarate | 850 | kBit/s |
| Preamble Length | 512 | Symbols |
| Preamble Spreading Code | 9 | Index |
| Packet Acquisition Chunk | 16 | Symbols |

## CSV Description

| Parameter | Description | Unit |
| --------- | ----- | ---- |
| iso | ISO 8601 Date | - |
| unix | Unix Timestampt | s |
| id | UAV ID | - |
| motive_x | Reference System Position X | m |
| motive_y | Reference System Position Y | m |
| motive_z | Reference System Position Z | m |
| motive_vx | Reference System Velocity X | m/s |
| motive_vy | Reference System Velocity Y | m/s |
| motive_vz | Reference System Velocity Z | m/s |
| motive_ax | Reference System Acceleration X | m/s² |
| motive_ay | Reference System Acceleration Y | m/s² |
| motive_az | Reference System Acceleration Z | m/s² |
| motiveSlow_x | Reference System Position (10Hz Update Rate) | m |
| motiveSlow_y | Reference System Position (10Hz Update Rate) | m |
| motiveSlow_z | Reference System Position (10Hz Update Rate) | m |
| motiveSlow_vx | Reference System Velocity (10Hz Update Rate) | m/s |
| motiveSlow_vy | Reference System Velocity (10Hz Update Rate) | m/s |
| motiveSlow_vz | Reference System Velocity (10Hz Update Rate) | m/s |
| motiveSlow_ax | Reference System Acceleration (10Hz Update Rate) | m/s² |
| motiveSlow_ay | Reference System Acceleration (10Hz Update Rate) | m/s² |
| motiveSlow_az | Reference System Acceleration (10Hz Update Rate) | m/s² |
| atlas_x | ATLAS UWB System Position | m |
| atlas_y | ATLAS UWB System Position | m |
| atlas_z | ATLAS UWB System Position | m |
| atlas_vx | ATLAS UWB System Velocity | m/s |
| atlas_vy | ATLAS UWB System Velocity | m/s |
| atlas_vz | ATLAS UWB System Velocity | m/s |
| atlas_ax | ATLAS UWB System Acceleration | m/s² |
| atlas_ay | ATLAS UWB System Acceleration | m/s² |
| atlas_az | ATLAS UWB System Acceleration | m/s² |
| odom_x | Bebop Odometry Position | m |
| odom_y | Bebop Odometry Position | m |
| odom_z | Bebop Odometry Position | m |
| odom_vx | Bebop Odometry Velocity | m/s |
| odom_vy | Bebop Odometry Velocity | m/s |
| odom_vz | Bebop Odometry Velocity | m/s |
| odom_ax | Bebop Odometry Acceleration | m/s² |
| odom_ay | Bebop Odometry Acceleration | m/s² |
| odom_az | Bebop Odometry Acceleration | m/s² |
| us_alti | Bebop Altidue State | m |
| motive_roll | Reference System Roll | rad |
| motive_pitch | Reference System Pitch | rad |
| motive_yaw | Reference System Yaw | rad |
| motive_qx | Reference System Quaternion X | rad |
| motive_qy | Reference System Quaternion Y | rad |
| motive_qz | Reference System Quaternion Z | rad |
| motive_qw | Reference System Quaternion W | rad |
| odom_roll | Bebop Odometry Roll | rad |
| odom_pitch | Bebop Odometry Pitch | rad |
| odom_yaw | Bebop Odometry Yaw | rad |
| odom_qx | Bebop Odometry Quaternion X | rad |
| odom_qy | Bebop Odometry Quaternion Y | rad |
| odom_qz | Bebop Odometry Quaternion Z | rad |
| odom_qw | Bebop Odometry Quaternion W | rad |
| way_x | Current Waypoint Position | m |
| way_y | Current Waypoint Position | m |
| way_z | Current Waypoint Position | m |
| pos_ox | Position Control Output X | m/s |
| pos_oy | Position Control Output Y | m/s |
| pos_lx | Position Control Output Limited X | m/s |
| pos_ly | Position Control Output Limited Y | m/s |
| pos_px | Position Control P Component X | m/s |
| pos_py | Position Control P Component Y | m/s |
| pos_ix | Position Control I Component X | m/s |
| pos_iy | Position Control I Component Y | m/s |
| pos_dx | Position Control D Component X | m/s |
| pos_dy | Position Control D Component Y | m/s |
| vel_ox | Velocity Control Output X | m/s |
| vel_oy | Velocity Control Output Y | m/s |
| vel_lx | Velocity Control Output Limited X | m/s |
| vel_ly | Velocity Control Output Limited Y | m/s |
| vel_px | Velocity Control P Component X | m/s² |
| vel_py | Velocity Control P Component Y | m/s² |
| vel_ix | Velocity Control I Component X | m/s² |
| vel_iy | Velocity Control I Component Y | m/s² |
| vel_dx | Velocity Control D Component X | m/s² |
| vel_dy | Velocity Control D Component Y | m/s² |

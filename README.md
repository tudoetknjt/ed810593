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
| motive_x | Reference System Position | m |
| motive_y | Reference System Position | m |
| motive_z | Reference System Position | m |
| motive_vx | Reference System Velocity | m/s |
| motive_vy | Reference System Velocity | m/s |
| motive_vz | Reference System Velocity | m/s |
| motive_ax | Reference System Acceleration | m/s² |
| motive_ay | Reference System Acceleration | m/s² |
| motive_az | Reference System Acceleration | m/s² |
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
| alti | Bebop Altidue State | m |

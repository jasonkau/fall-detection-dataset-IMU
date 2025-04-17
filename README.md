# fall-detection-dataset-IMU
This repository contains inertial sensor data collected for fall detection research. The data were gathered using the **LSM6DSO** sensor from STMicroelectronics and include both simulated falls and common daily activities. This dataset can be used to develop algorithms for fall detection and human activity recognition.

## 📁 Dataset Overview

The dataset is divided into two main categories:

### 🧍‍♂️ Simulated Fall Events (4 types)
- Forward fall
- Backward fall
- Rightward fall
- Leftward fall

### 🚶‍♀️ Daily Activities (8 types)
- Walking
- Running
- Stair ascent
- Stair descent
- Marching in place
- Sitting down
- Sitting down quickly
- Jumping

## 📊 Data Format

All data are stored in `.xlsx` (Microsoft Excel) format. Each file corresponds to a recording of a specific activity or fall event.

### 📝 Column Descriptions

| Column Name               | Description                                             |
|---------------------------|---------------------------------------------------------|
| Index                     | Sample index (starting from 0)                          |
| Acceleration SVM          | Signal Vector Magnitude of acceleration (m/s²)          |
| Accel X                   | Acceleration along X-axis (m/s²)                        |
| Accel Y                   | Acceleration along Y-axis (m/s²)                        |
| Accel Z                   | Acceleration along Z-axis (m/s²)                        |
| Gyro X                    | Angular velocity along X-axis (°/s)                     |
| Gyro Y                    | Angular velocity along Y-axis (°/s)                     |
| Gyro Z                    | Angular velocity along Z-axis (°/s)                     |
| Angular Velocity SVM      | Signal Vector Magnitude of angular velocity (°/s)       |
| Inclination X             | Inclination angle of X-axis to the horizontal plane     |
| Inclination Y             | Inclination angle of Y-axis to the horizontal plane     |
| Inclination Z             | Inclination angle of Z-axis to the horizontal plane     |

### ⏱ Sampling Specifications

- **Sensor**: LSM6DSO (by STMicroelectronics)
- **Sampling Rate**: 100 Hz (1 sample every 20 milliseconds)

## 📂 Folder Structure
Fall-Detection-Dataset-IMU/
├── Fall Events/
│   ├── 01.Forward Fall.xlsx
│   ├── 02.Backward Fall.xlsx
│   ├── 03.Right-side Fall.xlsx
│   ├── 04.Left-side Fall.xlsx
│
├── Daily Activities/
│   ├── 01.Going Upstairs.xlsx
│   ├── 02.Going Downstairs.xlsx
│   ├── 03.Walking.xlsx
│   ├── 04.Running.xlsx
│   ├── 05.Stepping.xlsx
│   ├── 06.Sitting Down.xlsx
│   ├── 07.Quickly Sitting Down.xlsx
│   ├── 08.Jumping.xlsx
│
├── README.md 
│
├── LICENSE

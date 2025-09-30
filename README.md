# RainSense
RainSense: An Autonomous Driving Environmental Perception Dataset with Rain Intensity Labels

All data will be up loaded soon.

Sample files shared via Baidu Netdisk: RainSense_Sample.zip
Link: https://pan.baidu.com/s/1MuyGXUPx-EqcxyKFZBmaIg?pwd=lmsx
Access Code: lmsx

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17231190.svg)](https://doi.org/10.5281/zenodo.17231190)


# Dataset structure
Dataset/
    ├── light_rain/
    │   ├── scene_0/
    │   │   ├── case_000/
    │   │   │   ├── image/
    │   │   │   │   ├── image_num.jpg/
    │   │   │   ├── lidar/
    │   │   │   │   └── frame_num.csv/
    │   │   │   ├── radar/
    │   │   │   │   └── frame_num.csv/
    │   │   │   ├── label/
    │   │   │   │   └── label_num.txt/
    │   │   │   ├── context
    │   │   │   │   ├── camera_intrinsics.txt/
    │   │   │   │   ├── calib_lid_to_cam.txt/
    │   │   │   │   ├── calib_lid_to_rad.txt/
    │   │   │   │   └── rainfall_intensity.txt/
    │   │   │   └── timestamps.txt/
    │   │   ├── case_001/
    │   │   └── ...
    │   ├── scene_1/
    │   └── ...
    ├── medium_rain/
    ├── heavy_rain/
    ├── torriental_rain/
    ├── clear/
    └── ...
<img width="740" height="872" alt="image" src="https://github.com/user-attachments/assets/3d301783-c9bc-461d-9441-dd5998b0f2d4" />


# liberhand
This repository contains the ros2 packages and python scripts for liberhand (V2).


## liberhand_description

Use this command to display hand model in RVIZ2.

```
ros2 launch liberhand_description view_robot.launch.py
```

## liberhand_retargeting

These scripts are modified from [dex-retargeting](https://github.com/dexsuite/dex-retargeting).

Real-time visualization of hand retargeting via webcam.

```
python3 show_realtime_retargeting.py \
  --retargeting-type dexpilot \
  --hand-type right \
  --camera_path /dev/video0
```

![retargeting](assets/retargeting.webp)

## liberhand_driver

Hand ros2 driver writed in python, including loop joint (four bar linkage) solution.

TODO
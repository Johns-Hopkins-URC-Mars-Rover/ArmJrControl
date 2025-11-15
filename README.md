## ArmJrControl
Basic leader/follower control for ArmJr.

Do not clone this repo into your ROS workspace.

Run `leader.py` first, then `follower.py`. `leader.py` writes positions to a csv file, `follower.py` plays it back.
Make sure to set the port in the device_name to whatever you’re using (usually /dev/ttyUSB0 for Linux or COM5, COM6, etc. on Windows).

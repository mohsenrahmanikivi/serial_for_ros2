# serial_for_ros2
Serial library modified to work with ros2 humble

- If you are using this library with libsegwayrmp then just download the serial library and put it in parallel to your ROS2 humble workspace.
- Also run <code>export COLCON_WS=~/ros2_ws</code>
- run the following code:
- <code>cd ~/serial</code>
- <code>rm -rf build</code>
- <code>mkdir build && cd build</code>
- <code>cmake .. && make</code>

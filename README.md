# serial_for_ros2
Serial library modified to work with ros2 humble

- If you are using this library with libsegwayrmp then just download the serial library and put it in parallel to your ROS2 humble workspace.
- Also run <code>export COLCON_WS=~/ros2_ws</code>
- run the following code:
- <code>cd  ${COLCON_WS}/src</code>
- <code>git clone https://github.com/mohsenrahmanikivi/serial_for_ros2.git</code>
- <code>cd  ${COLCON_WS}/src/serial_for_ros2/serial</code>
- <code>rm -rf build</code>
- <code>mkdir build && cd build</code>
- <code>cmake .. && make</code>

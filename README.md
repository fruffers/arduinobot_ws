# Robot arm simulation

## To visualise URDF (xacro) model in RVIZ2 
`ros2 launch urdf_tutorial display.launch.py model:=/home/louise/Development/arduinobot_ws/src/arduinobot_description/urdf/arduinobot.urdf.xacro`
alternately:
`ros2 run robot_state_publisher robot_state_publisher --ros-args -p robot_description:="$(xacro /home/louise/Development/arduinobot_ws/src/arduinobot_description/urdf/arduinobot.urdf.xacro)"`
`ros2 run joint_state_publisher_gui joint_state_publisher_gui`

# Robot arm simulation from tutorial

## To visualise URDF (xacro) model in RVIZ2, or run the launch file
`ros2 launch urdf_tutorial display.launch.py model:=/home/louise/Development/arduinobot_ws/src/arduinobot_description/urdf/arduinobot.urdf.xacro`

alternately:

`ros2 run robot_state_publisher robot_state_publisher --ros-args -p robot_description:="$(xacro /home/louise/Development/arduinobot_ws/src/arduinobot_description/urdf/arduinobot.urdf.xacro)"`

`ros2 run joint_state_publisher_gui joint_state_publisher_gui`

![image](https://github.com/user-attachments/assets/7bf9d738-985b-4d21-8012-4f304e5d9398)

The frames are on the start of each link. The joints are invisible but can be imagined as the connection between two links.

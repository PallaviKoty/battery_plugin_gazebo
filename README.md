# battery_plugin_gazebo

Uses `battery_plugin` and `battery_consumer_plugin` packages in it.
Need to export proper plugin path before running the simulation

Steps to run the code:
```
1. cd <gazebo_battery_plugin_ws>
2. catkin_make
3. source devel/setup.bash
4. gazebo --verbose -u <path_to_world_file>/TestBatteryPlugin.world
```

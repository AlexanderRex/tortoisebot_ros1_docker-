
# Tortoisebot docker for simulation

This package needed to build and run containers for tortoise bot in simulation

## How to run:

Move to root of tortoisebot_ros1_docker directory and then

```
docker compose up
```

after this action you will have ready to use containers

Next step is to connect to each container and do the following:

### tortoisebot-ros1-gazebo

```
roslaunch tortoisebot_gazebo tortoisebot_playground.launch
```

### tortoisebot-ros1-slam

```
roslaunch course_web_dev_ros mapping.launch
```

### tortoisebot-ros1-slam

```
rosrun course_web_dev_ros tortoisebot_action_server.py
```
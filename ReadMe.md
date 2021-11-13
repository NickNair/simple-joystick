## Simple-Joystick



Steps to run this demo

```
sudo apt-get install ros-noetic-rosbridge-server

roslaunch rosbridge_server rosbridge_websocket.launch 
```

In another terminal  run

```
git clone https://github.com/NickNair/simple-joystick.git

cd simple-joystick

python3 -m http.server
```

To check the /cmd_vel topic , in another terminal run

```
rostopic echo /cmd_vel
```


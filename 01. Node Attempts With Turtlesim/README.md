# 01. Node Attempts With Turtlesim

![turtlesim](https://user-images.githubusercontent.com/56072259/164704585-6cb32f85-ffdc-484d-8be1-90a7032bb18e.png)

On this small project, i used Turtlesim and catkin. Simply created three node on the launch file.

## Usage and Visualization
I also used rqt_graph. For the purpose of extract graph of project and understand the connection of input outputs between nodes, firstly you have to initialize roscore. (Because ros need a ros master for connect nodes.)
```
roscore
```

After that, we have to run launch file (assume you're already in your <catkin_workspace> folder):
```
roslaunch launch/run_turtle.launch
```

Now we can use rqt_graph :
```
rqt_graph
```

And our projects graph call:

![2022-04-22 13_40_26-rqt_graph__RosGraph - rqt](https://user-images.githubusercontent.com/56072259/164706135-0507ce95-c233-4a01-92b5-89e4cad806ce.png)

**P.S:** I know Node 3 is redundant. However, besides bootcamp, I wanted to add something.

# 02. Publisher and Subscriber with Python

Its a simple tutorial that ros publisher and subscriber's data transfer.

## Usage

```
cd script

chmod +x messagePublisher.py

chmod +x messageSubscriber.py
```

After that we can run python codes. 

```
python3 messagePublisher.py
python3 messageSubscriber.py
```

On the other it would be good if you echo the messages in the other terminal.

```
rostopic echo /messageTopic
```

![2022-04-22 21_08_22-3 1 1  Catkin - OneNote](https://user-images.githubusercontent.com/56072259/164773317-72c12a3b-512a-487f-ac76-75947e0915d0.png)

And if you want to show the project as graph :

```
rosrun rqt_graph rqt_graph
```

![2022-04-22 21_09_30-3 1 1  Catkin - OneNote](https://user-images.githubusercontent.com/56072259/164773322-e4e31f32-6e8b-4b57-8608-cd63eb9cf87a.png)

## Reference
* [Part 3: Create Your First ROS Publisher and Subscriber Nodes](https://medium.com/swlh/part-3-create-your-first-ros-publisher-and-subscriber-nodes-2e833dea7598)

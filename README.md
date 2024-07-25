This project deals with multi robot navigation and utilizing cartographer for both localization and SLAM.

1. Multiple turtlebots are used with different namespaces.
2. Instead of AMCL , to achieve more accuracy cartographer was modified to use for localization. A improvement of approx 15% was noticed.
3. In addition the pbstream feature of cartographer was used to achieve localization even if the robot was randomly placed in an mapped environment. Within a short time the smulation and real robot are able to synchronize even if both started from different locations.
4. In addition colission cone was also integrated to visualize the obstacle avoidance when rendered in a mixed reality environment in Unity with a holo-lens.
5. Multiple turtlebots were successful in collaborating in pick and drop operations in a industrial warehouse.



[Screencast from 26-06-24 10_45_32 PM IST.webm](https://github.com/user-attachments/assets/c86ed163-9506-4c30-9b1f-de3fcb145da9)

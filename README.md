# dataset-smarphone-sensor-segmentation-for-road-surface-monitoring
This datasen consist of csv files. 
Records motion sensors (accelerometer, gyroscope, magnetometer, and gravity) and GPS from smartphones which are brought while driving motorcycle.

column  column-name 
1       accelerometer x
2       accelerometer y
3       accelerometer z 
4       gyroscope x
5       gyroscope y
6       gyroscope z
7       magnetometer x
8       magnetometer y
9       magnetometer z
10      orientation value a (azimut)
11      orientation value p (pitch)
12      orientation value r (roll)
13      grafity x
14      grafity y
15      grafity z
16      latitude
17      longitude
18      speed
19      timestep
17      timestamp
18      class - groundtruth
19      class - segmentation result


class   class-name
0       flat-road
1       pothole
2       speedbump
3       rough surface
4       human movement
5       engine vibration

use SensorLabeler.exe to open the csv files

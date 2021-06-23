# final
## Intro 
Total 5 stage for this project. At the start and the end of each stage, car will use XBee to send the message to host.

## Test Environment
![](https://i.imgur.com/MtEoNIc.jpg)
![](https://i.imgur.com/DW1Cac4.jpg)


## Stages
### stage1
Use opencv to detect the black line. By using line regression, the camamra can know the car should be fixed to right or left.
Use ping to detect the distance from apriltag to car. if the distance is shorter than 50cm, the car stop.

### stage2
Turn the car into opsite direction.

### stage3 
Use opencv to detect the Apriltag and fix the direction of mbed car. The tag I used is 36h11. 
Use ping to detect the distance from apriltag to car. if the distance is shorter than 40cm. Start stage4.

### stage4
Turn the car to right 90 degrees.

### stage5
Use opencv to detect the Apriltag and fix the direction of mbed car. The tag I used is 36h11. 
Use ping to detect the distance from apriltag to car. if the distance is shorter than 20cm, the car stop.

## Test Result
https://drive.google.com/file/d/1GdKmn7OBhSV7CJoYXWyjml_q45apzYUz/view?usp=sharing
![](https://i.imgur.com/jHPVyQh.jpg)

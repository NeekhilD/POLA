#  Photogrammetry Using LIDAR + ARDUINO `(POLA)`

[![forthebadge](https://forthebadge.com/images/badges/made-with-c-plus-plus.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/check-it-out.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/open-source.svg)](https://forthebadge.com)

`1.` <img src="https://user-images.githubusercontent.com/26859754/160553016-117dd5ed-b7cf-4b82-a406-24accdca9507.png" width="500"/></br>
`2.` <img src="https://user-images.githubusercontent.com/26859754/160553172-300a27d5-dfde-4a4d-bf8a-66fbd52be52d.png" width="500" /></br>
`3.` <img src="https://surveyinggroup.com/wp-content/uploads/2021/05/lidar-min.png" width="500" />



## Photogrammetry
> "Photogrammetry is the science and technology of obtaining information about the physical environment from images, with a focus on applications in surveying, mapping and high-precision metrology. The aim of photogrammetry is to provide automated or semi-automated procedures for these engineering tasks, with emphasis on a specified accuracy, reliability, and completeness of the information."


## Arduino code
Thank to the Servo.h and LIDARLite.h Arduino libraries, the code to control these elements is made much easier. The basic work-flow of the code is the following:

 ``` Init. lidar, servos and serial; 
  For YawAngle = 0 to 180
  For PitchAngle = 0 to 180 
  Compute coordinates;
  Send value;
  ```
  
The micro-controller only knows the angles of the servos and the distance to the obstacle. A small amount of computation is required to convert the yaw angle, pitch angle and range information into much more usable X, Y and Z coordinates.



# Future Application
## Can Be Deployed in `ARDUSAT`

<img align="center" width="300px" src="https://i.pinimg.com/originals/9d/6a/db/9d6adb9b5865a9902d8ea2eeb515c1e5.png"/>

> ArduSat is an Arduino based nanosatellite, based on the CubeSat standard. 
It contains a set of Arduino boards and sensors.
The general public will be allowed to use these Arduinos and sensors for their own creative purposes while they are in space.



<!--
# FRAME.IO
The modern video workflow, `(re)defined`
<img align="center" width="800px" src="http://discountcode.online/wp-content/uploads/2018/12/frame.io-promo.png"/></br>
 -->










## With The Help Of  


<!--<img align="left" width="50px" src="https://user-images.githubusercontent.com/26859754/160555283-cc38287b-f8b1-460a-beba-f0c3439c039f.png"/>-->
<img align="left" width="20px" src="https://comma.ai/comma-white.png"/>
<img align="left" width="50px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/87/Arduino_Logo.svg/2560px-Arduino_Logo.svg.png"/>
<img align="left" width="150px" src="https://www.openlidar.net/wp-content/uploads/2016/05/OpenLidarLogoText.png"/>
<img align="left" width="50px" src="https://micronaut.io/wp-content/themes/micronaut/img/astronaut.png"/>
<img align="left" width="30px" src="https://assets-global.website-files.com/60acbb950c4d6606963e1fed/60c1f214c64e0975106806fb_flaskapi.svg"/>
<img align="left" width="120px" src="https://image4.owler.com/logo/ardusat_owler_20160228_024534_original.png"/>
<img align="left" width="120px" src="https://dka575ofm4ao0.cloudfront.net/pages-transactional_logos/retina/22145/azA7aad0SPiJCTOHAtuc"/>
<img align="center" width="120px" src="https://tooljet.com/img/logo/text-logo-blue.svg"/>

# Machine-learning-approach-to-monitor-departure-of-public-transport-buses

Machine Learning approach to monitor departure of buses near bus bay 

Problem Statement: Nowadays majority of the people prefer other means of transportation instead of traditional public bus transportation. The lack of reliable and safe means of transportation is clearly mentioned as one of the contributing factors leading to frustration and anger in a large number of people. Improper halt and speeding up harshly at the bus stop are some of the primary problems that the passengers face these days. Due to this, Women, children, Senior citizens and physically challenged passengers are not able to board the buses with ease and we also observe that most of the youngsters are risking their lives while running behind the buses to catch it. 

Solution: This system consists of camera attached to every bus bay which captures the bus number as well as the bus route if the bus doesn’t stop within 10 meters radius of the camera, appropriate action is taken and thus providing safe boarding for children ,women ,senior citizens, physically challenged people. 



Technologies Used: OpenCv, Machine Learning Algorithms.

So finally we feed our system with a video frame consisting of public transport buses. Our System identifies the bus using single shot algorithm and calculates the of which the bus is stopped at the bus stop and gives alerts if the stopping time is very less. By this system we prevent the inappropriate boarding.

WorkFlow:
1. A video frame is given as an input to our system. The video frame is divided into seperate images.

![Picture1](https://user-images.githubusercontent.com/25890584/74860444-a3c1e280-5316-11ea-873b-387a45fde5fa.png)

2. On each image, Single shot detector algorithm is employed where this algorithm basiccally identifies the objects present in the image.

![Picture3](https://user-images.githubusercontent.com/25890584/74860445-a3c1e280-5316-11ea-8265-4affa08827f5.png)

3.The System returns the amount of time the public transport bus present at the bus stop and gives alerts if the stopping time is very less

![Picture4](https://user-images.githubusercontent.com/25890584/74860448-a45a7900-5316-11ea-9939-1dea827901b0.png)

project results are there in the folder named output result

References:
https://www.pyimagesearch.com/2017/09/11/object-detection-with-deep-learning-and-opencv.
https://www.ijera.com/special_issue/ICIAC_April_2014/EN/V7/EN-2604549.pdf
http://academicscience.co.in/admin/resources/project/paper/f201706271498554084.pdf
http://www.kscst.iisc.ernet.in/sppArchive/public/Abstract/038/8011.pdf
http://www.ijemr.net/DOC/BusIdentificationModuleForVisuallyImpaired(452-455).pdf

					  



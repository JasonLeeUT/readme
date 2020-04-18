# CSC2504 Final Image Competition
Jianfeng Li   

This project is based on assignment 3. I create a new situation where two snowmen are under sun. The father is lifting his hand to protect his son from the sunshine.   

##Contribution 1:  
A new json file and a new situation.

##Contribution 2:   
Make the sun look more real by detecting the reflection part and replace it with surrounding color.

##Contribution 3:  
Change the background color to light blue.

##Contribution 4:  
Add impluse noise to the image to imitate snow.

##Contribution 5:  
Use mean filter to soft snowman edge.

##Note:  
Since the noise is produced randomly, the image generated every time may be slightly different.

##How to run:  
Enter the project folder, make a new "build" folder. Then enter "build".   
cmake ..  
make  
./raytracing  
Then you can generate the final image "Snowman.ppm"  
Besides, this program is run under Mac. If you use Windows, you may need to change the path in main.cpp.


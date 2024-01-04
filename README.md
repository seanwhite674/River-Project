# River-Project
Modelling a section of the Amazon River
This is a project I completed in a course called Modelling in Applied Mathematics.
I analysed the data of a river from 2000 to 2020 using Google Earth Pro
![Google Earth River](https://github.com/seanwhite674/River-Project/assets/110498155/564213f3-41e7-4354-8ac7-e32275583889)
I imported this data into excel and transferred to Python
![Screenshot 2024-01-04 192631](https://github.com/seanwhite674/River-Project/assets/110498155/fc973146-3868-416a-9273-29a857a802d3)

The basic premise behing our model:
##
  1- I moved each point of the river out in the orthonormal direction of the point by an amount proportional to a constant 
  times the square root of the width of the river at that point and the curvature at that point
  ![Proof of Concept width](https://github.com/seanwhite674/River-Project/assets/110498155/62e1b3ca-45b5-4ed9-8032-0d6b3b07fd63)
  ##
  2- To find this constant I used our previous data collected to see which constant caused our model to line up best with the 
  data collected.
  ![Finding the constant B=50](https://github.com/seanwhite674/River-Project/assets/110498155/88a09235-b2d4-498e-934a-d8bcdae880c2)
  ![Finding the constant](https://github.com/seanwhite674/River-Project/assets/110498155/7d91a181-cdb4-4593-8308-1b00c626ee64)
 ##
  3- I then made a python model for this river.
##
![myanimation](https://github.com/seanwhite674/River-Project/assets/110498155/39923922-5c91-44e7-991d-946df36297a7)
![205020502050](https://github.com/seanwhite674/River-Project/assets/110498155/9ef08b07-4f31-4051-8745-86213fedcaa7)
![208020802080](https://github.com/seanwhite674/River-Project/assets/110498155/82dc4166-41f2-4098-acec-d5ed7819474c)



# River-Project
Modelling a section of the Amazon River
This is a project I completed in a course called Modelling in Applied Mathematics.
I analysed the data of a river from 2000 to 2020 from Google Earth Pro



I imported this data into excel and transferred to Python
The basic premise behing our model:
  1- I moved each point of the river out in the orthonormal direction of the point by an amount proportional to a constant 
  times the square root of the width of the river at that point and the curvature at that point
  2- To find this constant I used our previous data collected to see which constant caused our model to line up best with the 
  data collected
  3- I then made a python model for this river
  4- I created an animation of the river



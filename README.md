# people-counter-in-a-vedeo-for-pedestrian
environment: python:3.7.1  opencv:4.1.0  operation system:windows 10
this project make some provement for others who use dnn to complete
the orginal project:https://www.pyimagesearch.com/2018/08/13/opencv-people-counter/
the following is the improvement what I have done:
   1.set the line to count the people: original is in the middle, but I set to the place  what I want
   2.original project can't judge people direction correctly, therefore, I set a dictionary, which 
      store the frames of specific id, to help judge the right direction(up or down)
   3.original project can't recognize people and other things corrects in a proper or low confidence. 
      So I have do a Laplace sharpening enhancement that can make a unbelievable improment in recognization.

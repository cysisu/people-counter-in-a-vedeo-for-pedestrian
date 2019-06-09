# people-counter-in-a-vedeo-for-pedestrian  
environment: python: 3.7.1  opencv: 4.1.0  operation system: windows 10<br>
this project make some provement for others who use dnn to complete<br>
the orginal project:https://www.pyimagesearch.com/2018/08/13/opencv-people-counter/<br>
the following is the improvement what I have done:<br>
   >1.set the line to count the people: original is in the middle, but I set to the place  what I want<br>
   >2.original project can't judge people direction correctly, therefore, I set a dictionary, which<br>
     >> store the frames of specific id, to help judge the right direction(up or down)<br>
>   3.original project can't recognize people and other things corrects in a proper or low confidence.<br> 
     >> So I have do a Laplace sharpening enhancement that can make a unbelievable improment in recognization.<br>


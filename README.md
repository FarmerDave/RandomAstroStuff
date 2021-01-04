# RandomAstroStuff
Random astronomy/astrophotography stuff

## Driving Miss Stellarium

A question on CloudyNights about using Stellarium to save viewing targets led me to write a brief tutorial on setting up remote control on Stellarium and writing a down-and-dirty WPF app to drive Stellarium using its remote control Web API.

## Meteor Hunter

A question on CloudyNights about using motion detection to find Meteors in videos led me to adapt a program I wrote to sift through hours of video of my hummingbird feeder (using the emgu C# wrapper to OpenCV).  

Need to add a readme for this, but if you download it, make sure you set the following options:

```
Edge Detection, CannyL2Gradient = True
Processing Pipeline, Blur = False
General, SkipFrmaes = 5


```


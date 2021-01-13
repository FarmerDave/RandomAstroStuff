# RandomAstroStuff
Random astronomy/astrophotography stuff

## Driving Miss Stellarium

A question on CloudyNights about using Stellarium to save viewing targets led me to write a brief tutorial on setting up remote control on Stellarium and writing a down-and-dirty WPF app to drive Stellarium using its remote control Web API.

## Meteor Hunter

A question on CloudyNights about using motion detection to find Meteors in videos led me to adapt a program I wrote to sift through hours of video of my hummingbird feeder (using the emgu C# wrapper to OpenCV).  

Changes in Latest Version 0.3:

- Changed primary detection method from line detection, which was subject to false positives, missing meteors, and all-around not that robust.  Replaced it with motion detection with some averaging and background subtraction thrown in for good measure.
- Tweaked the workflow and parameters based on the assumption you won't be putting 4K video in.  It works, it's just slow - use Handbrake to convert it just for detection.
- Added different levels of options because the options dialog was getting overwhelming: Basic, Advanced, and Complete.  Advanced needs more work.
- Dark and Astro themes - half-ass, as it's a WinForms app.  Will redo it in WPF some day, promise.
- Addressed some memory issues, probably added others
- Option to "Animate detections" - when this is checked, an animated gif is created that shows the original video frames outlined by the bounding box of all the motion detection rectangles for the frames that make up the clip.




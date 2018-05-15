# II_Project_Final

Instructions for testing patches:

1) Open the three patches in the main folder: ProjectionDisplayV2.maxpat, OutsideDetectionWebcam.maxpat, InsideDetectionInvert.maxpat
2) ProjectionDisplayV2 should automatically load the .MOV files from the folder in which the patch is saved and send the video to either the jit.pwindow or jit.window, whichever is selected with a red dot, so select in the GUI accordingly
3) The last thing to do is in OutsideDetectionWebcam *and* in InsideDetectionInvert, open the webcam and Kinect and bang the toggle to start sending the feeds to ProjectionDisplayV2

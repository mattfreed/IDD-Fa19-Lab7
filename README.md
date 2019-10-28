# Video Doorbell, Lab 7

*A lab report by Matt W. Freed*

### In This Report

1. Upload a video of your version of the camera lab to your lab Github repository
1. As usual, update your class Hub repository to add your [forked IDD-Fa18-Lab7](/FAR-Lab/IDD-Fa18-Lab7) repository.
1. Answer the questions in-line below on your README.md.

## Part A. HelloYou from the Raspberry Pi

**a. Link to a video of your HelloYou sketch running.**

https://www.youtube.com/watch?v=Mi93wV90XF4


## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**

In order to load the webcam module we had to call "var NodeWebcam = require("node-webcam");

Code was also added for webcam setup. These include default options located in the var opts variable and starting up the webcame by calling NodeWebcam.create(opts);.

Along with this, functionality on the webpage had to be added. This functionality can be seen at the line containing socket.on('takePicture', function(){ var imageName = new Date().toString().replace...;


Video Doorbell:

https://www.youtube.com/watch?v=AqBkUx28rXM


**b. Include a video of your working video doorbell**

## Part C. Make it your own

**a. Find, install, and try out a node-based library and try to incorporate into your lab. Document your successes and failures (totally okay!) for your writeup. This will help others in class figure out cool new tools and capabilities.**

**b. Upload a video of your working modified project**

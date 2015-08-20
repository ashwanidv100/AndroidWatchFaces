## AndroidWatchFaces

A conversation with someone got me curious about using OpenGL for Android Wear watchfaces, so I wrote a sample or two using some graphics code I had laying around. 

The OpenGL is ported from some existing WebGL code. JavaScript to Java?! I know right. Still in the process of filling it out. It's done enough right now to support the required functions on the watchfaces. 

### Watch Faces
##### Time Mesh
Spring mesh simulation. Responds to accelorometer. 

![alt tag](https://raw.githubusercontent.com/chaoticbob/AndroidWatchFaces/master/images/springs.png)

##### Fluids2D
2D fluids simulation. Responds to accelorometer. Looks similar to the screenshot below. Will get real screenshot soon.

![alt tag](https://raw.githubusercontent.com/chaoticbob/AndroidWatchFaces/master/images/fluids.png)

##### Particles
(not finished)

### Building
Project files are Android Studio 1.1. 

### Devices
Samples were tested on a LG G watch. Haven't had a chance to run on emulator yet.

### How Come the WatchFaces Don't Tell Time?!
These samples are just a starting point for learning! I'll add time telling soon!

### License
License is BSD/MIT/Boost. 

Have fun.

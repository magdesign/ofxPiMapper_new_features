# ofxPiMapper_new_features
must run on RPi3 and Linux (no plans for RPi4 so far)

Reference Projects:

ofxPiMapper
https://github.com/kr15h/ofxPiMapper

TCPiMap
https://github.com/CyrCom/TCPiMap

LPMT
https://github.com/pierrep/lpmt

KarmaMapper
https://github.com/Karma-Kusala/karmaMapper


# To Do:

Add following functions to the existing ofxPiMapper:

- Sync (several RPis with ofxPiMapper will share their timecode (boradcast, no IP entering!) to run in sync, maybe based on this: https://github.com/turingmachine/omxplayer-sync or this: https://github.com/bmoren/node-omxplayer-sync
see here: https://github.com/kr15h/ofxPiMapper/issues/117#issuecomment-591306363


- Soft Edge overlay, so you could drag a softedge blur from the edges of a quad:
![](https://github.com/magdesign/ofxPiMapper_new_features/blob/master/softedge.gif?raw=true)
- Fullscreen quad, select a quad, hit shift+f, this quad will go fullscreen:
![](https://github.com/magdesign/ofxPiMapper_new_features/blob/master/fullscreen2.gif?raw=true)
- Circular surface control (center point adjust):
![](https://github.com/magdesign/ofxPiMapper_new_features/blob/master/circular.gif?raw=true)

- Remote Control (control the mapping surfaces from another computer over tcp, there is an existing example, works great on Linux, but I am not able to build and run this for windows, can you build this?.


- .png overlay mask, overlay a .png with alpha over an existing quad


- Grip warp surface, rpi powerfull enough?, see this paper: https://www.ronenbarzel.org/papers/warp.pdf
![](https://github.com/magdesign/ofxPiMapper_new_features/blob/master/grid_warp.gif?raw=true)

- Pixel to DMX Mapping, create a quad which reads out the color of where its positioned over the video and send dmx signals (https://github.com/MadSciLabs/ofxDmxUtils).

- ofx timeline (enough performance?) to set pictures and videos behind each other....

- USB camera feed (to use RPi as mapping-box for other streams)


People who could help on this:

https://github.com/CyrCom  => asked, is motivated

https://github.com/kr15h => might not have enough time

https://github.com/c-mendoza => circular stuff?

https://github.com/lewislepton => asked via email.

https://github.com/pierrep/ => currently working on the additions!

If you can code one of the features, contact me!

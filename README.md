# ofxPiMapper_new_features

References:

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

- Soft Edge overlay, so you could drag a softedge blur from the edges of a quad
![](https://github.com/magdesign/ofxPiMapper_new_features/blob/master/softedge.gif?raw=true)
- Fullscreen quad, select a quad and with hitting a button this quad will go fullscreen
![](https://github.com/magdesign/ofxPiMapper_new_features/blob/master/fullscreen.gif?raw=true)
- .png overlay mask, overlay a .png over a quad

- Circular surface control (center point adjust)
![](https://github.com/magdesign/ofxPiMapper_new_features/blob/master/circular.gif?raw=true)
- Remote Control (control the mapping surfaces from another computer over tcp, there is an existing example)
- Sync (several RPis with ofxPiMapper will share their timecode (boradcast, no IP entering!) to run in sync, maybe based on this: https://github.com/turingmachine/omxplayer-sync or this: https://github.com/bmoren/node-omxplayer-sync
- Grip warp surface, rpi powerfull enough?, see this paper: https://www.ronenbarzel.org/papers/warp.pdf
![](https://github.com/magdesign/ofxPiMapper_new_features/blob/master/grid_warp.gif?raw=true)

- USB camera feed (to use RPi as mapping-box for other streams)


People who could help on this:

https://github.com/CyrCom  => asked, is motivated
https://github.com/kr15h => might not have enough time
https://github.com/lewislepton

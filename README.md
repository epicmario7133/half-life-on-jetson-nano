# half-life-on-jetson-nano
guide + file to run half life on the jetson nano

```
git clone https://github.com/epicmario7133/half-life-on-jetson-nano.git
cd half-life-on-jetson-nano/
```
After which download half life from steam via pc, and then move the valve folder (located inside the game files) to the game_launch folder

The game_launch folder should look like this:

 - client_arm64.so
 - game.cpp.1.o
 - hl_arm64.so
 - libmenu.so
 - libref_gl.so
 - libref_soft.so
 - libxash.so
 - xash3d
 - xash3d.sh
 - valve/
 
Copy  hl_arm64.so in the _valve/dlls_ directory.

Copy  client_arm64.so in the _valve/cl_dlls_ directory.

And now you can start the game:
```
bash xash3d.sh
```
# File sources
https://github.com/FWGS/xash3d

https://github.com/FWGS/hlsdk-xash3d

https://github.com/FWGS/xash3d-fwgs

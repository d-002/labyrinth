# maze

!(Logo)[https://user-images.githubusercontent.com/69427207/220354305-eec77b99-6ca9-466c-9d82-48938836f4de.png]

Doom-like maze with randomly generated levels. School project.

## Trailer
*coming soon*

## Overview
This project is a Python game where you try to find the exit gate to a maze and go to the next level, where a bigger maze will be waiting for you. But beware, evil monsters will try and stop you from doing so!

There is an infinite amount of levels, generated by an algorithm coded for a school project. The main file you will need to run is `main.pyw`. It will require you to install the required modules: `pip install requirements.txt`.  
You can also find two other python files: `entities.py` (entities handling) and `maze.py` (maze generation).  
The remaining python files were used in the development process in order to resize images. You don't need them.

## Handling and options
Pan with the mouse, left click to attack and right click to open doors.  
WASD to move around.

### Editing options
You can edit the file `files/options.txt` to change setting like the keys used to move (order: up, left, down, right), FOV, render distance.

The render distance doesn't have to be set higher, as the fog will hide most of the maze. It is also very unlikely that you will get long straight paths, which are the only reason why you would need high rander distance. I recommend to only change this to lower it if you are playing on a potato.

### Defaults
- move_keys: wasd
- fov: 70
- render_distance: 20

## Sources

**Textures**: [doomworld.com](https://www.doomworld.com/forum/topic/99021-doom-neural-upscale-2x-v-10)  
**Music**: myself (youtube video will be available soon)  
**SFX**: edited from [pixabay.com](https://pixabay.com)  

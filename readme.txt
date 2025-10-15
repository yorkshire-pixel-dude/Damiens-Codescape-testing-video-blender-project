Opening the .blend file in Blender (I used vers 4.32 as more recent ones crash for me)...

In the Video Sequencer editer at the bottom which is in Sequencer mode

If you click in the time stamps and drag you can scrub through the video

Hold Ctrl + x mouse expand/contracts time, y expands/contracts verically the channels

To goto a specific frame click the Current Frame number just to the left of the start frame in the bottom right of the app

If you single click any video press G to move and can then press x or y to restrict its movement

Channel 1 is your original video'ish but it now at 60 FPS but same duration, with channel 1 selected if you goto to frame 1521 you will see the Opacity in Compositing is yellow indicating it is key framed, advancing key frames you will see its value drop to 0.5 at frame 1771 at which it remains for the rest of the video. Also there is a hard cut in your video at 1771, with the 2nd part of video dragged right to frame 2080 but the first frame is then dragged back to 1772. The decline in opacity and static 1st frame are so the animation of python script (channel 2) and subsequent scipt hightlightings are more visible

Animation of python script (channel 2) has a Cross Transistion (channel 5) with the python script highlighting background (just white python code, channel 3)

The green selected bits of of python code are obviously on channel 4.  This was originally a single animation but quickly realised this could be single PNGs but I used little bits of video as I encountered some weird buffering problems with just PNGs

In the Video Sequencer editer at the top which is in Preview mode you obviously just the results of my fumblings :-)

Enjoy!

# UiPath-VidCreator

UiPath agent process to operate Open Broadcast Studio to record short tutorial/ how-to style videos and upload them to youtube.

Ctrl + 1: Open OBS, get a video topic from user input, add to referenced text file in obs scene, center topic text in scene, switch to scene 1, start recording.
Ctrl + 2: Stop recording
File Watch on output: if finished recording, find latest file

TODO: 
* Upload latest file to Youtube with title, description, tags, etc.
* Respond to original forum post or slack message with video link
* Allow addition of text files, workflows, screenshots, etc to be linked to a video and uploaded somewhere for viewer's reference.
* Allow addition of links to be added to associate to a how-to

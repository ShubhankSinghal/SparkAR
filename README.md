# SparkAR

This project is made for the facebook AR Hackathon, that took place on the Devpost platform.

Link to the Hackathon: https://fbar2.devpost.com/

Link to my submission: https://devpost.com/software/world-filter

##Inspiration
As we have to make a world filter, so it is kinda cool to be in another place. So, I thought to work on this.

##What it does
As the filter loads, first its checks if front camera is opened or back. If front camera is opened, it asks to switch the camera through custom instructions and after changing to back camera, it asks to move the device to have a look. Then the environment or surrounding of the user changes. It have UI Picker. So there are two options: One for day-time and another for night time. During night, snowfall also takes place using particle emitter. There is a slow background music to match the theme.

##How I built it
First, the 3D model was prepared. The sky is made of sphere. while the ground is made from the plane in blender along with rest of the things. Then the tectures were applied. And in SparkAR, placed the object in world environment along with particle emitter. Emitter was given a texture of snow to give a effect of snowfall. A speaker was added, which plays the background music. I used script for the UI Picker and the variable from the script is used in the patches to change the textures. Custom Instructions are implemented using patches.

##Challenges I ran into
Firstly, The 3D object was not so easy to work on, compression took most of the time. Then, I was planning to use DeviceMotionModule to make movement with the device moment but no result was obtained.So, then I switched to UI Picker, to give a good world AR effect. As my system is old, so all the working took so long to complete.

##Accomplishments that I'm proud of
The filter which I made is what I am proud of. Because they were all new concepts eg UI Picker, DeviceModule, Scripting, 3D-models, exporting, compression. But after the effect was completed, it was a satisfactory feeling.

##What I learned
The things I learnd are: Blender SparkAR - UI Picker Sound Speaker texture Compression Filter uploading Using Patches Working with Scripting and many more things.

##What's next for World filter
I will be working on this filter, if some-how I get a way to move a 3D object based on device motion. And creating somewhat more enhanced scenery.

##Built With
blender
sparkar


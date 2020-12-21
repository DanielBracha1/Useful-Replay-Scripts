# Marketing Banner

## What is it? 

A hand (with multiple different sprites to choose from) that will follow the mouse input entered during your video. 

![alt-text](https://media.giphy.com/media/1XOzf46BVNCtBZpOJ2/giphy.gif)
    
## Why use it?

When uploading your recording to playground it will be hard to see where inputs are being entered without a cursor visable. Using a sprite that follows where the inputs are placed helps the viewer understand how the game is being controlled.

## How to Use

1. Check what your scene camera's Projection type is (Orthographic or Perspective), and download the package version that matches it. 

2. Drag the package into your project (you do not need to import the scenes folder, as this just contains an example)

3. Drag the 'LunaFingerImage' prefabs onto your scene's camera as a child object, and place the 'LunaFollowTouchInput' anywhere in the hierarchy. 

4. Select the LunaFollowTouchInput prefab in your scene. Drag your scene's camera into the 'Main Camera' field, and the LunaFingerImage prefab that's in the scene into the 'Image To Move' field. 

<img src="https://i.imgur.com/xGIh0r1.jpg" width="500">

5. To make sure the hand appears infront of objects in your game, set the LunaFingerImage's Sorting Layer to that of your UI/last rendering layer (or make a sorting layer if you dont have one). 

<img src="https://i.imgur.com/l3lJwIF.jpg" width="500">

From here you're all good to go!

## Options & Adding New Sprites

**Options:**

Follow Speed: Affects how fast the hand moves towards the mouse location

Go Back Speed: Affects how fast the hand moves back to its starting position from the mouse location

Image To Use: Selects the sprite for the hand object

Size To Use: Scales the sprite size by setting the SizeType to either Small, Medium, Large or Custom. If you select custom you will need to enter your own dimensions inside the script within the 'SetImageSize' function.

Only Show Hand When Using: Ticking this option will mean the hand appears directly upon the mouse location as soon as an input is made. (Unticked the hand will move to the mouse from its starting position upon an input, and then back again)

## Sprites

The Hand fields contain the sprites for selection in the 'Image To Use' drop down. If you wish to change the sprites to your own you can add your own in these fields, though the ones included are part of our [free asset pack](https://github.com/LunaCommunity/Luna-Free-Assets) so feel free to use the ones provided!

<img src="https://i.imgur.com/ctT64dn.png" width="500">

If you wish to add your own, make sure the hand image has it's finger placed upon the centre of the image (and that the image has equal width & height. Example below:

<img src="https://i.imgur.com/TkGNstO.png" width="500">

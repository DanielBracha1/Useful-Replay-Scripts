## What is it? 

A hand (with multiple different sprites to choose from) that will follow your mouse input or a GameObject's movements during your video.

![alt-text](https://media.giphy.com/media/1XOzf46BVNCtBZpOJ2/giphy.gif)
    
## Why use it?

When uploading your recording to playground it will be hard to see where inputs are being entered without a cursor visible. Using a sprite that follows where the inputs are placed helps the viewer understand how the game is being controlled.

## How to Use

1. Drag the package into your project (you do not need to import the scenes folder, as this just contains examples)

2. Drag the 'LunaFingerImage' prefabs onto your scene's canvas as a child object, make sure it is the last object in the canvas hierarchy to ensure it appears over other UI elements! 

<img src="https://i.imgur.com/NDtljq7.jpg" width="500">

3. Next drag the 'LunaFingerFollowMouseInput' into anywhere in the hierarchy, and select it it in your scene. Drag your scene's camera into the 'Main Camera' field, drag the canvas that you put the LunaFingerImage prefab under into the Canvas field, and then the LunaFingerImage prefab that's in the scene into the 'Luna Finger Image' field. 

(If you are planning on using the added functionality of having the finger follow an object in the scene, drag whatever GameObject you wish the finger to follow into the 'To Follow' field)

<img src="https://i.imgur.com/PQjMjsk.jpg" width="500">

From here you're all good to go! 

**Note:** Read on below on how to have the finger follow a GameObject rather than the position of your mouse!

## Following Objects & Other Options

In some occasions your mouse input is not aligned with the GameObject being moved, making the position of the finger look strange. 

To follow a GameObject instead, whilst holding your mouse down also hold down the spacebar. You will notice that the finger is now following your object instead! (Example of this behaviour below)

![alt-text](https://media2.giphy.com/media/IioRVND2aodw51WVIL/giphy.gif)

If you encounter errors whilst holding space this likely means you have not added the GameObject you wish the finger to follow to the "To Follow" field in your scene's LunaFingerFollowMouseInput prefab. 

**Options:**

Show Hand: If unticked the Hand will no longer appear on screen

Follow Speed: Affects how fast the hand moves towards the mouse location

Go Back Speed: Affects how fast the hand moves back to its starting position from the mouse location

Image To Use: Selects the sprite for the hand object

Size To Use: Scales the sprite size by setting the SizeType to either Small, Medium, Large or Custom. If you select custom you will need to enter your own dimensions inside the script within the 'SetImageSize' function.

Only Show Hand When Using: Ticking this option will mean the hand appears directly upon the mouse location as soon as an input is made. (Unticked the hand will move to the mouse from its starting position upon an input, and then back again)

## Changing & Adding New Sprites

The Hand fields contain the sprites for selection in the 'Image To Use' drop down. If you wish to change the sprites to your own you can add your own in these fields, though the ones included are part of our [free asset pack](https://github.com/LunaCommunity/Luna-Free-Assets) so feel free to use the ones provided!

<img src="https://i.imgur.com/ctT64dn.png" width="500">

If you wish to add your own, make sure the hand image has it's finger placed upon the centre of the image (and that the image has equal width & height. Example below:

<img src="https://i.imgur.com/TkGNstO.png" width="500">

# Marketing Banner

## What is it? 

A marketing banner is a strip of colour and text at the top of your video. 

![alt-text](https://i.imgur.com/wvmHDvh.png)
    
## Why use it?

A marketing banner is great way to present a challenge or message to the user, which doesn't interrupt with your gameplay and stands out! For example, you could let the user know that "Only 1% of people can complete this game" as a way to peak their interest. 

## How to Use

1. Download and then drag the package into your project

2. Drag the 'MarketingUI' prefab onto your scene's canvas

3. Expand the 'Fonts' array in the inspector, increase the number to how many fonts you want to include. Drag the tff files into the elements created after setting the array size.

![alt text](https://i.imgur.com/xsCgG1B.jpeg)

4. After you add your fonts open up the 'ReplayTopBanner.cs' script (will be in the same folder as the 'MarketingUI' prefab). Inside the 'FontNames' enum add the names of the font files you added to the array. 

    NOTE: Make sure to spell the font's name the same as it appears in Unity, BUT use _ instead of spaces and remove any other special characters (don't remove underscores)
    E.g.: Cinzel-Bold -> CinzelBold   xylitol front -> xylitol_front
![alt text](https://i.imgur.com/7bhKFpi.jpg)

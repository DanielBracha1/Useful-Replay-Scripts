# Audio Selection
## What is it? 

The Audio Selection prefab allows you to add all music files in a given folder to an enum, which can then be used to change the music playing in the scene. There is an optional start time field which can be used to offset the time at which the music starts.

    
## Why use it?

Audio makes a big impact on video performance. 

You may want to have the flexibility to choose different music for your videos, but want the ease-of-use that comes from a drop down based on the current music in your folder. 

## How to Use

1. Download and then drag the package into your project

2. Drag the 'AudioManager' into your scene. 

You will see an error at this stage - don't worry, this will disappear after step 5. 

3. Add all your music files to the 'ReplayAudioFiles' folder, found in Resources. 

4. Make sure that the folder path set in the AudioManager Prefab uses the string "ReplayAudioFiles".

5. When read, in the Tools menu, run the GenerateMusicEnum item. Tools > GenerateMusicEnum

6. An enum will be created with all of the audio fule names added, in the ReplayAudio folder. It will be named `AudioEnum.cs`. 

7. In the AudioManager prefab you will now see the names of the music files, in the Replay Audio enum. You can use this to select the music. 

8. The Audio Start time integer allows you to set the delay. If set to 0, the audio will start as the scene starts. 
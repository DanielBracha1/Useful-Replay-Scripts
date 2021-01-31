# Audio Selection
## What is it? 

The Audio Selection prefab allows you to add all music files in a given folder to an enum, which can then be used to change the music playing in the scene. There is an optional start time field which can be used to offset the time at which the music starts.

    
## Why use it?

Audio makes a big impact on video performance. 

You may want to have the flexibility to choose different music for your videos, but want the ease-of-use that comes from a drop down based on the current music in your folder. 

## How to Use

1. Download and then drag the package into your project

2. Delete the file named `AudioEnum.cs` in the ReplayAudio folder.

 You will see an error at this stage - don't worry, this will disappear after step 6. 

3. Drag the 'AudioManager' into your scene. 

4. Add all your music files to the 'ReplayAudioFiles' folder, found in Resources. 

![alt-text](https://i.imgur.com/WK4IcoB.png)

5. Make sure that the folder path set in the AudioManager Prefab uses the string "ReplayAudioFiles".

![alt-text](https://i.imgur.com/xPGXcjq.png)

6. When ready, in the Tools menu, run the GenerateMusicEnum item. Tools > GenerateMusicEnum

![alt-text](https://i.imgur.com/fJRk3A1.png)

 Please note, that changing the order of the audio files, or removing them after generating the enum, will lead to incorrect behaviour. 

7. An enum will be created with all of the audio files names added, in the ReplayAudio folder. It will be named `AudioEnum.cs`. 

8. In the AudioManager prefab you will now see the names of the music files, in the Replay Audio enum. You can use this to select the music. 

![alt-text](https://i.imgur.com/Pgr0CvG.png)

9. The Audio Start time integer allows you to set the delay. If set to 0, the audio will start as the scene starts. 

10. In order to change music on Playground, add both "AudioManager.replayAudio" and "AudioManager.audioStartTime" to "Field Sets" on Replay.

![alt-text](https://i.imgur.com/GlXoM1I.png)

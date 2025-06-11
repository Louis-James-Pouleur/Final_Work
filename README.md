# Final_Work

# Introduction 

This repository contains the final project for my last year of the Bachelor's program at Erasmushogeschool Brussel, Campus Kaai. It includes all documentation, code, and assets used for the technical realization of the project.

**Triggers** is an audiovisual installation and research project that explores the dopamine-driven effects of smartphone notifications on the evening routines of young adults aged 18 to 21. Through generative visuals and immersive sound design, the installation visualizes the emotional and cognitive impact of digital interruptions, reflecting how attention, sleep patterns, and emotional well-being are influenced by constant connectivity.


# Needs
To fully experience this project, you’ll need an educational or higher license for [TouchDesigner](https://derivative.ca/download), along with the latest version of Ableton Live 12. Compatibility with Ableton Live 11 is still in progress.

The project also runs with the non-commercial TouchDesigner license, but this will limit the output resolution.


# How to run
1. Clone the github [repository](https://github.com/Louis-James-Pouleur/Final_Work)
2. Navigate in the folder to the project (TouchDesigner -> Final Work -> TD_FINAL -> PROJECT -> FW_COMP.XX.toe)
3. In the Touchdesigner project go to the tdAbletonPackage container and in the utility tab all the way down u can link the corresponding Ableton live project and press open.
4. Press play in Touchdesigner so that the project can be loaded in with all it's tracks (play the track till the end). After this all tracks should be connected to it's paramater and you can press the play button to Start the entire project.
5. If you're using the same instalation setup as me you can import the mapper tox, with this you can link the END TOP to the panorama input and unable "use panorama mode" and pres "trigger" button.
6. The Touchdesigner and Ableton project should loop perfectly
7. If you wish to Reset the animation press the Reset button and the animations will reset to the first frame

# How to Develop

Follow these steps to contribute to or modify the project:

## Development Setup MAIN Container
- In the MAIN Container you can access all current animations
- If you wish to add or change any animations then make a new container or copy one, in that container you can create or furder develop an animation.
- After you've made your adjustments add an Out Top to your container and link it to your final source of animation, when minimising to the MAIN container you can link that out to the Switch TOP.
- If you add an animation to the Switch Top you als have to increase the limit of the Count Chop in the MAIN container

## Development Setup CHAPTERS Container
- In the CHAPTER Container you can access all current animations
- If you wish to add or change any animations then make a new container or copy one, in that container you can create or furder develop an animation.
- If you wish to change the text, font, fontsize, font color, then you can easely go inside it's dedicated Container and change the Text Top parameters.
- If you wish to relink the brain pointcloud you can go inside the Brains Container, locate the RED Rectangle with inside the PointFileIn in which you can relocate the brain pointcloud
  - It's file (Brain_Vertices_2500) is located in the CONVERTED folder inside the ASSETS folder (TouchDesigner -> Final Work -> TD_FINAL -> ASSETS -> CONVERTED)
  - [3D Brain file](https://sketchfab.com/3d-models/brain-735ca31a3b22433281e6fa9606792faa) by: maheshshinde777 on Sketchfab (Converted it to a pointfile myself)
- If you wish to change the pointcloud to one of your choice then copy or add a pointFileIn, then select your file and link it to the pointTransform TOP

## Development Setup Ableton Live project
- If you've never worked with Ableton before I suggest you watch a [tutorial]([https://www.ableton.com/en/live/learn-live/#interface](https://youtu.be/2kg0wzKC1jI?si=LnwCr3HKhcHtHFdx  )) or go check the [Ableton Interface](https://www.ableton.com/en/live/learn-live/#interface) on the basics, these will explain the working and help you make changes in the file
- Using the Draw tool you can add or remove notes in the Drum Rack **WATCH OUT** -> changing these can affect some animations or transitions in The Touchdesigner project
- If you wish to add a sound you can open a new PAD in the Drum Rack and add yours to it, then using the Draw tool you can add those notes to your MIDI Note Editor.
  - This will add a new track in Touchdesigner in your AbletonMIDI Container, you can rename it using the rename CHOP. This can also be used to add extra interactivity in Touchdesigner animations.
 
# Folder Structure
- `TD_FINAL/`: Foler including the audio, assets and Touchdesigner project with components
  - `ASSETS/`: Place all assets you want to use in this folder, this also includes different Brain pointcloud you can you in the Touchdesigner project, **Look out* higher number = more processing power from your computer
  - `AUDIO_MIX/`: Here you can add your personal Soundtracks you've made
    - `ASSETS/`: List / Back up of all sound samples used in the Touch Designer project
    - `Audio_Mix_FW Project/`: Contains the Ableton Project
  - `components/`: List of the used Components in my project
  - `PROJECT/`: Contains the Touchdesigner Project

## References 
Ableton: Eptiar [RYOJI IKEDA INSPIRED MINIMAL GLITCH BEATS](https://youtu.be/1GW7xICyA30?si=2Jt99EzlFuxg5Q97)
Animation 1: PJ Visuals [Frequency Guided Particle Sim Touchdesigner Tutorial](https://youtu.be/A1TfrWmrOfA?si=0YdBhTJ2wMyfK96S)
Animation 2: supermarket sallad [Disintegration pt. 1](https://youtu.be/WavVlg3PZnk?si=NfR7hA4RbdxgLPAo) and [Disintegration pt. 2](https://youtu.be/KWOcPsk4d9w?si=gfD9A2FMcX4FZ-BZ)
Animation 4: PJ Visuals [Audio Reactive Spectrum Visual in Touchdesigner](https://youtu.be/jaXFcHgguq0?si=I5cqx5cgZyN_yvsa) 
Brains animation: Alexxxxxi [3D Laser scanning dissipation](https://youtu.be/Nqg8T4FtbRE?si=SCflxV0S215VZqPp)


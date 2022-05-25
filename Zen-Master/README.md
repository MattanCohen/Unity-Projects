# ZenMaster


Gameplay Controls:
* swipe (or click) the yellow rectangles (supposed to be fruits)
* avoid missing fruits (letting fruits get out of screen boundaries)
* avoid swiping (clicking) bombs (the black blobs)
* press the "up arrow" above the red bar on the right to append the difficulty level (holding isn't available) - making the summoning rates more frequent and increase the change of the summon being a bomb
* press the "down arrow" below the red bar on the right to decrease the difficulty level (holding isn't available)


this game was made as part of the Brain Gurion 2022 hackaton.

the hackaton focused on integrating behaviour physical changes with video games.

the game Zen Master is my take on the classic "Fruit-Ninja". the game's original gameplay:
- the player is wearing the EEG device called Muse
- muse records the player's electro-magnetic waves from the front brain parts (using its API Blue-Muse)
- using a few mathemetical functions (such as FFT), calculate the numeric changes in the player's electro-magnetic wave amplitudes into a singular number "concentration_level"
- transform the number "concentration_level" from Python to Unity
- using a few more mathemetical functions, make the variable "concentration_level" affect the gameplay:
    - as you lose focus the game gets harder (throwing more bombs at you at more frequent times)
    - if you succeed to regain that focus back, the game gets easier

the last point makes the game have a dynamic difficulty functioality - rewarding players with easier gameplay as they maintain their focus (and punish them for losing focus). 


the current version of the game is built for android: it contains smoother input system and buttons on the "concentration_level" bar allowing the common android player player change the difficulty during gameplay without acquiring the special 200$ EEG devide Muse. 



the Brain Gurion Hackaton site: https://he.brainstormil.com/braingurion3

the Brain Gurion Event site: https://he.brainstormil.com/event-info/brain-gurion-3-0




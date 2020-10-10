Reconetc 

Is a generative dual sample slicer with four micro algorithms organised in zones, with trigger probability and repeats. 
It comes with 2x stereo reverbs and four filters damping the reverbs. Left input can be used to send external signals thru the reverb as well. 
The instrument has a modular design and was developed based on the patches I used to teach generative composition. 
These are ported from Max to pd and modified. I encourage modification of the algorithms, slices and samples. 
I am hoping more people get into patching Nebulae this way. The mini sample pack is attached as well.  
Nebulae should load the pack once you select the patch from the pen drive. 
**Samples used in the patch are Piano1.wav, Piano2.wav, Atmos.wav, Kick.wav, Stabs.wav, SnareCrickets.wav**
 
These are mono and are used as 2 separate channels. If you like to change them you need to modify the patch or modify names of your samples to the ones above. In pd these are in file selector1 and 2, this is so patch gets the path and files right. 
This instrument reads specific 6 files.
Sometimes it might not load the file fine then keep pressing **file** it eventually should work fine.  

List of functions as on the panel: 

* Speed - speed/pitch of slicer 1
* Size - volume of slicer 1 
* Pitch - speed/pitch of slicer 2
* overlap - volume of slicer 2
* blend - probability of clocks/steps/slices 
* window - repeater of certain steps 
* start - zone selection / algorithm choice 1-4 5th one is free-running loops its on the right side.
* density - tempo / density of material / metro timing

Hidden functions :

* blend alt - reverb on sample 1
* window alt - reverb on sample 2
* size alt - volume of incoming input this is patched thru reverb 
* reset - resets steps 
* file - toggles between samples for slicer 1
* file alt - toggles between samples for slicer 2
* record alt - press to activate external clock then freez is input for clock 

There is MIDI controller activated too by sending program change messages.
You can change that to notes or other midi messages in pd keyboard. pgmin is the receiver of program change messages.



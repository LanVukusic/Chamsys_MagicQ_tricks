# Chamsys_MagicQ_tricks
A list of quick tricks that get you to speed when programming with Chamsys MagicQ.
I wished to create a bigger index of shortcuts. [There is an official link](https://secure.chamsys.co.uk/help/documentation/magicq/ch47.html)
for the magicQ shortcuts provided by chamsys.  
This list expands on it.

Special thanks to Manuel Rodrigues, for all the help in kickstarting this project.





### Shift + Record / Include / Copy / Remove
Opens a record window with aditional settings, where you can select which atributes are selected / recorded... 
(lets say, just dimmer and not the positions).
> Aditionally: setup->Windows you can set Rec Options as "Always show..."

***

### Merge / Remove record options
When you "Shift + Remove", upon you select destination, you geta menu with "Merge" and "Remove" options in top left.  
That gives you the option to either:
* remove the atributes in programmer from selected playback.
* merge the programer with the playback (previous stuff saved + the new ones).

***

### Set the PAUSE and GO button to trigger playbacks
> Setup > Playback > Play/Pause use exec grid 1.  

You can set up exec grid 1 as a 10x2 grid, and record your playbacks on it. Than you will be able to trigger them from the playbacks

***

### Pos/ Beam/ Color... + Inc
for example hold down the POS button and press include then only position data 
will be brought into the programmer when you select a cue etc;

***

### Size/speed masters
Just by selecting the group then recording to a fader and then simply choosing what attributes it controls.

*** 

### Updating palette offsets
Updating the palette offset, saving serious amounts of time when updating positions!

***

### Automatic icons
When you patch a generic dimmer and name it "Haze", magicQ automatically sets the icon to a hazer.

***

### Shift + Single = Pair (selection in Highlight mode)
That takes first and last in a group and work inwards  
On Mq500 there is a dedicated button for it

***

### Crossfader remaping
You can remap all the crossfader buttons to your own taste in:
> Setup > Playback
You can cset up the GO button to tap to time (Global or selected) for example.  

*** 

### <S\> + Record = record merge  
Record merge in the active cue. Or for people without a console or wing, RECORD UPDATE does the same in the selected playback.

***

### Thru + Record = Snapshot
It records the whole DMX output of the console.

***

### Ctrl + Record  
Records the DMX input.  
For example: It enables you to copy positions from one desk to another.

***

### Shift + Highlight
allows you to set custom selections like with Parts and Segments.

***

### Coping groups to a playback makes an intensity chase
Copying a Group to a Playback makes a Cue with Intensity at 100%  
Selecting multiple groups using the cursor (SHIFT + cursor keys) and then copying to a Playback creates a multi step Cue Stack of intensities – one Cue step for each group. This is an easy way to create, for example an intensity chase of your different moving light groups or your different par can colour groups.

***

### Copying color paletes to a playback
Select group, select all 10 color pallets, copy to playback.  This makes a CueStack with 10 cues with the 10 colors. Works with all type of palettes.

***

### Expand palette
When you want to add a parameter to a palette and make sure the new parameter is used in all the cues the palette lives in:  go to view palette / expand palette.

***

### Intelligent fan times palletes
Type this syntax in the command line and hit a pallete to fade with intelligent fan.  
If you then record that pallete to a playback it will fade acordingly.  
Example: Select fixtures, At full, 3*+ (select a color), record to a playback.  
Applying Palettes with times and fanned times can be applied to all Palette types including Beam and Colour.  


* \<time> *  
Fan times across selected heads

* \<time> * /  
Reverse fan

* \<time> * +    
Into centre fan

* \<time> * -  
Centre out fan

* \<time> *.  
Random

* \*  
Use last fan time

***

### Identical CueStack generation / cloning of CueStacks
Select group you want to copy the programming TO. press shift + copy, at the top press COPY TO SEL, press the cue stack you want to copy FROM, then press an empty cue stack s button.

***

### Customising Locate, Default, Highlight and Lowlight values  
Manual page 7.26  
Simply record a Cue into the Cue Store and then press the SET LOC CUE, SET DEF CUE, SET HIGHL CUE, SET LOWL CUE soft buttons. The Cue is indicated as Default, Locate, Highlight or Lowlight by a D, L,H or Lo after the Q number.

***

### Master Faders as Cue Stacks  
* from version 1.762 onwards  
* [Video tutorial here](https://www.youtube.com/watch?v=flRqRWCrd7A)
This allows us to make the masters behave as a normal playback, which increases the maximum number of available faders.   
Setup > Playback > Grand master / Sub master / Crossfade master function  
Here you hit Set and click the desired setting. Here you choose Cue stack 1/ 2/ 3 accordingly.    
Your masters now behave as cue stacks!!     
however we have no S button above them, so the only option to record a cuse stack to the fader, is to bring up the Stack Store button, and record your cue stacks  to the fields in the stack store.

***

### Copying position pallets from one desk (can be any brand!)
Connect the output of the first console to your input.  
Go to dmx IO and set your artnet output equal to your input. Disable your artnet output. Not the whole universe but only the artnet output.  
Ask the house operator to start a circle movement on a series of movers. Go to view output / view dmx select input (top right).   Notabene: you can only see the incoming dmx here. Go to the universe of the movers who are doing a circle. See changing numbers on the pan tilt channels. 
If there are. Ask the house operator to stop the move and show you his or her positions. Whenever you like one and want to copy one: select same group.  
Press ctrl rec and select an empty position palette location. This works with all parameters. Color, Beam looks, etc.

***

### Media server input to chamsys pixle mapper (Resolume, grandVj, ...)  
Patch the led pixels in your desk and in the patch win set the merge field of these pixels to “merge”. This gives you a HTP merge.   Research the the options there. You might want to use a LTP merge. There is also a multiply in option which gives you the possibility to dim your input from Resolume.   
In Resolume set your led to send at exact the same adres as in your desk but one subnet higher. In your desk set the IN field of the dmx-IO settings to this same uni and subnet combo.  
Last addition. Incomming DMX can only be viewed in the following window: Output, view dmx and then select INPUT. Top right button.




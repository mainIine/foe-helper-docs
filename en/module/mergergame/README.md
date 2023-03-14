---
description: How does the Merger Game info work?
---

# Merger Game Info

This module shows you information about the merger game board when you open up the minigame of the anniversary event.

## Info Box

![Info Box](./.images/mergergameinfo.png)

the following info s displayed:

* how much progress may be made on the current board from freeing the key pieces and how much progress was already made
* how much energy was already used (incl. reset costs)
    * when hovering over the energy, a tooltip will be shown, displaying how much progress should be made on the current board to reach the target, taking into account the energy currently spent
* how many keys were combined (on the board and converted)
* an efficiency (progress divided by energy)
    * progress includes freeing the key pieces as well as the progress that can be achieved when using up the keys later on by buying chests
    * via the settings a target value may be set - the color of the efficiency changes in relation to the target:
        * efficiency is red, when 5% or more below the target
		* efficiency is green, when 15% or more above the target
		* efficiency is yellow in between, when just enough progress is made to reach the target
	* when hovering over the efficiency, a tooltip is shown, displaying the progress that can be made with this efficiency, when this efficiency value is the same for all your games
* a table tallying the keys and key pieces on the board per color and level
    * the number that is smaller of "top" and "bottom" key piece is made bold
    * when the max number of keys is reached, they are made bold
    * when there are 2 or more full keys at level 3 (second column) they are shown red to remind you to combine them before converting them (1 level 4 gives 3 keys, while 2 level 3 give only 2 keys)

Furthermore, a blocker is shown on top of the reset button as long as there are complete keys on the board to prevent accidental resets.	

## Settings

This module may be (de)activated in the general settings (Boxes - Event Assistants).

![Settings](./.images/mergergamesettings.png)

* progress per key: this is the approximate value of a key (from buying chests - default: 1,3)
* target progress: this is how far you want to get in this event (default: 3750 for the golden kit)
* available energy: this much event currency is available in total (default: 11000 - 10500 from quests and ~500 from incidents)
    * bought currency should be added here
* if the reset blocker shall (not) vanish upon minimizing the module, this can be set here
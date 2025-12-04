# AbortCommand
This simple program adds a context-menu option for beacons in CobaltStrike. The option "Abort Command" will clear the selected beacon's command queue.
This is equivalent to using the ```clear``` command from the beacon terminal. 

# Usage
This adds flexibility for operators to cancel potentially erroneous or detrimental commands using only a mouse. 
- Avoid fumbling the ```clear``` command in high-stress scenarios with limited time between beacon sleep cycles
- Target beacon does not need to be opened via "interact"
- Multiple beacons can be selected at once. The "Abort Command" operation will apply to all of them simultaneously

# Example
![](https://github.com/PN-Tester/AbortCommand/blob/main/demo_abort.PNG)

# Installation
Git clone the repo or download just the AbortCommand.cna file. From CobaltStrike, navigate to the "Cobalt Strike" -> "Script Manager". Then use the "Load" button and select the aggressor script. The context menu for beacon's will now include the "Abort Command" capability.

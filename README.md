# AbortCommand
This simple program adds a context-menu option for beacon's in CobaltStrike. The option "Abort Command" will clear the selected beacon's command queue.
This is equivalent to using the ```clear``` command from the beacon terminal. 

# Example

# Usage
This adds flexibility for operators to cancel potentially erroneous or detrimental commands using only a mouse. This can avoid fumbling the ```clear``` command in high-stress scenarios with limited time between beacon sleep cycles.
Additionally, multiple beacons can be selected at once, and the "Abort Command" operation will apply to all of them silmultaneously.

# Installation
Git clone the report or download just the AbortCommand.cna file. From CobaltStrike, navigate to the "Cobalt Strike" -> "Script Manager". Then use the "Load" button and select the aggressor script. The context menu for beacon's will now include the "Abort Command" capability.

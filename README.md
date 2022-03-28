# CS455 Module 2 PR3: Behavior Trees++   
Author: Georgiy Antonovich Bondar  

Go to https://keshakot.github.io/CS455_M2.PR3/ to play the game)

# Behaviors
Behavior Tree (logic and movement): Assets/Scripts/BehaviorTreeMovement.cs

# Description
1. Use the buttons in the game to select the state of the door (locked, closed, or open) and of the bridge (broken/fixed).   
2. The player will then respectively barge, open, or walk through the doorway unhindered to it's destination on the other side, then fix the bridge(if needed) and cross it to the final destination.   

# Changes/fixes  
1. Added the handling of the new bridge to the behavior tree (see CS455_M2PR2_flowgraph.drawio.pdf)  
2. Added smoother transitions for the player - instead of performing actions instantly as the behavior tree is traversed, actions are added to a queue, which is then smoothly executed through Update() ).  




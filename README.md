# Example-Code-Lift
A series of code snippets focusing on my most recent work with Lift VR. Lift is being developed in Unity 3D. Code shown is C#.

Audio Length:
Function called by playmaker FSM to play and determine the length of the currently spoken dialogue. The audio length is sent to the active FSM as a Playmaker Global.

Gaze Timer:
Function used to determines the time a player chooses to look in the direction of a speaking patron. Choosing to ignore/ pay attention to patrons results in different interactions.

Robber1FSM:
Example of Playmaker Finite State Machine used to outline patron interactions. Dictates how conversations may branch depending on particular interactions. 

SpawnPatron:
Function used to instantiate a new patron from resources. The patron is then parented to their current floor, where they will wait for player interaction. 

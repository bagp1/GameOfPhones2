Description
this is a UE4 game with a C++ character extension
Character's beginPlay spawns a thread that non-blockingly polls for UDP input
Blueprint polls the thread for input
Blueprint adds the difference between current and last inputs to the transform of the ghost sword
Blueprint uses physics to make the real, game interactable sword approach the ghost sword

Warning
icon must be in Build/Windows/ before the uproject is used to generate files. Then the editor can be run.

Branch master/A has normal settings
Branch B has high force and recenter
Branch C has low force and normal recenter	

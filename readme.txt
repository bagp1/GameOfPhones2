Description:
this is a UE4 game with a C++ character extension
Character's beginPlay spawns a thread that non-blockingly polls for UDP input
Blueprint polls the thread for input
Blueprint adds the difference between current and last inputs to the transform of the ghost sword
Blueprint uses physics to make the real, game interactable sword approach the ghost sword

Warning:
icon must be in Build/Windows/ before the uproject is used to generate files. Then the editor can be run.

Installation:
you will need
	an android phone with gyroscope, accelerometer and magnetometer sensors
	a desktop pc with a mid range graphics card
	a wireless connection from phone to pc
	much of an afternoon

instructions
get Anders Malmgren's Android FreePIE IMU by finding the apk or building the project at https://github.com/AndersMalmgren/FreePIE/tree/master/Lib/Android
install FreePIE IMU on your phone.
set the IMU to route packets through your wi-fi to your computer using the default port 5555, you can confirm it works with the FreePIE desktop's provided scripts
clone the game of phones 2 repo
move the windows icon in the root folder into Build/Windows/
instruct the PhoneGame.uproject to build the project
Everything should be working and you should enjoy!

Note on git branches:
Branch master/A has normal settings
Branch B has high force and recenter
Branch C has low force and normal recenter	
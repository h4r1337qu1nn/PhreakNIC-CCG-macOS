# PhreakNIC-CCG port for macOS

This is a macOS release file for the PhreakNIC Collectible Card Game, originally developed by Nirtom84, with contributions from mogorman. The game was also programmed with assistance from Claude AI and Codex. The original FOTTR trading card game was designed by 5ud0, bitwize and crook3dfingers.

## macOS port

This release was exported to macOS using Godot, which was used to develop PhreakNIC-CCG. It does have the ad-hoc signature provided by Godot.

In order to run the app, you must open your System Settings, go to Privacy & Security, scroll to Security, and click Open right next to the PhreakNIC-CCG app. You will need to authenticate using your system password or Touch ID in order to authorise the app to run on your system. Make sure that your settings allow for you to run non-App Store applications.

## Testing

This version was exported and tested using an M1 MacBook Air with 16GB of RAM and macOS 27 (Golden Gate) installed on the system and it works mostly well on it, so I would definitely expect Apple Silicon compatiblity. It has not been tested on any Intel-based Macintosh systems but I may test it on my Intel-based 2018 MacBook Pro, if warranted to see if it is compatible.

The most notable issue I faced with this port is the fact that there is a one second delay once it is the player's turn and there are one copy of every card in the deck.

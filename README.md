# ExploreThreejs
Assignment

I changed Shapes.js by removing all of the shapes and instead importing a .obj model of a building to explore. This was accomplished with THREE-OBJLoader, and a new control scheme is used called THREE-FlyControls. Custom lighting was also added.

To run the program, simply open up the folder in a local web server. The screen will be black as the model loads in, but you can check the loading progress in console with f12.

Movement commands:

WASD: Standard forward/left/back/right movement
QE: Roll left/right
RF: Move up/down
Arrow keys: Look up/down/left/right.

If you don't want to feel sick to your stomach, I recommend avoiding up/down arrows and Q/E. Hopefully 'PointerLockControls' will be implemented soon, which is the more familiar first-person gaming controls.

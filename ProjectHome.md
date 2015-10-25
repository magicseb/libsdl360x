Simple DirectMedia Layer (SDL) is a cross-platform multimedia library designed to provide low level access to audio, keyboard, mouse, joystick, 3D hardware via OpenGL, and 2D video framebuffer. It is used by MPEG playback software, emulators, and many popular games, including the award winning Linux port of "Civilization: Call To Power."

This is an Xbox 360 implementation of SDL Libraries

2/9/2011 - V0.02 has been commited to SVN

Whats New?


- Fixed keyboard code so Shift/Alt/Control keys work correctly (fixes keyboard issues in XeDosBox)

- Fixed Joystick bug where controllers 2-4 would poll against player 1 (fixes Super Mario Wars controller issues)

- Added mouse emulation via Left Analog stick. Button A for left mouse, Button B for right mouse

- Adjusted vertex buffer to fit inside safe-area region
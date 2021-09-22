# webpad
A simple HTML pad visualizer using the Gamepad API made for OBS. 
- [Standard](https://thaumictom.github.io/webpad/index.html) v0.4
- [Wheel](https://thaumictom.github.io/webpad/wheel.html) v0.3
- [Debug](https://thaumictom.github.io/webpad/debug.html) v0.1

Please note that the visualizers in v0.3 and before are working on predefined keys.
If you want a working version on your device, please contact me on Discord: [ThaumicTom#7179](https://discord.gg/Trackmania) (You will need to share at least one discord server with me to find me.)

## v0.4 is now out for Standard and supporting key overwriting/button remapping
*Note: You can not customize the analog steering yet*

Go to [a gamepad tester website](https://greggman.github.io/html5-gamepad-test/) or use my own [Debug page](https://thaumictom.github.io/webpad/debug.html) and connect your device. Hold the button you want to use instead and look what number is changing from 0 to 1. For example if you press RB on a Xbox controller, B5 should change to 1. The 5 is correspondend to RB which you will have to use in the URL. We will call the number the ID of the button.

Change X to overwrite the acceleration key and Y to change the brake key with their corresponding IDs. For example, if you change X to 5, the visualizer will only display acceleration when you press RB, because RB = 5 as you can test on the link above. 
https://thaumictom.github.io/webpad/index.html?ac=X&br=Y

# binaryKeypad
it does those dang 0s and 1s


## Compiling+uploading

There are two ways to do this:

### PlatformIO

The current file structure is made for use with Platformio. It can either be used directly from the terminal or within a text editor like Atom or Sublime.

For the CLI, install Platformio Core, cd into the binaryKeypad directory, and use platformio run --target upload (it will also compile the code.) http://docs.platformio.org/en/latest/installation.html

For the IDE, install Deviot on Sublime or Platformio IDE on Atom through their respective package managers.

<sub><sup>Make sure to install the udev rules on Linux or the drivers on Windows if you're not using Windows 10.</sup></sub>

### Arduino IDE

To use this with the Arduino IDE, there are a few extra things you need to do after installing the IDE:

- Change the name of the "src" folder to "main" (the folder and filename need to match, so you could also change both of them to be named something more sensible.)

- Add the Adafruit board URL https://learn.adafruit.com/add-boards-arduino-v164/setup

- Install the Trinket M0 through tools>boards>board manager

- Install all required libraries through sketch>libraries>library manager

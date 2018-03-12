============
Installation
============

Install the package with pip::

    $ pip install read-the-docs-template


#First Steps
Welcome aboard!
when you launch **gRally.exe** the `Drive` page appears, but before you drive, you need to configure some things:

 .. warning All the settings are saved automatically, so you only need to change the setting!

##Video/Display
The first and simple configuration is to change the video resolution: click the config button on the top bar

[![video settings](https://github.com/gRally/dev/wiki/img/Config-Display.png)](https://github.com/gRally/dev/wiki/img/Config-Display.png)

Into this page you need to set the right resolution and the fullscreen.

The other pages/settings are explained later.

##Pacenotes

[![pacenotes](img/Config-Pacenotes.png)](img/Config-Pacenotes.png)

Into this page you can customize the Codriver AI, but the first thing that you should do is select the codriver, mostly for the non italian people :grin:

##Controls
[![controls](https://github.com/gRally/dev/wiki/img/Config-Controls.png)](https://github.com/gRally/dev/wiki/img/Config-Controls.png)

This is one of the biggest changes of this menu:

###Analogic controls
To set your analog control you just need to click the radio button on the left of the interested control *(ie: `steering wheel`)* and move the axis, so you can see a graph that show how will work the control in **gRally**

You can set the maximum and minimum value for each control clicking the button on the left/right of the slide *(in the shot the clutch has the maximum about at 75%, the green line)*

You can change the linearity of the control moving the slider below the graph

You can invert/no invert the control with the toggle button.

####Goofy controls
The analogic and digital controls are now unified: this means that for the analog controls like steering, accelerate, handbrake, etc. it's possible use an analogic controller or a digital controller.

The big difference is for the steering, that when you use an analogic wheel you use one input, and if you use a digital controller you need to configure a left and right buttons.

###Digital controls
To set the digital controls you do the same thing like the analogic controls.. you can click a joystick button or a keyboard key, once is set, clicking the element, the icon become red.

Here is the table of the default settings:

control    | key 
-----------|------
Accelerate | <kbd>S</kbd>
Brake      | <kbd>X</kbd>
Steer Left | <kbd>;</kbd>
Steer Right| <kbd>:</kbd>
Shift Up   | <kbd>Q</kbd>
Shift Down | <kbd>SPACE</kbd>
Handbrake  | <kbd>Z</kbd>
Clutch     | <kbd>C</kbd>
Engine     | <kbd>E</kbd>
Lights     | <kbd>L</kbd>
Look Left  | <kbd>N</kbd>
Look Right | <kbd>M</kbd>

##Drive
Let's do some interesting things!!
[![drive](img/drive.png)](img/drive.png)

###Car section
 1. Car choice *(at the moment only this car is available)*;
 2. Car paint: here you can choose a livery or customize the colors using some car template;
 3. Car version: by default the latest car is choosen.. if you want, you can select a previous car version to drive changing the slide position.
 4. Setup manager: you can change and create your setups;
 5. Setup chooser: you can fast choose your saved setups from a list;

    ###Session section
 6. Date and time to drive: you can select the date/time of the drive session;
 7. Groove: the groove of the track *(at the moment only graphical)*;
 8. Wet: the wet/damp of the track *(at the moment only graphical)*;

    ###Stage section
 9. Stage choice: appears a flyout where you can scroll to choose the stage to drive;
 10. Stage version: by default the latest stage is choosen.. if you want, you can select a previous stage version to drive changing the slide position.

    ###Drive section
 11. Drive: click and enjoy!!
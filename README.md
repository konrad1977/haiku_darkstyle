# Haiku-OS DarkMode

## Sources:
The binaries here, are only available for 64bits, but you can download the code and compile it using "make" command in the root of the path (decorator and controlLook). Mabe for 32bits need to make changes in the source code (no tested in 32bits!).

### Install of controlLook
Copy the binary "FlatControlLook" (https://github.com/unarix/haiku_darkstyle/tree/master/FlatControlLook/objects.x86_64-cc8-release) in the path: "/boot/home/config/non-packaged/add-ons/control_look" (if not exist the folder, create it).

### Install of Decorator
Copy the binary "FlatDecorator" (https://github.com/unarix/haiku_darkstyle/tree/master/FlatDecorator/objects.x86_64-cc8-release) in the path: "/boot/home/config/non-packaged/add-ons/decorators" (if not exist the folder, create it).

### Install Dark-Theme:
To use the theme you need to install the package "Theme Manager" from haiku-depot. After install it, copy the folder "DarkFlat" from (https://github.com/unarix/haiku_darkstyle/tree/master/DarkFlat) in the directory /boot/home/config/settings/UIThemes. Open Theme manager and select "DarkFlat" from the list.

### Select Decorator and ControlLook from Appearance
In the Appearance preferences dialog, select "Flat" from the combos "Decorator" and "ControlLook"

### Restart
You need to restart the computer or quit "Deskbar" and "Tracker" services from "ProcessControler" (they will restart auto).

### Guide
How to make ControlLooks & Decorators in Haiku: 
http://www.unarix.com.ar/lab/guide/haiku/decorator/controllok/darktheme/2020/06/20/Haiku-Decorators.html

![alt text](https://raw.githubusercontent.com/unarix/haiku_darkstyle/master/screenshot2.png?raw=true)

![alt text](https://raw.githubusercontent.com/unarix/haiku_darkstyle/master/screenshot1.png?raw=true)

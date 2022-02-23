# linux-norwegian-keyboard
Modifications to make Norwegian Mac Keyboard work like it does under macos

## Tested with
* Apple Keyboard 
* Logitech MX Keys Apple version

## Steps

* Open the keyboard settings (System -> Preferences -> Keyboard) and click the “Layouts” tab. Then click the “Other options…” button.
* Press “Alt/Win key behavior” and choose “Left Alt is swapped with left Win-key”.
* Press “Third level choosers” and select “Press any of Alt keys to choose 3rd level” (or “Press left Alt keys to choose 3rd level”).

##

* sudo mv /usr/share/X11/xkb/symbols/no /usr/share/X11/xkb/symbols/no.bak
* sudo cp no /usr/share/X11/xkb/symbols/no
* sudo reboot

##

Thanks to 
* https://github.com/gulrotkake/Ubuntu-MacBook-Norwegian-keyboard
* https://github.com/jacoweb/ubuntu-mac-keyboard-no

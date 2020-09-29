# SUMMARY

Shift-shift input source switcher for Gnome, that does not depend on keypress order.
Workaround for bug: https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=909332

Shamelessly ripped off from https://github.com/Azq2/gnome-alt-shift-kbd-layout-switcher

# INSTALL
1. Build and install:
```
git clone https://github.com/smoogly/gnome-shift-shift-kbd-layout-switcher
cd gnome-shift-shift-kbd-layout-switcher
mkdir build
cd build
cmake ../
make
sudo checkinstall
```
2. Delete any shortcuts for layout switching.
3. Relogin current gnome session. 
4. Try Shift+Shift and relax. 

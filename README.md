<img src="https://github.com/xeoron/macfoobar2000/blob/master/images/foobar2000mac.png"/>

Foobar2000mac:
===========
A front-end launcher program for Foobar2000 on Mac OS X that is running under WINE. If you have wine installed, this script merely creates a launcher app for running foobar2000, therefore you can not have a foobar2000 launcher pinned to your Dock or accessable in Launchpad 

Setting this up is not for the faint of heart. Installing Mac Ports is a pain, but doing so gives you access to all the *nix terminal programs Apple failed to include in OS X.

Setup:
======
0) X11 must be installed, if it is not, go grab it from apple's website here: 

    http://apple-x11.en.softonic.com

1) MacPorts must be installed. Download it here:

    macports.org  

2) Once MacPorts is installed, then in a terminal use this command to install wine: 

    sudo port install wine

   Depending on the speed of your computer, it might take a while to build and install wine.

3) Grab a copy of foobar2000. Download it here:
    
    foobar2000.org

4) Run wine to launch the Foobar2000 installer. In the terminal: 

    cd Downloads
    wine ./foobarinstaller.exe

5) finally, load the code into AppleScript Editor, compile, and save it as a runable binary in your Applications folder.


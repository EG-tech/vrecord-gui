# vrecord-gui

An AppleScript applet to launch [vrecord](https://github.com/amiaopensource/vrecord) in GUI mode.

Basically just opens Terminal and executes `$ vrecord -g`, but unlike an executable shell script, this applet can be added to the MacOS Applications folder. Vrecord GUI can thus be found in LaunchPad or added to the Dock and launched alongside user's other GUI applications.

## Installation

### via command line and Homebrew

1. vrecord must already be installed (`brew tap amiaopensource/amiaos` and `brew install vrecord`)
2. Run `brew tap EG-tech/digipres`
3. Run `brew cask install vrecord-gui`
4. "vrecord" applet should now be found in your system Applications folder! Double-click or select from Launchpad to launch.

### via GitHub

1. vrecord must already be installed (see above)
2. Click on "release" tab at top of this repository.
3. Click on source code (either .zip or .tar.gz to download).
4. Unzip the download. You'll need an archiver application like [The Unarchiver](https://theunarchiver.com/) to unpack the .tar.gz
5. The "vrecord" applet will be contained in the unzipped folder. Move it to your Applications folder/Dock as desired.

Either way you install, creating a [custom icon](https://support.apple.com/kb/PH25383?locale=en_US) for your fancy new vrecord launcher is highly recommended :wink:

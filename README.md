# NOTE
This branch is now in active development and should be considered unstable! Before compiling and running, make sure that your libraries are correct!

# xkoranate-CE
This README is a work in progress and should not be considered final.
## Overview

xkoranate-CE (xkoranate, **C**ommunity **E**dition) is a fork of ThirdGeek/Commerce Heights' **xkoranate** program, used for generating scores for sporting events held in NS Sports, the sports roleplay forum for the nation simulation game, NationStates.

**From Commerce Heights' (original creator) Web page on xkoranate:**

"xkoranate is a program that can be used to simulate results of a wide variety of individual and team sports, including Olympic sports. It is capable of scorinating events in one hundred disciplines of over sixty sports."

## Compiling/Installation
### Linux
NOTE: These instructions are copied from my posts on the NationStates forums.

**You will need:**
* A C++ compiler, such as `gcc` (which includes `g++`).
* The latest version of Qt 4. As of this writing, the scorinator does not work with later (or current) versions of Qt. Porting is in the works, but since I'm the only dev on this project, it will take time.
* Your target xkoranate build from the Releases section.

**Getting to it**
1. Open your favourite terminal and change directories into the source tree (known as $DIR in this procedure:
```cd $DIR/xkoranate/src```
2. Run `qmake` to generate the Makefile necessary to compile the xkoranate binary with:
```qmake-qt4```
3. Now that you have generated the Makefile, simply call:
```make```
4. Leave the `src` directory from which you compiled:
```cd ..```
5. Run xkoranate by making it executable and running it:
```chmod +x xkoranate```
```./xkoranate```

Once xkoranate is running, you have successfully compiled and executed the latest version.

### Windows
Coming soon!

### macOS
Coming soon!

## Sport files

Each available event has parameters which are stored in an editable xml file. These files are placed in the “sports” directory, which can be found in xkoranate.app/Contents/Resources/sports/ in the Mac os version. In version 0.3.1 and later (including xkoranate-CE), the application should automatically find this directory.

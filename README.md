# xkoranate-CE
This README is a work in progress and should not be considered final.
## Overview

xkoranate-CE (xkoranate, **C**ommunity **E**dition) is a fork of ThirdGeek/Commerce Heights' **xkoranate** program, used for generating scores for sporting events held in NS Sports, the sports roleplay forum for the nation simulation game, NationStates.

**From Commerce Heights' (original creator) Web page on xkoranate:**

"xkoranate is a program that can be used to simulate results of a wide variety of individual and team sports, including Olympic sports. It is capable of scorinating events in one hundred disciplines of over sixty sports."

## Compiling/Installation
**Linux**

**You will need:**
* A C++ compiler, such as `gcc`.
* The `make` utility.
* Qt 5 development tools from your distribution (e.g., `qt5-default` in Ubuntu, or `qt5` in Arch Linux).
*Note: Some distributions have a metapackage or group of packages, such as Ubuntu's `build-essential` or Arch Linux's `base-devel`, that include basic development tools. If you have such a package installed, `gcc` and `make` should already be present.*

## Sport files

Each available event has parameters which are stored in an editable xml file. These files are placed in the “sports” directory, which can be found in xkoranate.app/Contents/Resources/sports/ in the Mac os version. In version 0.3.1 and later (including xkoranate-CE), the application should automatically find this directory.

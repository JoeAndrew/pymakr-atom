## 1.2.1 - versioning update
* atom v1.23.0 compatibility added
* Bugfix for paste in terminal on mac (cmd-v instead of ctrl-v)

## 1.2.0 - Download feature, multi project support
* Splits 'sync' into 'download' and 'upload'
* Adds detection for selected project in the tree-view
* Better stability for upload

## 1.1.5 - Hotfix
* Compatibility until 1.22.0 tested
* Small bugfixes sync feature

## 1.1.4 - Bugfixes
* Serialport installation fix for linux
* Bugfix in sync code, caused in 1.1.3
* Sync support for old wipy 1.0

## 1.1.3 - Bugfixes
* Support for atom 1.20.1
* Small bugfixes in sync
* Fixed 'name undefined' error during run
* Disappearing connect/sync/run buttons fixed

## 1.1.1 - Win64 bugfix
* Serialport library improved for 64 bit
* Small bugfix in communication protocol

## 1.1.0 - Shared codebase with VSCode plugin
* Big refactor to get a shared base code with the VSCode plugin
* Added 'open_on_start' config
* Fixes issues with serialport lib for newer versions of atom
* Bugfix in the run feature on linux.
* More relaxed keep-alive protocol on telnet (ping has to fail twice before connection break)

## 1.0.3 - Serialport fix for atom 1.17
* Fixes issues with serialport lib on windows32 and problems in newer atom versions 1.17.2 and 1.18

## 1.0.2 - Bugfixes
* Added timeout and reconnect logic on serial connection (useful for pysense/pytrack sleep)
* Pysense/pytrack serialport detection
* Bugfix related to project settings not refreshing (issue #23)
* Ignoring hidden and empty subfolders during synchronize

## 1.0.1 - Bugfixes
* Multiple typo's and small bugfixes
* Added an option to get the wifi AP SSID from the board
* UI updates including pycom logo
* Increased maximum lines in terminal to 5000

## 1.0.0 - Stable release
* Added project specific settings
* Added serial port detection (in sub-navigation under the 'more' button)
* Multiple bug fixes for synchronization over serial
* Terminal height now resizable by dragging the top edge
* Fixed 'failed to connect' bug when reconnecting on telnet

## 0.9.4 - Stability improvements
* Include precompiled serialport libs for mac and linux
* Improved error handling and stability on sync
* Running files is now possible for unsaved files
* Bugfixes for pasting multiple lines and cmd-c/cmd-v commands.
* Fixed connection issue when using telnet to a device access point

## 0.9.3 - First round of bugfixes
* Improved sync stability and speed over serial
* Solved disappearing line in terminal (github issue 3)
* Other small bugfixes
* Logger class for easier debugging

## 0.9.2 - First Release
* Connection over serial and telnet using REPL
* Sync feature
* Run feature
* Close / open terminal

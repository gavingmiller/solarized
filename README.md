Color Settings for OS X Terminal.App
====================================

These instructions were forked from:
[https://github.com/altercation/solarized](https://github.com/altercation/solarized)
With instructions modified from:
[http://www.byteengine.net/custom-colors-in-snow-leopard-terminal-64-bit](http://www.byteengine.net/custom-colors-in-snow-leopard-terminal-64-bit)

Installation
------------

Terminal.app doesn't have full color modification support without some effort. The following has been tested successfully on Snow Leopard. It works on my current machine, but may not work on yours.

1. Install _SIMBL-0.9.9.zip_  
Updates can be found at: [http://www.culater.net/software/SIMBL/SIMBL.php](https://github.com/altercation/solarized)

2. Install _TerminalColours-SL-64bit.zip_ under __~/Library/Application Support/SIMBL/Plugins__  
If the SIMBL/Plugins directory doesn't exist, create it.  
Git repository: [https://github.com/timmfin/terminalcolours](https://github.com/altercation/solarized)  
Download: [http://github.com/timmfin/terminalcolours/raw/master/TerminalColours-SL-64bit.zip](https://github.com/altercation/solarized)

3. Install _IR\_Black.terminal_  
Download: [http://www.infinitered.com/settings/IR_Black.terminal.zip](http://www.infinitered.com/settings/IR_Black.terminal.zip)

4. Modify _.profile_ to include the following line:  
   `export CLICOLOR=1`

5. Restart Terminal, open preferences, and ensure that the "More..." button appears in the Text windows of the Settings tab  
![Diagram with more button](https://github.com/gavingmiller/solarized/raw/master/screenshot.jpg)

6. Enjoy your awesome terminal color


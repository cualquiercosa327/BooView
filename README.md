# BooView
Data Visualizer for Super Mario Kart (SNES)


Quick Download: https://github.com/MrL314/BooView/archive/main.zip




## Requirements: 

1. Bizhawk 2.3 or above (http://tasvideos.org/BizHawk.html)
   - Run the prereq installer before installing if on Windows

If running from raw source code, make sure to use Python 3.6 (higher versions may not work properly), and run `SETUP.bat`

## Installation

1. Download BizHawk 2.3 or above
2. (If on Windows) Download and run the Bizhawk Prereq installer
3. Install BizHawk
4. Download **BooView** from link above and unzip



## How to run

1. Open BizHawk (**EmuHawk.exe**) and load a Super Mario Kart rom
   - Version should not matter
2. In BizHawk, go to **Tools > Lua Console**
3. In the Lua Console, go to **Script > Open Script**
4. Navigate to the downloaded folder, and click on **LuaSide.lua**
   - This should freeze the emulator for a few seconds, then resume after.
   - This will load the script into the console.
5. Run **BooView.bat**
   - Wait a few seconds until the welcome message appears
   - If running from raw source, run `python BooView.py`
7. In the Lua Console, double click on the red square next to **LuaSide**

If the script is already loaded in the console, all you need to do is step 5 and 6.


## Config Options

If you are having framerate issues, considering editting the options in the **config.json** file. A few issues come from the screen size for the rendered window, so you can adjust the window size and the amount of frame skipping. `window_size` will determine the size of the render window, and `frame_skip` will determine the amount of frames to wait between renders and polling the Lua script


## Special Notes
###### SMKWorkshop Discord
If you are interested in updates to this project, or Super Mario Kart in general, come join the 
Super Mario Kart Workshop Discord!
	https://discord.gg/QNcKNQC


###### MrL's Patreon:
This program is provided completely free of charge, at no cost to the user. However, it has been
brought to my attention that some people would like to donate in order to support me in my efforts
in making more -- as well as better -- tools for the community as a whole. If this applies to you, 
donate via the link below. 10% of all proceeds earned through that donation link will go towards 
the Autistic Self Advocacy Network, a charity devoted to the betterment of autistic and disabled
individuals.
 
Patreon:
	https://www.patreon.com/MrL314 




## GNU License
BooView is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, version 3 of the License.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

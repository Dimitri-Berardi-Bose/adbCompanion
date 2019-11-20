# adbCompanion
<br><br>

## Requirements
	1. ~/bin/ directory must exist
	2. To run from anywhere, users ~/bin/ directory must be in users PATH

## Installation
	1. Clone Repo into ~/bin/ directory
	2. Navigate to ~/bin/adbCompanion/ directory
	3. Run "./adbcompanion"
	
## Usage
	1. Plug in any number of adb-enabled devices
	2. Give device(s) a unique name (Only neccessary the first time a device is plugged in)
	3. Run "adbcompanion" from any directory to do the following
	    - adb_log
	        - Starts collecting logs to terminal, and to /scratch/logs/
		- When log collection is terminated (ctrl+c/ctrl+z), user
		  will be given the option to open the log in a text editor
	    - last_log
	        - Opens the last log collected to users /scratch/logs/ directory
	    - adb_shell
	    	- Opens an adb shell for users specified device
	    - clear_logs
	    	- Empties users /scratch/logs/ directory
	    - cp-bins-to-target
	        - Facilitates copying binaries to users specified device
		- Support the following music services:
		    - Spotify
		    - Amazon Music
		    - SiriusXM
		    - Deezer
		    - IHeart Radio
		- Gives user the option to build for "sdk=Release cfg=qc8017_32" first
 
	**More Services Coming Soon (or create your own)**

## Key Features
	- Multiple Devices w/ Unique Naming
	    - Store as many devices as you'd like, they'll be there in future sessions
	    - Name devices for easier recognition during future sessions
	    
	- Auto-Updating (Optional)
	    - Always run the latest version of adbCompanion, without even knowing it
	    - Any changes at run-time are stashed, and put back on exit
	    
	- Expandable Services
	    - Can run any shell script, without having to alter the existing code base
	    - Just create your script in the "adbCompanion/services/" directory
	    
	- Accessible from any Directory (above requirements must be met for this feature)
	    - No need to manually update your PATH, adbCompanion will be accessible 
	      from any directory after inital run

	- Settings for Complete Control (can be accessed by running "adbcompanion -s")
	    - Settings currently include:
	        - Toggle Auto-Update
		- Clear Device Names
		- Uninstall adbCompanion
		- Choose Preferred Editor

<br><br>
This project uses **kv-bash** under MIT License: Copyright (c) 2017 Phat (https://github.com/damphat)

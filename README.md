# adbCompanion
<br><br>

## Requirements
	1. ~/bin/ directory must exist
	2. To run from anywhere, your ~/bin/ directory must be in your PATH

## Installation
	1. Clone Repo into ~/bin/ directory
	2. Navigate to ~/bin/adbCompanion/ directory
	3. Run "./adbcompanion"
	
## Usage
	- Run "adbcompanion" from any directory to do the following:
	    - adb_shell
	    - cp-bins-to-target-spotify
	    - adblog

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

<br><br>
This project uses **kv-bash** under MIT License: Copyright (c) 2017 Phat (https://github.com/damphat)

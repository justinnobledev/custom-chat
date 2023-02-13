## Description
From what I've seen from publicly released chat color plugins is that they can only be defined via a config file which to me isn't very user friendly and does not let players change their stuff on the fly. So I decided to make a custom chat plugin based off of an old community I used to play on where the players can set their chat tag(with colors), name color and chat color by commands and menus.

## Commands

* sm_colors - Used to display the chat color menu
* sm_namecolors - Used to display the name colors menu
* sm_settag - Used to set a cusutom chat tag or print out the list of colors useable


## Changelog
	1.1
	Update to use enum struct over old syntax enums and converted from scp to chat-processor if their is a need for the scp version I can easily make a version that works with both
    1.0
    Initial Release

## Installation
1. Install simple chat processor - [link](https://forums.alliedmods.net/showpost.php?p=2629088&postcount=413)
2. Setup the database config
3. Install the plugin
4. Have fun with pretty colors

## Database
    
    "chatcolors"
    {
    	"driver"			"mysql"
    	"host"				"INSERT HOST HERE"
    	"database"			"INSERT DB NAME HERE"
    	"user"				"INSERT USER HERE"
    	"pass"				"INSERT PASSWORD HERE"
    	//"timeout"			"0"
    	//"port"			"0"
    }
    

Please report any problems to the github issue tracker
## [Github](https://github.com/R3TROATTACK/custom-chat/tree/master)

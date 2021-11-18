# Leftwm-theme doublebar

![Twist-Leftwm](https://github.com/PeterDauwe/doublebar/blob/master/doublebar.png)


# Get the theme to implement in your system

	git clone https://github.com/PeterDauwe/doublebar


# Changed some stuff in up !!!!!!!!!!!!!
	- config.toml will be changed according to your keyboard layout 
	- if you have personal keybinds put them in sxhkd directory,
		if not the standard will be	used.
	- picom is put in it's own directory.
	- background is changed on every login or reload.
	- polybar is split into two bars : polybartop , polybarbottom.

# Changes in template.liquid.
	- deleted some stuff in this file. Only occupied tags are visible and the focused tag is 		between brackets.

# Changes in config.toml.
	- move to tag and focus to tag has been replaced by one command
	   	[[keybind]]
		command = "Execute"
		value = "leftwm-command \"SendWindowToTag 1\" \"SendWorkspaceToTag 0 0\""
		modifier = ["modkey", "Shift"]
		key = "1"
	- scratchpad is added
	
# Themechanger.
	- made a script in directory scripts : changetheme.sh. This lets you in one go  : update,
		install and apply the theme of your choice.


Hope you like this, it was fun to make.



# Leftwm-theme doublebar


# Get the theme to implement in your system

	git clone https://github.com/PeterDauwe/doublebar


# Changed some stuff in up !!!!!!!!!!!!!
	- if you have personal keybinds put them in sxhkd directory inside your theme,
	those will be added to the standard, BE AWARE for double keybinds!!!!!!
	- background is changed on every login or reload.
	- backgrounds are in the theme
	- polybar is split into two bars : polybartop , polybarbottom.

# Changes in config.toml.
	- move to tag and focus to tag has been replaced by one command
	   	[[keybind]]
		command = "Execute"
		value = "leftwm-command \"SendWindowToTag 1\" \"SendWorkspaceToTag 0 0\""
		modifier = ["modkey", "Shift"]
		key = "1"
	- scratchpad is added

Hope you like this, it was fun to make.



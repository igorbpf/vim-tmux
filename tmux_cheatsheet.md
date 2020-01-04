# TMUX CHEATSHEET

##### Create new session
	- tmux new -s <session_name>


##### List all tmux sessions
	- tmux ls


##### Rename window
	- <prefix> + ,


##### Create new window
	- <prefix> + c


##### Switch window
	- <prefix> + p


##### Detach session
	- <prefix> + d


##### Attach session
	- tmux attach -t <session_name>


##### Close window
	- <prefix> + x


##### Create vertical pane
	- <prefix> + %


##### Create horizontal pane
	- <prefix> + "


##### Switch panes
	- <prefix> + o


##### Close pane
	- <prefix> + x


##### Resize panes
	- <prefix> + :resize-pane -U (-D or -L or -R) <number_of_cells>


##### Reload .tmux.conf file without killing session
	- <prefix> + :source-file ~/.tmux.conf (from tmux)
	- tmux source-file ~/.tmux.conf (from shell)



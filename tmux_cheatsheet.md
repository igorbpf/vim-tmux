# TMUX CHEATSHEET

##### Create new session
	- tmux new -s <session_name>


##### List all tmux sessions
	- tmux ls


##### Help
	- <prefix> + ?


##### Rename window
	- <prefix> + ,


##### Create new window
	- <prefix> + c


##### Switch window (previous)
	- <prefix> + p


##### Switch window (next)
	- <prefix> + n


##### Choose window
	- <prefix> + [0-9] 


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


##### Scroll inside pane
	- <prefix> + [ (to exit scroll mode press q)


##### Resize panes
	- <prefix> + :resize-pane -U (-D or -L or -R) <number_of_cells>


##### Reload .tmux.conf file without killing session
	- <prefix> + :source-file ~/.tmux.conf (from tmux)
	- tmux source-file ~/.tmux.conf (from shell)



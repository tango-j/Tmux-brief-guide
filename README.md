# Tmux-brief-guide
Tmux  It is a terminal multiplexer utility which has a capability to let you split up the screen in multiple console without any hassle of managing the size of terminal.

To get started type command "tmux" to start your tmux session.This will create a new tmux session with a nice all-green status bar at the bottom

The status bar shows you the multiple tmux sessions created by you and also helps us to navigate to different panes.
------------------------------------------------------------------------------------------------------------------------------------------------------------------
Ctrl+b is the default prefix in tmux utility and is used to instruct tmux session that user is going to give a command after the prefix. So before all commands we need to trigger the prefix command.

Handy commands:
#Spliting Panes
Prefix + % : Will split up the screen in two equal half vertically.
Prefix + " : Will split up the screen in two equal half horizontally.
#Adjust size of your pane : Prefix + (Ctrl+arrow keys)

#Navigating through the panes
Prefix + >/</up arrow/down arrow keys used to navigate through the new panes.

#Closing Panes
Prefix + d : Will close the current pane. This can also be done by typing command "exit".

#Creating Windows/Workspaces
Prefix + C : Will create a new workspace/window in the tmux session.

#Navigating	Windows/Workspaces
Prefix + p/n : Will switch from one window to another. p for previous and n for next wrt to the current workspace/window.

#Session Handling//*Best feature of tmux*
Prefix + D: Will give you an option of detaching from the tmux session without closing the task running in the session.
tmux ls : Will list the active detached sessions.
tmux attach -t <number of tmux session from above command o/p> : Will attach you back to the detached session.


#help command : Prefix + ?

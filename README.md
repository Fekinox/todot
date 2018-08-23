# todot

A shell-based todo list.

## About

Todot is an extremely minimalistic todo list manager, taking up no more than 200 lines of shell script. It's simple enough to get the job done.

Todot will keep track of its list in $HOME/.local/share/todot.

### Usage

+ `add` - Add a new task
+ `delete` - Remove a task
+ `check` - Mark a task as complete
+ `uncheck` - Mark a task as incomplete
+ `deleteall, checkall, uncheckall` - Applies respective command to all entries
+ list - Show all tasks. Pass an argument to show (c)omplete or (i)ncomplete tasks.
+ remind - If there are incomplete tasks, send a reminder via notification.

## Requirements

+ Requires GNU sed and notify-send.

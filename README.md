This project has moved to GitLab.

https://gitlab.com/Fekinox/todot

# todot

A shell-based todo list.

## About

`todot` is an extremely minimalistic todo list manager, taking up no more than 200 lines of shell script. It's simple enough to get the job done.

`todot` will keep track of its list in `$HOME/.local/share/todot`.

### Usage

```
todot list (c/i)	# List all todo list items and their IDs. Pass additional parameter to show (c)omplete or (i)ncomplete tasks.
todot remind		# Send a notification if there are incomplete tasks.
todot add "(item)"	# Add a new task.
todot check (id)	# Mark a task as complete.
todot uncheck (id)	# Mark a task as incomplete.
todot delete (id)	# Delete a todo list item.
todot checkall		# Mark all tasks as complete.
todot uncheckall	# Mark all tasks as incomplete.
todot deleteall		# Delete all tasks.
```

## Requirements

+ Requires GNU sed and notify-send.

## Upcoming features

+ Perhaps a daemon? So you wouldn't need to use crontabs to handle notifications, clearing the list every day, etc. Shouldn't be too hard.

# List running session
~~~
tmux ls
~~~

# Connect to session
~~~
tmux attach -t session_name
~~~

# Create new session
~~~
tmux new -s session_name
~~~

# New increment session
~~~
tmux new
~~~

# Detach from session
1. press "control-b"
2. release
3. press "d"

# Delete session
~~~
tmux attach -t session_name
exit
~~~
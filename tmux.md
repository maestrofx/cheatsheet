### Markdown cheatsheet

For details, you can used this one on references, I'll add some usecase based on my experiences


Tips
- Just install tmux to machine you want to remote

##### Tmux to remote server

    $ssh <user>@<hostname> -t tmux new -s <your_session_name> 

    $ssh franheit@192.168.1.10 -t tmux new -s remote_to_server
    
  1. franheit@192.168.1.10 : **host**
  2. -t : avoid **not a terminal** err
  3. tmux new -s remote_to_server : open new session named remote_to_server








#### References
- tmux shortcuts & cheatsheet by @MohamedAlaa | https://gist.github.com/MohamedAlaa/2961058
- http://www.dayid.org/comp/tm.html
- Start multiple synchronized SSH connections with Tmux | https://gist.github.com/dmytro/3984680

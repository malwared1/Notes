## Interactive TTY
```
python3 -c 'import pty;pty.spawn("/bin/bash")'                                             
export TERM=xterm                                                                          
CTRL + Z                                                                                   
stty raw -echo; fg   
```

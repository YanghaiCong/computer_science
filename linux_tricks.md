# [Screen](https://www.tecmint.com/keep-remote-ssh-sessions-running-after-disconnection/)

## in command line

### get into a new screen
> screen

### exit a screen
press `ctrl+a` then `d`

### resume a detached screen
> screen -r \[session # you want to kill\]

### kill a screen
> screen -X -S \[session # you want to kill\] kill

### kill all screens
> pkill screen  

> killall screen


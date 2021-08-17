# CiscoTerminalServer

Terminal Server Config used for labbing

## Commands
### check line numbers for async ports: 
show line

### clear an existing line: 
clear line x

### start the menu: 
menu TS

### always see menu when logging in:
line con 0

autocommand menu TS

### Commands for aync ports:
line 0/1/0 0/1/15

 exec-t 0
 
 no exec
 
 transport input telnet
 
 transport output none
 
 stopbits 1
 
 flowcontrol hardware

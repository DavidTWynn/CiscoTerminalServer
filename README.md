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
 
 ## Sources
 Configuring a Terminal/Comm Server - https://www.cisco.com/c/en/us/support/docs/dial-access/asynchronous-connections/5466-comm-server.html
 
 Configure Terminal Server through Menu Options - https://www.cisco.com/c/en/us/support/docs/dial-access/asynchronous-connections/200462-Terminal-server-configuration-using-Menu.html
 
 Cisco Terminal Server with ‘Menu’ command - https://routing-bits.com/2008/09/30/cisco-terminal-server-with-menu-command/

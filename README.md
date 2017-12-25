# ssh-function
SSH Functions for OSX to execute commands on multiple servers at once.

These shell functions require a server list from ~/.ssh/config

It allows:

 
 - execute local script on remote servers (remote)
 - upload a file to remote servers (rupload)
 - download files from remote servers (rdownload)
 - backup multiple or all servers via ssh (rbackup)


Its quite similar to ansible but only thes four functions are available (atm)

Unlike ansible it does not require Python and it does not require a separate Hosts file.
These functions just read the server list from default ssh config file.

Installation:

Place these functions in /.bashrc or /.zshrc and do "source ~/.zshrc.

Execution:

Required parameters are displayed when calling the function.


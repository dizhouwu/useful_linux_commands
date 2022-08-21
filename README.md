# useful_linux_commands

check process id using a port: netstat -tulpn | grep 3001

force kill the process: netstat -tulpn | grep 8088 | grep /python | awk '{print $7}' | cut -d'/' -f1-1 | xargs kill -9 

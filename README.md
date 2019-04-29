# chaturbate-daemon
Extremely simple daemon that automaticlaly downloads chaturbate streams with youtube-dl

# Requirements
Python 3, python-requests, youtube-dl, GNU screen

# Usage
1) Add the CB profiles you want to the array
2) Edit the systemd unit file accordingly, set your user and the directory you want to download to
3) Put service file in `/etc/systemd/system`
3) sudo systemctl start cb-daemon
4) Can use use screen -list and screen -r to connect to running youtube-dl sessions

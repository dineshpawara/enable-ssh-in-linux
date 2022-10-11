# enable-ssh-in-linux
**how to enable and disable ssh port in linux**

>apt install openssh-server

>mkdir /etc/ssh/default_keys

>mv /etc/ssh/ssh_host_* /etc/ssh/default_keys/

>dpkg-reconfigure openssh-server

>systemctl start ssh.socket

>systemctl enable ssh.service

**disable ssh port in linux**

>systemctl stop ssh.socket

>systemctl disable ssh.service

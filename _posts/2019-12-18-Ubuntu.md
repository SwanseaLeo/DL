
# Ubuntu
## Comand
***Whether the specific port is used.***
```
netstat -anp|grep port_num
```
***Cancel Verify-Peer.***
```
Add lines to /etc/apt/apt.conf
For Example:
Acquire::https::nvidia.github.io::Verify-Peer "false";
Acquire::https:: developer.download.nvidia.com::Verify-Peer "false";
```
***Ubuntu Version***
```
lsb_release -a
```
***Compress file***
```
tat -cvf xx.tar ./xxx
./xxx : source folder.
xx.tar : The name of compressed file.
```

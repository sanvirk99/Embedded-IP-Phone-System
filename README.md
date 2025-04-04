# 433-ip-phone

## System Diagram 
<img src="https://github.com/user-attachments/assets/a98e223c-2803-4743-82ab-23079ce04484" alt="systems diagram" width="400">

## Run the node app locally
```
$(host) make
$(bbg) cd /mnt/remote/myApps/ip_phone_node_copy
$(bbg) node server.js
```
App url: 192.168.7.2:8080


Intial account url is hard coded modify this using getaddr.. function call 
pjsua module starts up similar to udp module, currently fucntion dependent on cli modify this to be dependedent on the fucntion calls which are thread safe

## Beagle phone 
### note some hardware is not being used on this particular version
<img src="https://github.com/user-attachments/assets/0aa0fa0d-71ba-4fb0-9627-8a83e57b2127" alt="beaglephone" width="400">




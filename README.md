# note
justnotes

## Sudoers  
```  
chmod 777 /etc/sudoers
vi /etc/sudoers
chmod 440 /etc/sudoers
```  

## Route on WIFI  
Add:  
```  
neuron.jumpdesktop.com
route add 3.222.180.101 mask 255.255.255.255 192.168.43.71
route add 54.173.246.23 mask 255.255.255.255 192.168.43.71

route add 3.215.173.234 mask 255.255.255.255 192.168.43.60
route add 3.221.168.103 mask 255.255.255.255 192.168.43.60

route add 175.162.109.106 mask 255.255.255.255 192.168.43.60
route add 66.206.3.114 mask 255.255.255.255 192.168.43.60
route add 108.177.15.127 mask 255.255.255.255 192.168.43.60
route add 172.105.221.0 mask 255.255.255.0 192.168.43.60
route add 18.195.48.0 mask 255.255.255.0 192.168.43.60
```

Remove:
```
route DELETE 3.215.173.234 mask 255.255.255.255
route DELETE 3.221.168.103 mask 255.255.255.255

route DELETE 175.162.109.106 mask 255.255.255.255
route DELETE 66.206.3.114 mask 255.255.255.255
route DELETE 108.177.15.127 mask 255.255.255.255
route DELETE 172.105.221.0 mask 255.255.255.0
route DELETE 18.195.48.0 mask 255.255.255.0
```


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

## ssh密钥登录  
```  
ssh-keygen  ##一路回车
ls .ssh/
ssh-copy-id root@目标主机    ##拷贝公钥到目标主机
```  

## Ansible  
所有模块: https://docs.ansible.com/ansible/latest/modules/list_of_all_modules.html  
`ansible all -m shell -a "ls /root"`  
常用命令: shell

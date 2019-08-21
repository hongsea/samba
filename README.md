# samba
```
sudo docker poll hongsea/samba
sudo docker run -d -p 135:135/tcp \
-p 137:137/udp \
-p 138:138/udp\ 
-p 139:139/tcp \
-p 445:445/tcp \
-v <Directory>:/shared \
--name samba \
hongsea/samba
```

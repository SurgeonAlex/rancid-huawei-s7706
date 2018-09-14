# rancid-huawei-s7706
huawei s7606 work scripts file to rancid-3.2-2 program!

Rhel based distributive configure!

1) Copy hulogin and hurancid in to the working directory - my working copy dir is /usr/libexec/rancid

2) Edit the file - rancid.types.base, and add end of the file string - huawei;script;hurancid,  my path to config file /etc/rancid/rancid.types.base

3) Add string in to the file .cloginrc - add method 1.2.3.4 ssh, add autoenable 1.2.3.4 {[01]}

4) Add string in to the file routers.db - 1.2.3.4;huawei;up

#1.2.3.4 it's your huawei ip address.

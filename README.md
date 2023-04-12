# helh
Home Engryption Login Helper

1. setup with luks an encrypted home partition
2. create an autlogin remote user
3. copy autostart, password, and try_home into bin folder of remote user (make sure autstart is started)
4. copy cryptsetup_home to /usr/local/sbin and configure it for your system
5. add to /etc/sudoers: ``remote ALL=(root) NOPASSWD: /usr/local/sbin/cryptsetup_home``

 

# network
![network](https://cdn.pixabay.com/photo/2018/12/10/10/21/earth-3866609_960_720.jpg)
network setup and configuration (RHEL)

Disable or enable ipV6:
```sh
$ sysctl -w net.ipv6.conf.all.disable_ipv6=1
```
##Fail2Ban
List input rulles:
```sh
$ iptables -L INPUT -v -n
```
vim /etc/fail2ban/fail2ban.conf
vim /etc/fail2ban/jail.conf
ittables -L
iptables -L
cat /etc/denyhosts.conf
cat /etc/hosts.deny

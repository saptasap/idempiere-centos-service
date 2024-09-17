# iDempiere CentOS service
Install iDempiere as a service in centos using init script (tested with CentOS 8, CentOS 8 Stream).
Run as root :
```
cp /opt/idempiere-server/utils/unix/idempiere_RedHat.sh /etc/init.d/idempiere
systemctl daemon-reload
systemctl enable idempiere     # to enable iDempiere from start on reboot
```
then start iDempiere Service
```
systemctl start idempiere
```
See original how-to from [Running iDempiere from Installers]([https://pages.github.com/](https://wiki.idempiere.org/en/Running_iDempiere_from_Installers))

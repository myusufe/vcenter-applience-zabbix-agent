# vcenter-applience-zabbix-agent

This Zabbix-agent binary is for vMware 6.7U1 Photon 1.0 OS. Already tested and validated using vMware 6.7U1.
To install it, you have to get all files, and copy it to right directory.

```
cp -frp usr/bin/* usr/bin
cp -frp etc/zabbix /etc/
cp -frp var/log/zabbix /var/log/
cp -frp var/run/zabbix /var/run/
```

Then edit /etc/zabbix/zabbix_agent.conf file, and change Server, ServerActive, and Hostname config as you have, then run Zabbix-agent using this command,

```
/usr/bin/zabbix_agentd -c /etc/zabbix/zabbix_agent.conf
```
Please donate to the author, so he can continue to publish other awesome project for free:

[Donate via PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=P4VC8MCT7NDKJ&source=url)

# vcenter-applience-zabbix-agent

This Zabbix-agent binary is for vMware 6.7U1 Photon 1.0 OS. Already tested and validated using vMware 6.7U1.
To install this your have to extract tar file or copy all file to appropriate directory.

After you got the file, run this command,

cd /
tar xvfz zabbix_agent_photon.tgz

Then run Zabbix-agent using this command,

/usr/bin/zabbix_agentd -c /etc/zabbix/zabbix_agent.conf

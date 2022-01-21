# Ansible Role: squid_exporter

This Ansible role installs squid_exporter from the project http://github.com/boynux/squid-exporter/ 

This role is totally based on the ansible role mysql_exporter from cloudachemy (https://github.com/cloudalchemy/ansible-mysqld_exporter)

Ansible Variables
-------------------------
```
squid_exporter_label: {}
squid_exporter_metrics_path: '/metrics'
squid_exporter_squid_pid: ""
squid_exporter_squid_port: 3128
squid_exporter_version: '1.10.0'
squid_exporter_web_listen_address: "0.0.0.0:9301"
```

This role was tested with the version v1.10.0 of squid_exporter.

## License

MIT

## Authors Information

* Pawel Krupa
* Baptiste Mille-Mathias <baptiste.millemathias@gmail.com>

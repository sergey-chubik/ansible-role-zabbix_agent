Ansible Role: Zabbix_Agent
=========

Эта роль установит zabbix agent версии 5.0 на сервер с ОС CentOS или Ubuntu

Requirements
------------

None.

Role Variables
--------------

Доступные переменные перечислены ниже вместе со значениями по умолчанию в файле **defaults/main.yml**.

Dependencies
------------

Также необходимо открыть следующие порты в firewall:
```
- port: 10050-10051/tcp
- port: 161-162/udp
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - zabbix_agent

License
-------

BSD

Author Information
------------------

Chubik Sergey.

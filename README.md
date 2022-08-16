Role Name
=========
Simple [Nginx](https://nginx.org/en/docs/) deploy on EL7 

Requirements
------------
EL7 OS

Role Variables
--------------
``` yaml
nginx_user: root
nginx_config_dest: "/etc/nginx/nginx.conf"
```

Example Playbook
----------------

    - name: Install my_nginx
      hosts: nginx servers
      roles:
        - nginx-role

License
-------
MIT

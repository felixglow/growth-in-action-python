部署
===

配置管理 
---

local_settings.py

Fabric
---

 - NGINX - public facing web server
 - gunicorn - internal HTTP application server
 - PostgreSQL - database server
 - memcached - in-memory caching server
 - supervisord - process control and monitor
 - virtualenv - isolated Python environments for each project
 - git or mercurial - version control systems (optional)

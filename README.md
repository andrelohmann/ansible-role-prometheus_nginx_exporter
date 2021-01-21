andrelohmann.prometheus_nginx_exporter
======================================

Install and configure nginx-prometheus-exporter

https://github.com/nginxinc/nginx-prometheus-exporter

Role Variables
--------------

    prometheus_nginx_exporter_scrape_uri: http://localhost:8080/stub_status # URL, where nginx is serving the stub_status
    prometheus_nginx_exporter_listen_ip: 127.0.0.1
    prometheus_nginx_exporter_listen_port: 9113

Example Playbook
----------------

    - hosts: prometheus_nginx_exporter
      roles:
      - andrelohmann.prometheus_nginx_exporter

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann

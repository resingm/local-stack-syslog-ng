# local-stack-syslog-ng

Repository contains configuration files for the centralized syslog-ng setup for
my servers and my VPS instances.

## syslog-ng.conf.server

Server configuration file. Listens on TCP port 514.

## syslog-ng.conf.client

Client configuration file. Logs to the local `/var/log/messages` but also
uploads logs to the remote syslog-ng log collector `10.8.0.9:514`.



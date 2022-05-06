# DevOps-Experimentations 

## Basic information

Here is an experimental project for ansible, vagrant and docker swarm.

Playbooks directory description:

***1. config_docker_compose.yml***

Playbook for install and config docker and docker-compose

***2. install_proxychains4.yml***

Playbook install proxychains4 and microsocks.
It allows you to use it like TOR, but with your proxies.
All requests sends like this `host -> proxy1 -> proxy2 -> proxy3` and so on.
You can use proxychains as a proxy server through socks5://loclahost:1080

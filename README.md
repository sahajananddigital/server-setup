# server-setup

## Installation steps
- Install Docker
- We are going to use https://nginxproxymanager.com/setup/ because it is easy to setup
- Then we will run our setup in docker

## Startup
- goto http://localhost:81 to access the Ngnix proxy manager
- Assign internal 172.x.x.x ip with port of docker application with test.localhost for local dev
- Assign internal 172.x.x.x ip with port for actual domain for the production setup

this will route traffic to specific container. We can even use traefik proxy if you are confident

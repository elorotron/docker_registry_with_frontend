# **docker_registry_with_frontend**
---
## Manual
### 1. Tag your image 
##### docker tag [image] [ip_address_of_ur_docker_registry_machine]:5000/[name_of_image]
### 2. Push tagged image to your docker registry server
##### docker push [ip_address_of_ur_docker_registry_machine]:5000/[name_of_image]

### P.S. if you have error with push image to your server (http error) edit /etc/docker/daemon.json
##### { "insecure-registries" : ["#ip_address_of_ur_docker_registry_machine#:5000"] }
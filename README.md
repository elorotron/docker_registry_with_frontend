# docker_registry_with_frontend
# Manual
# docker tag [image] [ip_address_of_ur_docker_registry_machine]:5000/[name_of_image]
# docker push [ip_address_of_ur_docker_registry_machine]:5000/[name_of_image]
# if have error with http edit /etc/docker/daemon.json
# { "insecure-registries" : ["#ip_address_of_ur_docker_registry_machine#:5000"] }
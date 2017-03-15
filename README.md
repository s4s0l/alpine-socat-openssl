# alpine-socat-openssl
Docker image based on alpine with openssl and socat meant for docker unix socket forwarding. 

Example can be found https://github.com/s4s0l/docker-gen/tree/master/examples/swarm. This example has sligtly different purpose, but in prepare.sh there is some piece of code that prepares certificates and in docker-compose-socating.yml is an example service that uses this image.

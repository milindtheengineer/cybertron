# cybertron
config files and readmes for personal lab running on a laptop

### ports

portainer: 9000
registry: 9001
gogs: 9002
drone: 9003

### Notes

* having an incorrect hostname will not allow drone to register new repo and throws nilpointer exceptions without specific errors
* root url should be properly configured for gogs. Else, drone will not be able to clone


### To-do

* ngrok integration and caddy service
* all services should only talk to each other through caddy
* object storage with minio
* Evaluate need of k3s or micro k8s
* automate everything and probably build a image based on lightweight distro :D

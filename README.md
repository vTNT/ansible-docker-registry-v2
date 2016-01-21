ansible-docker-registry
===============================
role to install docker registry on ubuntu </br>
docker version: 1.9.1 </br>
registry version: 2.2.1 </br>

usage
-----
usage: ansible-playbook setup.yml -i hosts </br>

## Users


Usernames started with just `admin` have access to modify registry.
Push images, create, remove tags.

Any other useers can only read registry.

###Default users
admin:admin

readonly:readonly

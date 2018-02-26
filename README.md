# Docker SSH
The goal of this project is to provide Docker SSH images based on multiple operating systems and Supervisord in order to provide the infrastructure necessary to develop and test Ansible Playbooks and other similar automation suites using Docker.

## Inspiration
This project was inspired by the work done on the Docker container `centos-ssh` by @newswangerd for their project [newswangerd/learn-ansible](https://github.com/newswangerd/learn-ansible). The Docker images used in that project where:
+ [jdeathe/centos-ssh](https://github.com/jdeathe/centos-ssh) as the parent/base image.
+ [newswangerd/learn-ansible/centos-ssh](https://github.com/newswangerd/learn-ansible/tree/master/centos-server) as the actual image used.

## License
This project is licensed under the [GPLv3](LICENSE).

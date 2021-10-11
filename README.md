## SH

Fast check for TCP open ports and their active listeners
```
$ sudo netstat -plnt
```

Destroy a tree within a folder and a folder itself completely (impossible to recover)
```
$ rm -rf <folder>
```

## Docker

Checking for running containers
```
$ docker container ls
```

## Ansible
Single command (AWS)
```
$ ansible <hosts> --private-key <key-location> -m command -a <shell-command-itself> -u ec2-user
```
Playbook execution (AWS)
```
$ ansible-playbook --private-key <key-location> -K <playbook-location> -u ec2-user
```
## SSH
Easy AWS SSH
```
$ ssh -i <key-location> ec2-user@<host>
```

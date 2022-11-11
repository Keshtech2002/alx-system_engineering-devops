# 0x0B. SSH
#### Learning Objectives
- What is a server
- Where servers usually live
- What is SSH
- How to create an SSH RSA key pair
- How to connect to a remote host using an SSH RSA key pair
- The advantage of using #!/usr/bin/env bash instead of /bin/bash

####  To be able to login to a server from your machine
- ```cd ~/.ssh```
- Create a keygen with ```ssh-keygen```
- Copy the public key
- Open the server you want to login to
- ```cd ~/.ssh```
- Add the public key
- You will be able to login to the server from your machine now

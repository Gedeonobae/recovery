# 0x0E Web stack debugging #1
## Requirements
## General
* Allowed editors: vi, vim, emacs
* All your files will be interpreted on Ubuntu 20.04 LTS
* All your files should end with a new line
* A README.md file at the root of the folder of the project is mandatory
* All your Bash script files must be executable
* Your Bash scripts must pass Shellcheck without any error
* Your Bash scripts must run without error
* The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
* The second line of all your Bash scripts should be a comment explaining what is the script doing
* You are not allowed to use wget

## Tasks

* **0. Nginx likes port 80**
  * [0-nginx_likes_port_80](./0-nginx_likes_port_80): Bash script that
  configures Nginx to run and listen to port 80 on all of a server's active IPv4's.

* **1. Make it sweet and short**
  * [1-debugging_made_short](./1-debugging_made_short): Bash script that
  configures Nginx to listen to port 80 without running on all of a server's
  active IPv4's.
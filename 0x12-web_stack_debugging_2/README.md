# 0x12 Web stack debugging #2

## Requirements
## General
* All your files will be interpreted on Ubuntu 14.04 LTS
* All your files should end with a new line
* A README.md file at the root of the folder of the project is mandatory
* All your Bash script files must be executable
* Your Bash scripts must pass Shellcheck without any error
* Your Bash scripts must run without error
* The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
* The second line of all your Bash scripts should be a comment explaining what is the script doing

## Tasks

* **0. Run software as another user**
  * [0-iamsomeonelese](./0-iamsomeonelese): Bash script that runs the command
  `whoami` under the user passed as argument.
  * Usage: `./0-iamsomeonelese <user>`

* **1. Run Nginx as Nginx**
  * [1-run_nginx_as_nginx](./1-run_nginx_as_nginx): Bash script that fixes a
  web server to run Nginx listening on port `8080` as the `nginx` user.
* **2. 7 lines or less**
  * [100-fix_in_7_lines_or_less](./100-fix_in_7_lines_or_less): Bash script
  that fixes a web server to run Nginx listening on port `8080` as the `nginx`
  user.
  * 7 lines long.
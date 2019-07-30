# Docker-Install

<br />

##### 1] Setup Terraform in project <br />
### 2] *"Install docker/docker-compose"*
#### Terraform workaround:
- Split install scripts into docker and docker-compose:
  - eg. docker:
    - docker: pull repo (available on my github)
    - cd in docker dir
    - run install script
  - eg. docker-compose:
    - cd in docker-compose dir
    - run install script
- When running the scripts through *.tf* **"remote-exec" provisioner**, every entry will run as a fresh terminal <br />
(bypassing manual reset) <br />
##### 3] Profit


---
title: Docker_Command
published: true
---


## Comand
***Run Docker***
```
nvidia-docker(or docker) run -it --name pytorch_docker  -v /:/home/ pytorch_1.3:tag /bin/bash
```
***Add shared memory***
```
add parameters
--shm-size 10G
```
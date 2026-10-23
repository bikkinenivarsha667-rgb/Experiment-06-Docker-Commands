\# Experiment 6: Explore Docker Commands for Content Management



\## Aim

To explore and practice Docker commands for managing images and containers.



\## Commands and Description



| S.No. | Docker Command | Description |

|---|---|---|

| 1 | `docker --version` | Displays the installed Docker version. |

| 2 | `docker info` | Displays Docker system information. |

| 3 | `docker pull ubuntu:16.04` | Downloads the Ubuntu 16.04 image. |

| 4 | `docker images` | Lists locally available Docker images. |

| 5 | `docker run --name mycontainer -it ubuntu:16.04 /bin/bash` | Creates and runs an interactive Ubuntu container. |

| 6 | `docker ps` | Lists running containers. |

| 7 | `docker ps -a` | Lists all containers, including stopped containers. |

| 8 | `docker start mycontainer` | Starts an existing container. |

| 9 | `docker stop mycontainer` | Stops a running container. |

| 10 | `docker rm mycontainer` | Removes a stopped container. |

| 11 | `docker tag myimage:latest varsha0510/myimage:latest` | Tags the image for Docker Hub. |

| 12 | `docker push varsha0510/myimage:latest` | Pushes the image to Docker Hub. |



\## Result

The Docker commands were explored and executed to manage images and containers. The `myimage:latest` image was successfully pushed to Docker Hub under the repository `varsha0510/myimage`.




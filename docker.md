Docker
===

- [Docker Docs](https://docs.docker.com/)
- [菜鸟教程-Docker](https://www.runoob.com/docker/docker-tutorial.html)

Concepts
===

1. Image
2. Container
3. Volume
4. Docker Compose

Common Commands
===

Service
---

- Docker version information: `docker version`
- Docker brief information: `docker -v`
- Start Docker:
- Close Docker:

Lifecycle
---

| Meaning                               | Commands                                 |
| ------------------------------------- | ---------------------------------------- |
| List all running containers           | `docker ps`                              |
| List all containers                   | `docker ps -a`                           |
| Pull pre-built images from Docker Hub | `docker pull`                            |
|                                       | `docker images`                          |
|                                       | `docker stop <container_name>`           |
|                                       | `docker exec -it <container_id> command` |

- `-it`: interactive

Dockerfile
===

3.1 Content in a dockerfile
---

1. Base Image
2. Install all libraries
3. Copy code and data
4. run the training loop

3.2 Commands
---
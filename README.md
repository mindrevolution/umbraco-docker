# Umbraco 9 Docker
## Quickly fire up Umbraco 9 and a database in containers for projects, play and fun.

**This is a development container with an insecure and publicly shared configuration. Please do not deploy this to production via either Docker or Kubernetes.**

### Prerequisite
Docker from https://www.docker.com/get-started

### Containers
1. [Umbraco 9 (alpha 4)](https://hub.docker.com/repository/docker/mindrevolution/umbraco])
2. [MS SQL Express 2019 (Linux)](https://hub.docker.com/_/microsoft-mssql-server)

### How to use
1. Clone repo: **git clone https://github.com/mindrevolution/umbraco-docker.git**
2. Change into repo folder: **cd umbraco-docker**
3. Run: **docker-compose up**
4. Browse http://localhost:9000

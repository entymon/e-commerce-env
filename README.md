### Setup Docker Environment
1. Run command `docker-compose up -d`
2. Open pgadmin on `localhost:8888` or different port, depends on docker-compose.yml file
3. Set server connection by clicking on `add server` 
  - for `Name` choose whatever as it is internal name, 
  - next click `connection` tab on top
  - for `Host` type `host.docker.internal` - as postgress is set on docker (!IMPORTANT)
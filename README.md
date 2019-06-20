# jenkins-docker
Official jenkins image plus docker

 - Auto update when have new push on officual jenkins image
 - Rebuild with latest stable docker version

## Note
- When running the container. Please mount host docker socket. Ex:

```
   docker container run -d -p 8080:8080 -v /var/run/docker.sock:/var/run/docker.sock jenkins-docker
```

# containers
```bash
# run an image (run)
docker run jenkins
# detach a container when running (-d)
docker run -d jenkins
# publish a port (-p <host-port>:<container-port>)
docker run -d -p 80:8080 jenkins
# set the name of the container (--name <name>)
docker run -d -p 80:8080 --name jenkins jenkins
# execute a command on a running container (exec <container-name> <command>)
docker exec jenkins echo hi
# get an interactive terminal on a container (-it)
docker exec -it jenkins bash
# stop a container (stop <container-name>)
docker stop jenkins
# start a container (start <container-name>)
docker start jenkins
# rename a container (rename <old-name> <new-name>)
docker rename naughty_dubinsky jenkins
```

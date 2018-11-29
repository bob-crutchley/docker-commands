# images
With image commands the tag is always optional, of ommitted it will default to `:latest`
```bash
# search for an image (docker search <image>:<tag>)
docker search java:8
# download an image (docker pull <image>:<tag>)
docker pull java:8
# remove an image (docker rmi <image>:<tag>)
docker rmi java:8
# rename an image (docker tag <old-image>:<old-tag>)
docker tag java:8 bobcrutchley/java:8
```


# Section 2

## Commands

```
docker build -t apecr/debian .
docker run <imageId>
docker run <imageId> echo "hello docker" ## overwrites CMD
docker run -it <imageId> # Enter in the image
docker tag <imageId> apecr/debian:1.0.0 # Tag the image
docker login --username=<username>
docker push apecr/debian:1.0.0
```
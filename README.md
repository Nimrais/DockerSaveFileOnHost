# DockerSaveFileOnHost
Minimal example when the docker container saves a file on a host machine

```bash
docker build . -t mytest
docker run -v "$(pwd)/mnt:/tmp" mytest python test.py
```

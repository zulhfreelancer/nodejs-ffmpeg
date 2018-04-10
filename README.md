# Alpine Linux NodeJS with FFmpeg

This Dockerfile is based on [Node Alpine 9](https://hub.docker.com/_/node/) with FFmpeg installed.


## Build
```bash
docker build -t node-ffmpeg .
```

## Run

```bash
docker run -it --rm --name my-node-ffmpeg node-ffmpeg
```

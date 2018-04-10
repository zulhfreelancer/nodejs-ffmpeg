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

## DockerHub

If you want to include this in your Docker image, simply add the following line on top of your Dockerfile:

```
FROM zulhfreelancer/node-ffmpeg:latest
```

The image can be found on [DockerHub](https://hub.docker.com/r/zulhfreelancer/node-ffmpeg/).

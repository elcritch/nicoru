# nicoru

A container runtime written in Nim.

NOTE: Work in progress.

# Features

- Create/Run a container

- Daemon-less

- Docker image support

- Management of container/image

## Installation

nicoru can run on only GNU/Linux

- Nim v1.4.8 or higher

```
nimble install nicoru
```

## Quick start

You need to be root to run nicoru.

```
sudo nicoru run ubuntu
```

Run the above command will download ubuntu:latest image from Docker Hub, run the container and attach it.

Please check [more](https://github.com/fox0430/nicoru/tree/develop/documents/command.md)

## License

MIT

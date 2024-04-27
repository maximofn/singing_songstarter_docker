# Singing Songstarter docker
Dockerization of the [Hugging Face Singing Songstarter Space](https://huggingface.co/spaces/nateraw/singing-songstarter)

 * Model card: [nateraw/musicgen-songstarter-v0.2](https://huggingface.co/nateraw/musicgen-songstarter-v0.2)
 * Space: [nateraw/singing-songstarter](https://huggingface.co/spaces/nateraw/singing-songstarter)
 * Replicate [nateraw/musicgen-songstarter-v0.2](https://replicate.com/nateraw/musicgen-songstarter-v0.2)

To make from this

https://github.com/maximofn/singing_songstarter_docker/assets/15805036/305662c7-f30c-4bad-b900-51a8e4cf9b01

To this

https://github.com/maximofn/singing_songstarter_docker/assets/15805036/853d1348-6be6-45f4-951b-c04b56afbca8

## Requisites

[Docker](https://docs.docker.com/desktop/) and [nvidia container toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html) must be installed.

## Usage

### Download the image from the Docker Hub

You can download the image and run it

```bash
docker pull maximofn/singing_songstarter:latest
./run_app.sh
```

### Build the image

Or you can build the image and run it

```bash
./build_docker_image.sh
./run_app.sh
```

# Nextcloud Docker Setup with FFmpeg

This repository contains a Docker setup for Nextcloud with FFmpeg installed. This setup ensures FFmpeg is installed every time the Nextcloud container starts. This will allow Memories to show thumbnails for most video and picture formats.

## Contents

- `Dockerfile`: Custom Dockerfile to install FFmpeg in the Nextcloud container.
- `docker-compose.yml`: Docker Compose file to build and run the Nextcloud and MariaDB containers.

## Requirements

- Docker
- Docker Compose

## Setup

1. Clone this repository:
   ```sh
   git clone https://github.com/Cameron22T/nextcloud_ffmpeg_docker
   cd nextcloud_ffmpeg_docker

2. Modify docker-compose for your set up, make sure to set up your own credentials.
3. Start nextcloud container:
   ```
   docker-compose up -d

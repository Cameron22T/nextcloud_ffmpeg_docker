# Nextcloud Docker Setup with FFmpeg

This repository contains a Docker setup for Nextcloud with FFmpeg installed. This setup ensures FFmpeg is installed every time the Nextcloud container starts.

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

2. Modify docker-compose for nextcloud, mariadb database setup as normal.
3. Start nextcloud container:
   ```
   docker-compose up -d

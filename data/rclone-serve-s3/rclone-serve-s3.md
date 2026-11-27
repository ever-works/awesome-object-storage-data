## Overview

rclone serve S3 is a feature of rclone that serves any of its remotes over the S3 protocol, turning anything rclone supports into a temporary S3 endpoint. It is handy for bridging an odd backend to S3 tools for a one-off transfer.

## Features

- Serves any rclone remote over the S3 protocol
- Turns any rclone-supported backend into a temporary S3 endpoint
- Useful for one-off transfers between odd backends and S3 tools
- Self-hosted deployment

## Deployment

Self-hosted. Endpoint format: `http://<host>:8080`. Addressing: path-style.

## License

Open source (MIT).
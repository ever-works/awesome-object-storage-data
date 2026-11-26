## Overview

s3-orchestrator is a storage orchestration layer that presents multiple cloud providers as a single S3 endpoint. It maintains N copies across different backends with read failover, and supports optional per-backend limits for bytes, requests, ingress, and egress. Additional features include zstd compression and envelope encryption.

## Deployment

Self-hosted. Built with Go, supports Docker, deb packages, and Kubernetes.

## License

MIT License. Source code available on GitHub.

## Features

- Single S3 endpoint for multiple cloud providers
- N-copy replication across backends
- Read failover
- Per-backend byte, request, ingress, and egress limits
- zstd compression
- Envelope encryption
- Go, Docker, deb, and Kubernetes support

## Pricing

Free and open-source under the MIT license.
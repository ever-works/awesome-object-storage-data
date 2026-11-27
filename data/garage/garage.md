## Overview

Garage is a distributed object storage system written in Rust, developed by the Deuxfleurs collective for self-hosted CDN scenarios. It is S3-compatible and uses an AGPL 3.0 license.

## Architecture

Pure key-value distributed architecture where every node knows about every object. Geo-distribution is first-class - replication across distant nodes is the default mode rather than an optional feature.

## Features

- S3-compatible API
- Native geo-distribution across multiple geographic locations
- Single binary deployment with simple configuration
- Minimal resource footprint (512 MB RAM minimum)
- Rust safety guarantees (memory safety, fewer crash classes)
- Key-value distributed storage

## Weaknesses

- Smaller community than SeaweedFS or Ceph
- AGPL license can complicate commercial deployment
- Less mature than alternatives (5 years versus 12+ for SeaweedFS)
- Fewer features (no advanced tiering, limited monitoring integration)

## Quick Start

Download from garagehq.deuxfleurs.fr, generate config, start daemon, initialize cluster, create access key and bucket. S3 endpoint at http://localhost:3900.

## License

AGPL 3.0

## Deployment

Self-hosted
## Overview

Upstash Blob is S3-compatible object storage designed for web applications such as user file uploads, avatars, documents, and exports. It includes an upload SDK and React hook so browsers can upload directly to the bucket without IAM users, bucket policies, or CORS rules.

## Key Features

- S3-compatible API via `bucket.s3()` returning endpoint, region, credentials, and bucket name for use with AWS SDK, AWS CLI, and other S3 tools
- Browser upload handler with server-side authorization and signing; bytes go straight from browser to storage
- Upload React hook (7.6 KB gzipped) with progress tracking, pause, resume, cancel, and retry
- Automatic multipart upload for files over 16 MB with per-part retry and resume after connection drop
- Global CDN for file delivery with no additional CDN cost
- Same pricing worldwide; no replication or cross-region transfer charges
- SDKs for TypeScript, Python, and Go
- Shares account and billing with Upstash Redis, QStash, and Workflow

## Pricing

- Storage: $0.02 per GB per month (billed on monthly average bucket size)
- Read operations: $0.30 per million (origin or CDN)
- Write, copy, and list operations: $4.50 per million
- Delete operations: Free
- Egress: Free up to 1 TB per month, then $0.02 per GB (uploads do not count against bandwidth)
- Free tier available (no credit card required)

## Deployment

Cloud-managed service.

## Repository

Not open source; proprietary managed service.
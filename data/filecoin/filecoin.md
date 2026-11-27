## Overview

Filecoin is a peer-to-peer storage network with economic incentives. Clients store content with storage providers, and retrieval can involve provider discovery through content identifiers and protocols including HTTP, Bitswap, and Graphsync.

## Core Model

Decentralized marketplace using storage deals and cryptographic proofs. Storage deals are time-bound, although applications can renew them and create many copies.

## Good Fit For

- Large content-addressed archives
- Public datasets
- Backups
- Applications that value verifiable decentralized storage

## Not Ideal For

- Teams expecting every object to behave like a low-latency S3 request without an on-ramp, retrieval service, cache, or gateway layer

## Implementation Questions

- How many providers store each dataset?
- Is a hot copy available?
- What is the recovery-time objective?
- Which retrieval client or gateway is used?
- How are deals renewed and monitored?

## Cost Model

Provider and deal economics plus retrieval. Pricing emerges through storage markets and service providers.

## Primary Sources

- Filecoin documentation
- Filecoin retrieval documentation

## Common Considerations

Filecoin provides flexibility but may involve deal, provider, and retrieval tooling. Buyers must know what happens at deal expiry and whether other systems retain the data. Availability and durability are different properties; test the full delivery path including gateway, cache, and CDN.
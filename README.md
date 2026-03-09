# Capacity Conditioned Continuation in Resource Constrained Activity Networks

**Author:** J. M. Bookbinder  
**Affiliation:** Witness Grade Analytics, Atlanta, GA, USA

This repository contains the sealed paper artifact and publication packet for:

**Capacity Conditioned Continuation in Resource Constrained Activity Networks**

## Contents

- `paper/` : source manuscript and source hash receipt
- `artifact/` : seal, manifest, manifest-hashes, tarball packet, and SHA-256 receipts

## Verification

To verify the sealed bundle, run:

```bash
shasum -a 256 -c artifact/Capacity_Conditioned_Continuation_PACKET.tar.gz.sha256
shasum -a 256 -c paper/"Capacity Conditioned Continuation in Resource Constrained Activity Networks.txt.sha256"
```

## Expected

```text
artifact/Capacity_Conditioned_Continuation_PACKET.tar.gz: OK
paper/Capacity Conditioned Continuation in Resource Constrained Activity Networks.txt: OK
```

## Release

See `RELEASE_v1.0.txt` for release framing and packet notes.

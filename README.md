# GrandGain Runtime Configuration

Public runtime configuration and synchronization repository for GrandGain Automation NX services.

## Overview

| File | Purpose |
|---|---|
| `appsettings.json` | Active runtime configuration and synchronization manifest |

## Synchronization

- Client applications synchronize configuration metadata over secure HTTPS.
- Integrity is verified cryptographically using SHA-256 digests.

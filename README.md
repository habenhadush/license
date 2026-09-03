# GrandGain License Repository

This is the **public** quarterly license distribution repository for GrandGain Automation NX products.

## What is in this repo

| File | Purpose |
|---|---|
| `license.json` | The active RSA-2048 signed quarterly license token |

## How it works

- Client machines automatically fetch `license.json` over HTTPS on startup.
- The token is cryptographically signed with RSA-2048 — it cannot be forged or modified.
- No private keys or tooling are stored here. This repo contains only the signed output.

## Update cycle

A new `license.json` is generated each quarter and pushed to `main`.
Clients automatically pick up the renewed token on their next launch — no installer needed.

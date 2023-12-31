# KV Shop
This repository contains the code for the KV Shop, a simple micoservice-based webshop.

## Architecture

KV Shop contains the following services:

| Service | Language | Version |
| --- | --- | --- |
| Frontend | Java | 17 (Eclipse Temurin) |
| Inventory | Java | 11 (Eclipse Temurin) |
| Pricing | Java | 8 (Eclipse Temurin) |
| Membership | Go | 1.21 |
| Coupon | JavaScript | NodeJS 18.3.0 |

## Running locally

To build the project and run it locally on a Kind cluster, run the following command:

```bash
make build-images load-to-kind deploy
```
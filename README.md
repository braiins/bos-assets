# BOS Assets Repository

This repository contains proprietary binary blobs and web assets required for **Braiins OS (BOS)**, an open-source Linux distribution based on **OpenWrt** for mining devices. These assets are distributed separately from the main BOS source code due to licensing constraints.

## Repository Structure

```
.
├── bin
│   ├── boser       # BOS Service binary
│   ├── bosminer    # BOSminer binary (mining)
│   └── bos-tools   # BOS BusyBox-like utility
└── www
    ├── boser       # BOS web UI assets
    └── var         # Variable web assets
```

## Usage

These assets are intended to be used alongside the **BOS source code**. To integrate them, ensure they are placed in the appropriate locations within the BOS filesystem.

## Licensing

While the **BOS source code** is open-source, the binaries in this repository remain **proprietary** and are distributed under a separate license. Please refer to individual component licenses for more details.

## Contact

For questions or support, please visit [**Braiins website**](https://braiins.com) or reach out via our **community channels**.

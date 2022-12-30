# Installation fail repro

This is a totally blank repo on Ubuntu 22.04.1 LTS, node 18.12.1, npm 9.1.3.

To reproduce:

```bash
npm init
npm install @vanilla-extract/next-plugin # Fails
```

## npm error log

See this [logfile](./2022-12-30T12_49_22_369Z-debug-0.log).

## System

```
OS: Linux 5.15 Ubuntu 22.04.1 LTS 22.04.1 LTS (Jammy Jellyfish)
CPU: (12) x64 AMD Ryzen 5 2600X Six-Core Processor
Memory: 4.77 GB / 15.55 GB
Container: Yes
Shell: 5.1.16 - /bin/bash
```

# Quents Containers

A lightweight containerization platform and Docker alternative built for Linux environments.

## Features

* Rootless containers
* Linux chroot support
* Multiple Linux distributions
* Resource isolation
* Custom networking
* Portable environments
* VPS deployment ready
* Lightweight runtime
* Simple CLI interface

## Supported Distributions

* Ubuntu
* Debian
* Kali Linux
* Alpine Linux
* Arch Linux
* Fedora
* Rocky Linux

## Installation

```bash
curl -fsSL https://quents.dev/install.sh | bash
```

## Create Container

```bash
quents create ubuntu
```

## Start Container

```bash
quents start ubuntu
```

## Enter Container

```bash
quents shell ubuntu
```

## List Containers

```bash
quents list
```

## Stop Container

```bash
quents stop ubuntu
```

## Remove Container

```bash
quents remove ubuntu
```

## Architecture

Quents uses Linux namespaces, chroot environments, and lightweight process isolation to provide a container experience without requiring a full Docker stack.

## Use Cases

* Development environments
* Security testing labs
* VPS hosting
* Linux training
* CI/CD environments
* Portable applications

## Website

https://quents.dev

## License

MIT License

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

Quents is designed to support virtually all Linux environments, architectures, and device classes through a universal runtime layer.

### Officially Supported

* Ubuntu
* Debian
* Kali Linux
* Alpine Linux
* Arch Linux
* Fedora
* Rocky Linux
* CentOS
* Oracle Linux
* openSUSE
* Gentoo
* Void Linux
* Linux Mint
* Manjaro
* Pop!_OS
* Elementary OS
* Zorin OS
* MX Linux
* Deepin
* NixOS
* Termux on android
* @all Linux devices support, all architectures support

### Architectures

* x86
* x86_64 (AMD64)
* ARM
* ARM64 (AArch64)
* RISC-V
* PowerPC
* IBM Z
* LoongArch

### Device Support

* Physical Servers
* Virtual Private Servers (VPS)
* Dedicated Servers
* Cloud Instances
* Desktop Systems
* Laptops
* Embedded Systems
* IoT Devices
* Single Board Computers
* Workstations
* Development Environments
* Enterprise Infrastructure

### Universal Compatibility

Quents aims to provide a universal Linux environment capable of running across nearly any Linux distribution, architecture, virtualization platform, cloud provider, container host, edge device, or custom infrastructure deployment.

### Deployment Targets

* Bare Metal
* KVM
* QEMU
* Xen
* Hyper-V
* VMware
* Proxmox VE
* OpenStack
* Private Cloud
* Public Cloud
* Hybrid Cloud
* Edge Infrastructure

> Build once. Run anywhere Linux runs.


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

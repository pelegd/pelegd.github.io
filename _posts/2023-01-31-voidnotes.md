---
title: Void Linux - my current used distro
date: 2023-01-31 08:00
categories: [Linux,Void]
tags: [linux,distro] #should always be lower case
---

# The Void (Linux) distribution

Void is a general purpose operating system, based on the monolithic Linux kernel. Its package system allows you to quickly install, update and remove software; software is provided in binary packages or can be built directly from sources with the help of the XBPS source packages collection.

It is available for a variety of platforms. Software packages can be built natively or cross compiled through the [XBPS source packages collection](https://github.com/void-linux/void-packages).

## Not a fork!
Void Linux is an independent distribution, developed entirely by volunteers.
Unlike trillions of other existing distros, Void is not a modification of an existing distribution. Void's package manager and build system have been written from scratch.

## Stable rolling release
Void focuses on stability, rather than on being bleeding-edge. Install once, update routinely and safely.
Thanks to our continuous build system, new software is built into binary packages as soon as the changes are pushed to the void-packages repository.

## runit
We use runit as the init system and service supervisor.
runit is a simple and effective approach to initialize the system with reliable service supervision. Refer to the [Void Handbook](https://docs.voidlinux.org/config/services/index.html) for an introduction.

## C library diversity
Void Linux supports both the musl and GNU libc implementations, patching incompatible software when necessary and working with upstream developers to improve the correctness and portability of their projects.

## XBPS
[xbps](https://github.com/void-linux/xbps) is the native system package manager, written from scratch with a 2-clause BSD license.

XBPS allows you to quickly install/update/remove software in your system and features detection of incompatible shared libraries and dependencies while updating or removing packages (among others). Refer to the [Handbook for an overview](https://docs.voidlinux.org/xbps/index.html).

## xbps-src
[xbps-src](https://github.com/void-linux/void-packages) is the xbps package builder, written from scratch with a 2-clause BSD license.
This builds the software in containers through the use of Linux namespaces, providing isolation of processes and bind mounts (among others). No root required!
Additionally, xbps-src can build natively or cross compile for the target machine, and supports multiple C libraries (glibc and musl currently).

### [Downloads](https://voidlinux.org/download/)
### [Packeges](https://voidlinux.org/packages/)
### [Documentations](https://docs.voidlinux.org/)
### [Manual Pages](https://man.voidlinux.org/)

## My Notes for installing void-linux



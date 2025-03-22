# Linux

- Linux is the kernel that powers a Linux Operating System.
- Kernels are programs that talk directly to the hardware and manage resources and processes.
- Kernels need a whole operating system to be useful.
- When a Linux kernel is bundled with operating system and shipped together, that is called as Linux Distribution.

## Linux Distributions

- Red Hat Family
- Debian Family
- Source Code Distributions
- System V init vs SystemD


### Red Hat Family
The Red Hat family consists of enterprise-grade Linux distributions known for stability, security, and commercial support. Key distributions include:

- **Red Hat Enterprise Linux (RHEL):** Commercial distribution with long-term support, widely used in enterprises.
- **CentOS Stream:** Rolling-release upstream version of RHEL, meant for testing upcoming features.
- **Fedora:** Cutting-edge distribution, used as a testing ground for RHEL.
- **AlmaLinux & Rocky Linux:** Community-driven RHEL-compatible alternatives after CentOS shifted to Stream.

### Debian Family
Debian-based distributions prioritize stability and free software principles. Key distributions include:

- **Debian:** One of the oldest Linux distributions, known for its robustness and package management (APT).
- **Ubuntu:** User-friendly derivative of Debian, widely used on desktops and servers.
- **Kali Linux:** Security-focused distribution based on Debian, used for penetration testing.
- **Raspberry Pi OS:** Optimized for Raspberry Pi hardware, based on Debian.

### Source Code Distributions
These distributions require users to compile software from source, offering customization and performance benefits.

- **Gentoo:** Uses the Portage package manager, allowing fine-grained optimization and customization.
- **Arch Linux:** Minimalistic and user-centric distribution with a rolling release model and Pacman package manager.
- **Linux From Scratch (LFS):** A project that provides step-by-step instructions to build a Linux system from the ground up.

### System V Init vs SystemD
#### System V Init
- Traditional initialization system based on shell scripts.
- Uses runlevels (0-6) to define system states.
- Slower boot process due to sequential execution.
- Example distributions: Older Debian, RHEL 6, Slackware.

#### SystemD
- Modern init system designed for parallel execution and improved service management.
- Uses unit files instead of scripts.
- Supports on-demand service activation and better logging (journald).
- Example distributions: RHEL 7+, Ubuntu 16.04+, Debian 8+.

SystemD is now the default init system for most major Linux distributions, replacing System V Init for efficiency and ease of use.


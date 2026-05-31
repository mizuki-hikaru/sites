---
description: Small shell scripts for managing Ubuntu/KVM/libvirt virtual machines.
---

# Scripts

Small shell scripts for managing Ubuntu/KVM/libvirt virtual machines.

 - create-vm: Create a virtual machine and set up iptables networking.
 - delete-vm: Delete a virtual machine created with create-vm.
 - auto-updates: Enable automatic security updates for Ubuntu.

create-vm and delete-vm will prompt for settings (e.g. RAM, CPUs, etc)

## Quick start

    curl -s https://hikaru.org/projects/scripts/create-vm | bash
    curl -s https://hikaru.org/projects/scripts/delete-vm | bash
    curl -s https://hikaru.org/projects/scripts/auto-updates | bash

## Safety

Read scripts before running remote shell commands. These scripts assume Ubuntu, KVM/libvirt, and systemd.

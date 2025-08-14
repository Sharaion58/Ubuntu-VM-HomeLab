# Ubuntu-VM-HomeLab
Documenting my VMware Ubuntu Linux Server setup, configurations, and IT practice projects.

# VMware Ubuntu Linux Server Home Lab

This repo documents setup of a **VMware Ubuntu Linux server** lab—perfect for building IT job experience.

## Overview

Guide to install Ubuntu Server on VMware Workstation Pro with essential tools:
- SSH access
- VMware Tools integration (`open-vm-tools`)
- Optional Docker setup
- Snapshot workflow

## Steps

1. Create VM in VMware Workstation.
2. Configure memory, disk, and bridged networking.
3. Install Ubuntu Server via installer.
4. Update system with `apt update && apt upgrade`.
5. Install `open-vm-tools` for host integration.
6. Ensure SSH is installed and functional.
7. (Optional) Install Docker.
8. Take a snapshot.

## Screenshots

Add screenshots at key steps:
- ISO download and VM config
- During Ubuntu install
- After updates
- Docker test output

## Goals for IT Practice

- Server provisioning
- Remote access via SSH
- Virtual tools integration
- Container management basics
- Snapshot and rollback workflow

## How to Use

1. Clone this repo and review steps.
2. Replicate each step in your environment.
3. Add your own screenshots in a `/screenshots` folder.
4. Use snapshot to reset lab and try different configurations.

Configure memory, disk, and bridged networking.
<img width="747" height="723" alt="config VM" src="https://github.com/user-attachments/assets/ed1950d8-f3b2-4cc7-9c0d-901e9059df0c" />

During Ubuntu install
<img width="1278" height="798" alt="Screenshot 2025-07-02 124341" src="https://github.com/user-attachments/assets/e6962305-51ea-45f0-9b29-50039c052a45" />

After updates
<img width="1347" height="839" alt="sudo apt upgrade -y" src="https://github.com/user-attachments/assets/0a4b50cc-4655-43a4-9719-a08dbc0ae828" />

Docker test output
<img width="1308" height="381" alt="systemctl status docker" src="https://github.com/user-attachments/assets/4d60314e-9a3a-40f7-9cb0-1fd45e5a5ad6" />

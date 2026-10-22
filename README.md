# AWS Linux Administration Labs

## Overview

This repository documents my hands-on learning journey in AWS cloud computing and Linux system administration. The labs use an Amazon EC2 instance running Amazon Linux 2023.

## Technologies and Tools

- **Cloud platform:** Amazon Web Services (AWS)
- **Compute:** Amazon EC2
- **Operating system:** Amazon Linux 2023
- **Remote access:** SSH and PuTTY
- **Package management:** DNF
- **Service management:** systemd and systemctl
- **Web server:** Nginx
- **File permissions:** chmod and chown

## Labs Completed

### 1. EC2 and Linux Fundamentals

- Launched an Amazon EC2 instance.
- Connected to the instance using SSH through PuTTY.
- Inspected operating system information, disk space, and uptime.

### 2. Linux User Administration

- Created a Linux user using `useradd`.
- Inspected user IDs and group membership with `id`.
- Examined home directory ownership and permissions.

### 3. File Permissions and Ownership

- Created files and directories.
- Changed file permissions using `chmod`.
- Changed file ownership using `chown`.
- Verified permissions and ownership using `ls -l`.

### 4. Package and Service Management

- Checked for available package updates with `dnf`.
- Installed Nginx.
- Started and enabled services using `systemctl`.
- Checked service status.

### 5. Nginx Web Server

- Prepared a custom HTML page for Nginx.
- Practised testing the local web server using `curl`.
- Explored EC2 security group configuration for HTTP access.

## Planned Labs

- Publish and verify a website hosted on EC2.
- Amazon S3 bucket and object management.
- AWS IAM users, roles, and policies.
- Linux troubleshooting and service management.
- Cloud security and least-privilege access.

## Key Learning Outcomes

This project helps me build practical skills in Linux administration, cloud infrastructure, service management, file permissions, and troubleshooting.

## Security Practices

- Never commit SSH private keys, passwords, access tokens, or AWS credentials.
- Restrict SSH access to trusted IP addresses.
- Apply least-privilege permissions.
- Keep S3 buckets private unless public access is explicitly required.

## Author

**Godfrey Makwale Madiba**

GitHub: [Godfrey-CodeKiller](https://github.com/Godfrey-CodeKiller)


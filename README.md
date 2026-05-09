# Secure Linux Server on AWS EC2

Hardened Ubuntu server deployed on AWS EC2 with automated Linux security configuration using Bash scripting.

## Features

- SSH key authentication only
- Root login disabled
- Non-root sudo user configured
- UFW firewall enabled
- fail2ban brute-force protection
- Automatic security updates enabled

## Stack

- AWS EC2
- Ubuntu Server
- Bash
- UFW
- fail2ban

## Architecture

```text
Internet
   ↓
AWS Security Group
   ↓
Ubuntu EC2
 ├── SSH Hardening
 ├── UFW Firewall
 ├── fail2ban
 └── Automatic Security Updates
```

## Automation

Server hardening automated with:

```bash
scripts/secure_server.sh
```

Run:

```bash
chmod +x secure_server.sh
./secure_server.sh
```

## Screenshots

### UFW Status

![UFW](screenshots/ufw-status.png)

### fail2ban Status

![fail2ban](screenshots/fail2ban-status.png)

## Future Improvements

- Terraform provisioning
- Ansible automation
- Monitoring integration
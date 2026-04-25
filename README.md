# Secure Linux Server

Built on AWS EC2. The goal was to take a fresh Ubuntu server and make sure it isn't an open door for anyone on the internet.

## What's in here
- SSH locked down to key auth only
- UFW firewall configured, with minimal open ports 
- fail2ban watching for brute force attempts
- Root access disabled, sudo user set up properly
- Automatic security updates enabled

## Motivation
Every project in this portfolio runs on infrastructure.
This is the infrastructure — built and secured from scratch.

## Stack
AWS EC2 · Ubuntu · UFW · fail2ban · Bash
## Status
In progress
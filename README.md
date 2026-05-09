# Secure Linux Server

Its built on AWS EC2. The goal is to take a new Ubuntu server and make sure its secured on the internet.

## Features
- SSH locked down to key auth only
- UFW firewall configured, with minimal open ports 
- fail2ban watching for brute force attempts
- Root access disabled, sudo user set up properly
- Automatic security updates enabled

## Motivation
Every project in this portfolio runs on infrastructure.
This is the infrastructure built and secured from scratch,its the baseline of upcoming projects

## Stack
AWS EC2 · Ubuntu · UFW · fail2ban · Bash
## Status
In progress
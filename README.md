# Linux SRE Lab — Production-Like Application Server

## Project Overview

Build, operate, secure, automate, and troubleshoot a Linux application server running on AWS Lightsail.

This project simulates the responsibilities of a Linux Administrator and Site Reliability Engineer supporting a production application.

## What We're Building

A Python FastAPI application deployed on Ubuntu Server, using:

- **AWS Lightsail:** Linux server hosting
- **Ubuntu:** Operating system administration
- **Nginx:** Reverse proxy
- **FastAPI:** Backend application
- **systemd:** Application service management
- **journald:** System and application logging
- **Bash and Python:** Operational automation
- **SSH and Linux security:** Secure administration

## Architecture

Client → Nginx (Port 80) → FastAPI (Port 8000)

The application runs as a systemd service on Ubuntu.

## Project Objectives

1. Provision and configure an Ubuntu server.
2. Deploy and manage the FastAPI application.
3. Configure Nginx as a reverse proxy.
4. Manage users, permissions, packages, and services.
5. Troubleshoot networking, storage, and performance problems.
6. Simulate incidents and document root causes.
7. Automate health checks and maintenance.
8. Implement security hardening and recovery procedures.
9. Automate provisioning and teardown to control costs.

## Learning Approach

Each lab follows:

**Build → Break → Investigate → Fix → Verify → Document**

Every exercise includes commands, troubleshooting evidence, and lessons learned.

## Project Status

Planning complete. Implementation not yet started.

## Cost Management

Lightsail resources will be created for lab sessions and deleted afterward. Scripts, configuration files, and documentation will be preserved in GitHub.

## Deliverables

- Working Linux application server
- Nginx and systemd configurations
- Bash and Python automation scripts
- Incident reports and troubleshooting runbooks
- Infrastructure provisioning and recovery automation
- Interview-ready technical explanations
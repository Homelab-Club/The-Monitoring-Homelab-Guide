# 📖The-Homelab-Monitoring-Guide

<img width="352" height="562" alt="The Homelab Monitoring Guide_Black" src="https://github.com/user-attachments/assets/1bfadf22-dea8-4c11-9c40-897622dc00ce" />

# The Homelab Monitoring Guide

**By Kevin Villarreal | Homelab Club**

Welcome to the official GitHub repository for *The Homelab Monitoring Guide*, the fifth book in the Homelab Club book series.

This repository contains the configuration files, Docker Compose definitions, Prometheus configuration, alert rules, and practical examples that accompany the book. These resources help you follow the hands-on exercises without having to type lengthy configuration files from the printed or digital edition.

## About the Book

*The Homelab Monitoring Guide* helps you build a monitoring solution for your homelab using Prometheus, Grafana, and Alertmanager.

You will learn how to prepare a monitoring server, collect metrics from Proxmox VE, Linux servers, and Windows Server, visualize performance data with Grafana, and configure alerts to notify you when something needs attention.

The examples are designed for a learning environment using Proxmox VE, Ubuntu Server, Docker Compose, and Windows Server. You can adapt them to your own infrastructure.

## Repository Contents

Files are organized by chapter to make it easy to find the resources associated with each exercise.

- **Monitoring server setup**: Docker Compose configuration and supporting files for the monitoring stack.
- **Prometheus**: Configuration files and scrape jobs for monitoring targets.
- **Linux monitoring**: Node Exporter configuration and related examples.
- **Windows monitoring**: Windows Exporter configuration and related examples.
- **Proxmox VE monitoring**: Prometheus configuration and exporter resources for Proxmox VE.
- **Grafana**: Dashboard examples and supporting configuration.
- **Alerting**: Prometheus alert rules and Alertmanager configuration examples.

Additional files may be added as the book develops.

## How to Use This Repository

1. Browse the folders to find the chapter or exercise you are following.
2. Open a file to view its contents directly on GitHub.
3. Use the **Raw** button to view the plain-text version of a file.
4. Copy the contents or download the file to your monitoring server.
5. Review the configuration and customize it for your environment before running it.

You can also download the repository as a ZIP file using **Code → Download ZIP** on the repository's main page.

## Important: Customize Before Use

The examples are provided for educational purposes. Your IP addresses, hostnames, usernames, network settings, and other configuration values may differ from those used in the book.

Review each file before executing it. Never commit passwords, API tokens, private keys, or other sensitive information to a public repository.

Some commands require administrative privileges and can modify system configuration. Understand what a command does before running it.

## Requirements

Depending on the chapter, you may need:

- Proxmox VE or another supported virtualization platform
- Ubuntu Server for the monitoring VM
- Windows Server for the Windows monitoring exercises
- Docker Engine and Docker Compose
- Basic Linux command-line and networking knowledge
- Prometheus exporters for the systems you want to monitor
- A working network with DNS and Internet connectivity

Check the relevant chapter for specific requirements and configuration details.

## About Homelab Club

Homelab Club helps IT enthusiasts, self-hosters, and aspiring IT professionals learn through practical homelab projects.

Explore more book resources and apparel at [homelab-club.com](https://homelab-club.com/).

## Feedback and Contributions

Found an issue, outdated command, or improvement? Please open a GitHub issue describing the problem and the chapter or file concerned.

Thank you for learning with Homelab Club. Happy monitoring!

**Kevin Villarreal**  
Author, *The HOMELAB Monitoring Guide*  
Homelab Club


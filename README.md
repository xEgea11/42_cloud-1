# Cloud-1 — Automated Deployment of Inception

Automated deployment of an Inception-based web application on a cloud server.

## Project Purpose

This repository contains the work for the 42 **Cloud-1** project.

The objective is to automate the deployment of a containerized WordPress environment on cloud infrastructure, using infrastructure provisioning, configuration management, containerization, and automated deployment practices.

## Team

- **Ruben Egea**
- **Davyd Bredykhin**

## Project Workflow

We use a feature-branch and Pull Request workflow:

```text

Issue
  ↓
Feature / Bugfix branch
  ↓
Pull Request
  ↓
develop
  ↓
Promotion Pull Request
  ↓
main

```

## Documentation / Governance

Detailed branching, review, and PR/merge rules
Governance, contribution rules and development workflows 

are documented in

[CONTRIBUTING.md](CONTRIBUTING.md)

## Milestones

A list of the defined Milestones:

| Milestone | Objective |
|---|---|
| M0 — Planning & Architecture | Define requirements and project architecture 
| M1 — Azure Infrastructure | Prepare the cloud environment
| M2 — Ansible Automation | Automate provisioning and deployment
| M3 — Docker Architecture | Define the containerized application
| M4 — Application Stack | Deploy WordPress, database and phpMyAdmin
| M5 — Security & Networking | Secure and configure external/internal access
| M6 — Persistence & Recovery | Ensure data persistence and automatic recovery
| M7 — Automation Validation | Validate idempotency, portability and multi-server deployment
| M8 — TLS & Routing | Configure HTTPS and application routing
| M9 — Final Validation & Defense | Validate all mandatory requirements

## Project Board

The current work and project roadmap are tracked through the GitHub Project:

[Cloud-1 Project Board](https://github.com/users/xEgea11/projects/1)


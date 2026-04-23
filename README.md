# Windows Server Enterprise Lab

This repository documents a Windows Server 2025 enterprise lab designed to simulate the implementation of a small business infrastructure with centralized identity, file access control, backup operations, and remote administration.

The project was developed as a structured technical lab with an emphasis on business-oriented documentation, validation, and operational coherence.

## Project Focus

This lab covers the following areas:

- Windows Server 2025 initial preparation
- static IPv4 configuration
- Active Directory Domain Services (AD DS)
- DNS integration
- domain controller promotion
- organizational units, security groups, and domain users
- shared folders and NTFS permission design
- mapped network drives
- scheduled and manual backup operations
- restore validation
- command-line backup with `wbadmin`
- Windows 11 domain join
- controlled Remote Desktop access

## Objectives

The main objective of this lab was to design and validate a coherent Windows Server environment that reflects the core needs of a small organization:

- centralized authentication
- structured identity management
- controlled access to shared resources
- backup and recovery readiness
- secure remote administration
- professional technical documentation

## Technical Scope

### Core Services
- Active Directory Domain Services
- DNS
- domain controller configuration

### Identity and Access
- OU structure by department
- security groups
- domain users
- group membership logic

### File Services
- shared folders
- NTFS permissions
- persistent mapped drives

### Backup and Recovery
- Windows Server Backup
- scheduled backups
- manual backup execution
- restore validation
- `wbadmin` usage

### Client Integration
- Windows 11 client join to domain
- domain authentication testing

### Remote Administration
- Remote Desktop configuration
- permission control through policy and group membership

## What This Repository Shows

This repository is intended to demonstrate:

- practical knowledge of Windows Server administration
- understanding of domain-based identity management
- awareness of access control and backup strategy
- ability to validate configuration outcomes
- capability to document technical work in a structured and professional way

## Repository Structure

```text
windows-server-enterprise-lab/
├── README.md
├── docs/
│   ├── trabalho-final/
│   ├── tarefas-base/
│   └── evidencias/
├── images/
│   ├── capa/
│   ├── arquitetura/
│   ├── active-directory/
│   ├── backups/
│   ├── partilhas/
│   └── rdp/
└── notes/
    ├── overview.md
    ├── lessons-learned.md
    └── technical-scope.md

## Documentation Note

Some original lab documents contain contextual and identifying details that are being reviewed before publication. For that reason, this repository is being built in stages, starting with a structured public overview of the project scope and technical focus.

## Status

In progress — repository structure and public-facing documentation are being prepared.

---
layout: default
title: Personal VPS Backup Privacy Policy
---

# Privacy policy

Effective date: 2026-11-16.

Personal VPS Backup is a tool for one account owner's private server. Its Google Drive integration stores and restores the owner's encrypted server configuration backups.

## Google data access and use

The app requests only `https://www.googleapis.com/auth/drive.file`. It uses that permission to create backup folders, upload encrypted archives and integrity manifests, read them back for verification or recovery, and remove its own expired backups according to the retention settings. It does not request access to the owner's entire Drive, Gmail, contacts, or calendar.

## Backup contents and encryption

Backups contain proxy and system service configuration, firewall rules, deployment and recovery scripts, public SSH keys, software versions, and necessary operational settings. They may contain proxy access credentials or the app's Drive authorization token. Archives are encrypted with age before they leave the VPS. SSH private keys are excluded. The recovery private key remains with the owner and is not uploaded to Drive.

The tool does not collect website browsing lists, searches, or AI conversation content. Operational records are limited to service state, aggregate traffic, costs, security events, backup integrity, and failures.

## Storage, sharing, and retention

Encrypted files are stored in the owner's Google Drive. The app does not make those backups public or provide them to advertisers or other users, and does not use Google user data for advertising or model training. Google Cloud and Google Drive process data as the infrastructure providers used by the owner.

The configured retention is seven daily, four weekly, and three monthly backups. The tool removes only the backup files it manages when they exceed that retention. Local encrypted backups remain available if a Drive upload fails.

## Owner control

The owner may revoke this app's access in Google Account security settings and may delete its backup files in Google Drive. Revocation stops subsequent Drive uploads and access; it does not delete local encrypted backups or stop the core VPS service.

Use and transfer of information received from Google APIs is limited to the backup, verification, recovery, and retention functions described here, including the applicable Limited Use requirements in the Google API Services User Data Policy.

[Application home](index.html)

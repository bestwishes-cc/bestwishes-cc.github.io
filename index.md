---
layout: default
title: Personal VPS Backup
---

# Personal VPS Backup

This tool backs up one account owner's private VPS configuration to that owner's Google Drive. It is for personal use and does not provide a public proxy service.

Configuration archives are encrypted on the VPS before upload. The recovery private key stays with the account owner. The tool requests only the Google Drive `drive.file` scope, which limits access to files created or explicitly opened with this app.

The tool does not collect browsing history, searches, or AI conversations. It retains configuration backups and limited operational records needed to restore the owner's server.

[Privacy policy](privacy.html)

To stop Drive access, the owner can revoke this app in their Google Account security settings. The VPS can continue operating independently of Drive.

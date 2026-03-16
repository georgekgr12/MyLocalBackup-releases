# MyLocalBackup - Releases

Official release downloads for **MyLocalBackup** — a free, open-source versioned local backup tool for Windows.

## Download Latest

[![Download MSI](https://img.shields.io/badge/Download-MyLocalBackup_Setup.msi-blue?style=for-the-badge&logo=windows)](https://github.com/georgekgr12/MyLocalBackup-releases/releases/latest/download/MyLocalBackupSetup.msi)

> **Direct link:** https://github.com/georgekgr12/MyLocalBackup-releases/releases/latest/download/MyLocalBackupSetup.msi

## Features

- **NTFS Hard Link Deduplication** — Unchanged files are hard-linked across snapshots, saving disk space
- **Live Streaming Backup Engine** — Real-time file backup with smooth progress tracking
- **Dark Mode** — Sleek dark-mode-only theme
- **Automated Scheduling** — Configurable backup intervals (1-168 hours) or daily fixed-time, with catch-up logic
- **One-Click Updates** — Automatic update checking with SHA256 integrity verification
- **System Tray Integration** — Context-aware tray menu with pause/resume/cancel controls
- **Retention Policies** — Automatic thinning: keeps all from last 24h, one per day for 30 days, one per week after that
- **Storage Pressure Protection** — Auto-deletes oldest backups when disk space runs low

## System Requirements

- Windows 10/11 (64-bit)
- NTFS file system (required for hard link deduplication)
- .NET 9 Runtime (bundled in installer)

## Source Code

The source code is available at [georgekgr12/MyLocalBackup](https://github.com/georgekgr12/MyLocalBackup).

---
© 2026 Developed by George Karagioules.

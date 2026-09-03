# Awesome Rclone with stars

> A curated list of tools, GUIs, integrations, libraries, and resources for [rclone](https://rclone.org/#docs) - the "Swiss army knife of cloud storage".

[Rclone](https://github.com/rclone/rclone?tab=readme-ov-file#rclone) ⭐ 59,524 | 🐛 1,251 | 🌐 Go | 📅 2026-09-03 is a command-line program to sync files and directories to and from dozens of cloud storage providers. This list collects the ecosystem of projects built around rclone.

## Contents

* [Official Resources](#official-resources)
* [Clients & GUIs](#clients--guis)
  * [Desktop](#desktop)
  * [Web](#web)
  * [Mobile](#mobile)
* [Sync and Backup Tools](#sync-and-backup-tools)
  * [Two-Way Sync](#two-way-sync)
  * [Backup Utilities](#backup-utilities)
  * [Backup Software with Rclone Support](#backup-software-with-rclone-support)
* [API Libraries and SDKs](#api-libraries-and-sdks)
  * [JavaScript / TypeScript](#javascript--typescript)
  * [Python](#python)
  * [PHP](#php)
  * [Rust](#rust)
  * [Go](#go)
* [Automation and Scripts](#automation-and-scripts)
* [Cloud and System Integrations](#cloud-and-system-integrations)
  * [Kubernetes](#kubernetes)
  * [Home Automation](#home-automation)
  * [CI/CD](#cicd)
  * [NFS](#nfs)
* [Docker Images](#docker-images)
* [Forks and Alternate Builds](#forks-and-alternate-builds)
* [Utilities and Miscellaneous](#utilities-and-miscellaneous)

***

## Official Resources

* [Rclone](https://github.com/rclone/rclone) ⭐ 59,524 | 🐛 1,251 | 🌐 Go | 📅 2026-09-03 - The core command-line tool for syncing files to 70+ cloud storage providers. Created by @ncw and loved by everyone. ![GitHub stars](https://img.shields.io/github/stars/rclone/rclone)
* [Docs](https://rclone.org) - The official **`rclone`** docs.
* [Forum](https://forum.rclone.org) - The official **`rclone`** forum.

## Clients & GUIs

### Desktop

* [Rclone Browser](https://github.com/kapitainsky/RcloneBrowser) ⭐ 2,950 | 🐛 138 | 🌐 C++ | 📅 2024-03-11 - Cross-platform Qt GUI for browsing, transferring, mounting, and streaming files. Fork of original by mmozeiko. **`Inactive since 2020`** ![GitHub stars](https://img.shields.io/github/stars/kapitainsky/RcloneBrowser)
* [Rclone UI](https://github.com/rclone-ui/rclone-ui) ⭐ 2,223 | 🐛 11 | 🌐 TypeScript | 📅 2026-08-31 - Modern, battle-tested, cross-platform desktop GUI built with Rust. Most recommended & actively maintained solution for both newbies and veterans. ![GitHub stars](https://img.shields.io/github/stars/rclone-ui/rclone-ui)
* [Rclone Manager](https://github.com/Zarestia-Dev/rclone-manager) ⭐ 1,077 | 🐛 19 | 🌐 TypeScript | 📅 2026-09-03 - Hobby cross-platform GUI built with Angular. ![GitHub stars](https://img.shields.io/github/stars/Zarestia-Dev/rclone-manager)
* [REM](https://github.com/liriliri/rem) ⭐ 618 | 🐛 13 | 🌐 TypeScript | 📅 2025-12-22 - Kawaii rclone client. Can be seen as an open source version of RcloneView. ![GitHub stars](https://img.shields.io/github/stars/liriliri/rem)
* [RcloneTray](https://github.com/dimitrov-adrian/RcloneTray) ⭐ 288 | 🐛 17 | 🌐 JavaScript | 📅 2024-05-11 - Minimal Electron-based system tray application for mounting and managing remotes. **`Inactive since 2018`** ![GitHub stars](https://img.shields.io/github/stars/dimitrov-adrian/RcloneTray)
* [RcloneNg](https://github.com/ElonH/RcloneNg) ⭐ 195 | 🐛 27 | 🌐 TypeScript | 📅 2023-01-06 - Angular-based web app GUI with two-pane file manager interface. Packaged for OpenWrt. **`Inactive since 2021`** ![GitHub stars](https://img.shields.io/github/stars/ElonH/RcloneNg)
* [Rclone Shuttle](https://github.com/pieterdd/RcloneShuttle) ⭐ 156 | 🐛 3 | 🌐 Rust | 📅 2026-06-27 - GTK4-based graphical uploader for rclone. Simple drag-and-drop file transfers written in Rust. ![GitHub stars](https://img.shields.io/github/stars/pieterdd/RcloneShuttle)
* [Rclone Navigator](https://github.com/Communist02/RcloneNavigator) ⭐ 8 | 🐛 4 | 🌐 Python | 📅 2026-05-27 - Desktop GUI for managing files in cloud storage. Supports Linux and Windows with features for browsing, uploading, downloading, mounting, and serving remotes. ![GitHub stars](https://img.shields.io/github/stars/Communist02/RcloneNavigator)
* [RcloneView](https://rcloneview.com/) - Commercial GUI for Windows/macOS with folder comparison and multi-window remote control. Flutter based and developed in Korea.
* [S3Drive](https://s3drive.app/) - Commercial GUI that includes a proprietary cloud storage offering. Supports encryption.

### Web

* [WebUI React](https://github.com/rclone/rclone-webui-react) ⚠️ Archived - Official web-based GUI bundled with rclone (`rclone rcd --rc-web-gui`). ![GitHub stars](https://img.shields.io/github/stars/rclone/rclone-webui-react)
* [Motuz](https://github.com/FredHutch/motuz) ⭐ 115 | 🐛 112 | 🌐 JavaScript | 📅 2026-01-13 - Web interface designed for large-scale, multi-user data transfers (e.g., scientists moving TBs of data). Provides web UI and REST API on top of rclone. ![GitHub stars](https://img.shields.io/github/stars/FredHutch/motuz)
* [MultCloud](https://www.multcloud.com/) - Commercial web-based cloud management platform. Transfer, sync, and backup files between 30+ cloud services. Supports cloud-to-cloud transfers without downloading. Available on Android and iOS.

### Mobile

* [Round Sync](https://github.com/newhinton/Round-Sync) ⭐ 2,342 | 🐛 193 | 🌐 Java | 📅 2025-11-16 - Fork of RCX with Material 3 Design, task management, and enhanced features. Available on [F-Droid](https://f-droid.org/packages/de.felixnuesse.extract/) and [IzzyOnDroid](https://apt.izzysoft.de/fdroid/index/apk/de.felixnuesse.extract). [Website](https://roundsync.com/) ![GitHub stars](https://img.shields.io/github/stars/newhinton/Round-Sync)
* [RCX (Rclone for Android)](https://github.com/x0b/rcx) ⭐ 2,039 | 🐛 144 | 🌐 Java | 📅 2023-11-26 - Full-featured Android file manager powered by rclone. Browse, upload, download, stream, and manage files on cloud remotes. Available on [F-Droid](https://f-droid.org/en/packages/io.github.x0b.rcx/) and Google Play. ![GitHub stars](https://img.shields.io/github/stars/x0b/rcx)
* [Rclone Explorer](https://github.com/patrykcoding/rcloneExplorer) ⭐ 360 | 🐛 49 | 🌐 Java | 📅 2020-05-03 - Original Android GUI for rclone. **`Inactive since 2018, superseded by RCX`** ![GitHub stars](https://img.shields.io/github/stars/patrykcoding/rcloneExplorer)
* [Unified Cloud Storage](https://play.google.com/store/apps/details?id=com.codestation.unifiedcloudstorage) - Legacy Android app for managing multiple cloud storage accounts via rclone. **`Inactive since 2017`**

## Sync and Backup Tools

### Two-Way Sync

* [rclonesync V2](https://github.com/cjnaz/rclonesync-V2) ⭐ 363 | 🐛 15 | 🌐 Python | 📅 2022-04-07 - Python script for two-way sync with safety checks and max deletion limits. **`Superseded by rclone's built-in bisync`** ![GitHub stars](https://img.shields.io/github/stars/cjnaz/rclonesync-V2)
* [syncrclone](https://github.com/Jwink3101/syncrclone) ⭐ 170 | 🐛 4 | 🌐 Python | 📅 2023-11-17 - Python-based bi-directional sync tool built specifically for rclone. Supports conflict resolution, move/rename tracking, and backups of changed files. ![GitHub stars](https://img.shields.io/github/stars/Jwink3101/syncrclone)
* [PyFiSync](https://github.com/Jwink3101/PyFiSync) ⭐ 109 | 🐛 1 | 🌐 Python | 📅 2021-10-17 - Python-based 2-way sync utility that can use rclone for transfers. Tracks moves/deletions and backs up on conflict. **`Predecessor to syncrclone`** ![GitHub stars](https://img.shields.io/github/stars/Jwink3101/PyFiSync)
* [rsinc](https://github.com/ConorWilliams/rsinc) ⭐ 56 | 🐛 7 | 🌐 Python | 📅 2020-08-11 - Tiny hackable two-way cloud sync client for Linux. Tracks file moves using hashes and supports parallel transfers. ![GitHub stars](https://img.shields.io/github/stars/ConorWilliams/rsinc)
* [UpBack](https://github.com/DavideRossi/upback) ⭐ 30 | 🐛 8 | 🌐 Python | 📅 2022-01-19 - Two-way sync utility assuming star topology (one cloud remote syncing with multiple clients). ![GitHub stars](https://img.shields.io/github/stars/DavideRossi/upback)

### Backup Utilities

* [rclone\_jobber](https://github.com/wolfv6/rclone_jobber) ⭐ 272 | 🐛 7 | 🌐 Shell | 📅 2020-08-24 - Bash script for backup rotation with logging, archival of old files, retries, and desktop notifications on errors. ![GitHub stars](https://img.shields.io/github/stars/wolfv6/rclone_jobber)
* [PyClone](https://github.com/PyCloneOrg/PyClone) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2025-07-08 - Python automation engine for rclone backup scenarios. Define backup strategy in config file with Telegram notifications. ![GitHub stars](https://img.shields.io/github/stars/PyCloneOrg/PyClone)
* [Rclone BiSync Manager](https://github.com/Gunther-Schulz/rclone-bisync-manager) ⭐ 19 | 🐛 3 | 🌐 Python | 📅 2026-07-27 - GUI + daemon for continuous two-way sync using rclone's bisync. Provides system tray monitor with real-time status. ![GitHub stars](https://img.shields.io/github/stars/Gunther-Schulz/rclone-bisync-manager)
* [dfb (Dated File Backup)](https://github.com/Jwink3101/dfb) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2026-06-21 - Wrapper implementing reverse-incremental backups with rclone. Preserves older versions by appending dates to filenames. ![GitHub stars](https://img.shields.io/github/stars/Jwink3101/dfb)
* [RCloneBackup](https://github.com/polar147/RCloneBackup) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-08-15 - Cross-platform script for reverse incremental backups with Windows VSS support and email reports. ![GitHub stars](https://img.shields.io/github/stars/polar147/RCloneBackup)

### Backup Software with Rclone Support

* [restic](https://github.com/restic/restic) ⭐ 35,838 | 🐛 585 | 🌐 Go | 📅 2026-09-01 - Secure deduplicating backup program. Can use rclone as backend to access many cloud storage services. ![GitHub stars](https://img.shields.io/github/stars/restic/restic)
* [Kopia](https://github.com/kopia/kopia) ⭐ 14,025 | 🐛 877 | 🌐 Go | 📅 2026-09-03 - Open-source backup tool for encrypted, deduplicated backups. Supports rclone as transport for additional cloud providers. ![GitHub stars](https://img.shields.io/github/stars/kopia/kopia)
* [Duplicity Backend](https://github.com/GilGalaad/duplicity-rclone) ⚠️ Archived - Plugin allowing Duplicity backup software to use rclone as a storage backend. **`Archived`** ![GitHub stars](https://img.shields.io/github/stars/GilGalaad/duplicity-rclone)
* [Rcloner](https://github.com/vifreefly/rcloner) ⭐ 9 | 🐛 0 | 🌐 Ruby | 📅 2021-02-24 - Ruby gem wrapping Duplicity and rclone for easy app backups with encryption. ![GitHub stars](https://img.shields.io/github/stars/vifreefly/rcloner)
* [HashBackup](http://www.hashbackup.com/) - Efficient multi-threaded command-line backup for Linux/Unix. Can invoke rclone as transport for unsupported storage systems. **`Commercial`**
* [Doomsday Machine](https://github.com/johnjones4/Doomsday-Machine) - Backup tool using rclone to archive data from various cloud services (IMAP, Drive, etc.) into Docker containers. **`Archived`** ![GitHub stars](https://img.shields.io/github/stars/johnjones4/Doomsday-Machine)

## API Libraries and SDKs

### JavaScript / TypeScript

* [rclone](https://github.com/FWeinb/rclone-js) ⭐ 79 | 🐛 21 | 🌐 JavaScript | 📅 2023-12-21 - JavaScript implementation of rclone cryptography for the browser (filename encryption). ![GitHub stars](https://img.shields.io/github/stars/FWeinb/rclone-js)
* [rclone-sdk](https://github.com/rclone-ui/rclone-sdk?tab=readme-ov-file#-javascript--typescript) ⭐ 69 | 🐛 1 | 🌐 Rust | 📅 2026-08-19 - Typed SDK for browser and Node. Integrates with vanilla fetch, React Query, and SWR. ![GitHub stars](https://img.shields.io/github/stars/rclone-ui/rclone-sdk)
* [rclone-api](https://github.com/rclone/rclone-js-api) ⚠️ Archived - JavaScript client for rclone's RC HTTP API. Promise-based functions for all RC endpoints. **`Inactive, superseded by rclone-sdk`** ![GitHub stars](https://img.shields.io/github/stars/rclone/rclone-js-api)
* [rclone.js](https://github.com/sntran/rclone.js) ⭐ 41 | 🐛 1 | 🌐 JavaScript | 📅 2022-07-04 - Node.js wrapper exposing rclone functions via JavaScript. Downloads rclone binary on install and provides Promise-based API. **`Inactive, superseded by rclone-sdk`** ![GitHub stars](https://img.shields.io/github/stars/sntran/rclone.js)
* [@fyears/rclone-crypt](https://www.npmjs.com/package/@fyears/rclone-crypt) - Rclone's Crypt encryption algorithm implemented in TypeScript. Enables encrypting/decrypting compatible with rclone's crypt remote.

### Python

* [rclone-api (PyPI)](https://pypi.org/project/rclone-api/) - High-level Python API focusing on performance. Auto-downloads rclone binary if not in PATH. Includes HTTP server for ranged file access.
* [PyClone (ltgiv)](https://gitlab.com/ltgiv/pyclone) - Python package wrapping rclone with Pythonic interface. Run operations in threads and get results as Python data structures.
* [python-rclone](https://pypi.org/project/python-rclone/) - Simple Python wrapper for invoking rclone commands.

### PHP

* [Flyclone](https://github.com/verseles/flyclone) ⭐ 10 | 🐛 1 | 🌐 PHP | 📅 2026-07-09 - Object-oriented PHP library wrapping rclone operations. Supports many backends with progress tracking and transfer stats. ![GitHub stars](https://img.shields.io/github/stars/verseles/flyclone)

### Rust

* [rclone-sdk](https://github.com/rclone-ui/rclone-sdk) ⭐ 69 | 🐛 1 | 🌐 Rust | 📅 2026-08-19 - Rust crate providing full client to rclone's RC REST API. Based on the [OpenAPI spec](https://github.com/rclone-ui/rclone-openapi) ⭐ 46 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-19. Used internally by Rclone UI. ![GitHub stars](https://img.shields.io/github/stars/rclone-ui/rclone-sdk)

### Go

* [Librclone](https://rclone.org/rc/#using-librclone) - Official C library interface for rclone. Enables embedding rclone in other programs (C, Python via ctypes, etc.). Part of rclone core.

## Automation and Scripts

* [AutoRclone](https://github.com/xyou365/AutoRclone) ⭐ 1,382 | 🐛 67 | 🌐 Python | 📅 2022-12-11 - Scripts to automate rclone Google Drive operations using multiple service accounts to bypass quotas. ![GitHub stars](https://img.shields.io/github/stars/xyou365/AutoRclone)
* [rclone4pi](https://github.com/pageauc/rclone4pi) ⭐ 102 | 🐛 2 | 🌐 Shell | 📅 2018-06-09 - Easy installer and cron setup for rclone on Raspberry Pi with sample sync scripts. ![GitHub stars](https://img.shields.io/github/stars/pageauc/rclone4pi)
* [rhttpserve](https://github.com/brandur/rhttpserve) ⭐ 39 | 🐛 1 | 🌐 Go | 📅 2017-03-04 - Lightweight HTTP server that serves files from any rclone remote with expiring signed URLs for secure sharing. ![GitHub stars](https://img.shields.io/github/stars/brandur/rhttpserve)

## Cloud and System Integrations

### Kubernetes

* [CSI Driver (Veloxpack)](https://github.com/veloxpack/csi-driver-rclone) ⭐ 347 | 🐛 9 | 🌐 Go | 📅 2026-09-03 - Kubernetes CSI driver built on rclone Go library. Mounts 50+ cloud providers in pods with dynamic PV provisioning and secrets management. ![GitHub stars](https://img.shields.io/github/stars/veloxpack/csi-driver-rclone)
* [CSI Driver (Wunderio)](https://github.com/wunderio/csi-rclone) ⭐ 261 | 🐛 26 | 🌐 Go | 📅 2026-08-18 - Original Kubernetes CSI storage driver using rclone mount. **`Archived`** ![GitHub stars](https://img.shields.io/github/stars/wunderio/csi-rclone)

### Home Automation

* [Home Assistant Rclone Backup](https://github.com/jcwillox/hassio-rclone-backup) ⭐ 201 | 🐛 45 | 🌐 Go | 📅 2026-07-12 - Home Assistant add-on that uses rclone to automatically sync backups to remote cloud storage. ![GitHub stars](https://img.shields.io/github/stars/jcwillox/hassio-rclone-backup)

### CI/CD

* [GitHub Action for rclone](https://github.com/wei/rclone) ⭐ 73 | 🐛 1 | 🌐 Dockerfile | 📅 2019-08-29 - GitHub Action that installs and runs rclone within workflows for syncing artifacts to cloud storage. ![GitHub stars](https://img.shields.io/github/stars/wei/rclone)

### NFS

* [rclone-nfs-server](https://gitlab.com/encircle360/rclone-nfs-server) - Dockerized NFS server exposing any rclone remote as an NFS share. Useful in Kubernetes for providing cached mount points.

## Docker Images

* [rclone/rclone (official)](https://hub.docker.com/r/rclone/rclone) - Official Alpine-based Docker image maintained by rclone developers. Tracks latest stable and beta releases.
* [pfidr/rclone](https://hub.docker.com/r/pfidr/rclone/) - Community image for scheduled rclone sync jobs via cron with Healthchecks.io integration.
* [mumiehub/rclone-mount](https://hub.docker.com/r/mumiehub/rclone-mount) - Container running rclone mount to expose cloud storage to host or other containers.
* [openbridge/ob\_bulkstash](https://github.com/openbridge/ob_bulkstash) ⭐ 117 | 🐛 3 | 🌐 Shell | 📅 2020-09-21 - Docker image for bulk transfers with Alpine + crond + Monit for reliability. ![GitHub stars](https://img.shields.io/github/stars/openbridge/ob_bulkstash)
* [tynor88/rclone](https://hub.docker.com/r/tynor88/rclone) - Minimal Docker image for one-off rclone copy/sync operations.
* [rayou/rclone](https://hub.docker.com/r/rayou/rclone) - Ultra-minimal (\~20MB) rclone image for custom usage.

## Forks and Alternate Builds

* [gclone (donwa)](https://github.com/donwa/gclone) ⭐ 774 | 🐛 46 | 🌐 Go | 📅 2021-04-05 - Original gclone mod optimized for Google Drive SA usage. Based on rclone v1.51. **`Inactive`** ![GitHub stars](https://img.shields.io/github/stars/donwa/gclone)
* [Rclone\_RD](https://github.com/itsToggle/rclone_RD) ⚠️ Archived - Fork integrating Real-Debrid API as a backend. Mount and stream cached torrents from Real-Debrid. ![GitHub stars](https://img.shields.io/github/stars/itsToggle/rclone_RD)
* [gclone (dogbutcat)](https://github.com/dogbutcat/gclone) ⭐ 196 | 🐛 2 | 🌐 Go | 📅 2026-04-05 - Actively maintained fork with Google Drive Service Account rotation to bypass API quotas. ![GitHub stars](https://img.shields.io/github/stars/dogbutcat/gclone)
* [gclone (l3v11)](https://github.com/l3v11/gclone) ⚠️ Archived - Another gclone fork with auto SA rotation. **`Archived`** ![GitHub stars](https://img.shields.io/github/stars/l3v11/gclone)
* [Fclone](https://github.com/NyaMisty/fclone) ⭐ 75 | 🐛 12 | 🌐 Go | 📅 2023-09-12 - Continuously updated fork providing pre-built binaries and speedy updates. ![GitHub stars](https://img.shields.io/github/stars/NyaMisty/fclone)

## Utilities and Miscellaneous

* [vim-netranger](https://github.com/ipod825/vim-netranger) ⚠️ Archived - Vim/Neovim plugin providing ranger-like file explorer with rclone cloud storage support. **`Deprecated`** ![GitHub stars](https://img.shields.io/github/stars/ipod825/vim-netranger)
* [rclone-openapi](https://github.com/rclone-ui/rclone-openapi) ⭐ 46 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-19 - OpenAPI 3.0 specification for rclone's RC API. Useful for generating clients and documentation. ![GitHub stars](https://img.shields.io/github/stars/rclone-ui/rclone-openapi)
* [rclone-config-builder](https://github.com/Lesmiscore/rclone-config-builder) ⭐ 1 | 🐛 8 | 🌐 JavaScript | 📅 2026-08-31 - Library to build rclone config files in JSON/YAML. ![GitHub stars](https://img.shields.io/github/stars/Lesmiscore/rclone-config-builder)
* [@x-cmd-pkg/rclone](https://www.npmjs.com/package/@x-cmd-pkg/rclone) - Rclone binaries repackaged as npm module for easy installation in Node projects.
* [Sprinkle](https://mmontuori.github.io/Sprinkle/) - Volume clustering utility presenting multiple rclone cloud drives as one virtual volume for backup/recovery. **`Inactive`**
* [Polo File Manager](https://teejee2008.github.io/polo/) - Advanced Linux file manager with built-in rclone integration for cloud storage. **`Inactive`**

***

## Contributing

Contributions are welcome!

Please read the [contribution guidelines](contributing.md) before submitting a pull request:

* Ensure the project is actively related to rclone
* Include a brief description and link to the project
* Check that the project isn't already listed
* Add new entries in alphabetical order within their section

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-03._

<div align="center">

<h1>Bulk Crap Uninstaller</h1>

<p><strong>Remove large amounts of unwanted Windows applications quickly with minimal user input.</strong></p>

</div>

## 🧹 Overview

Bulk Crap Uninstaller, also known as BCUninstaller or BCU, is a free and open-source program uninstaller for Windows. It is designed to help remove many unwanted applications efficiently, including cases where standard manual uninstalling would be slow, repetitive, or difficult to manage.

BCU is intended for users who understand the basics of how Windows applications are installed and removed. It was created with IT professionals in mind, but it can also be useful for individual users who want more control over application cleanup.

The project is licensed under the Apache 2.0 open source license and may be used in private and commercial settings as long as the license terms are followed.

## ✨ Features

BCUninstaller focuses on bulk application removal and cleanup workflows. Based on the project documentation, it supports:

- Removing large numbers of applications with minimal user interaction
- Cleaning up leftovers after uninstalling software
- Detecting orphaned applications
- Running uninstallers according to prepared lists
- Working with Windows Store Apps
- Working with Steam applications
- Working with Windows Features
- Special support for many uninstaller systems, including:
  - NSIS
  - Inno Setup
  - Msiexec
  - Other common uninstalling systems

These features make BCU useful when managing systems with many installed programs, cleaning up old software, or preparing a Windows environment for maintenance.

## 🖥️ System Requirements

BCUninstaller has different requirements depending on the major version.

### BCUninstaller v6

- Earliest supported OS: Windows 10  
- May work on Windows 7
- Requires .NET 8 Desktop Runtime
- Portable builds do not require the runtime to be installed separately
- v6 releases no longer include an x86 build because supported systems do not have x86 versions

### BCUninstaller v5

- Earliest supported OS: Windows 7 SP1
- Requires Windows Platform Updates such as KB2670838 and KB2533623
- Requires .NET 6 Desktop Runtime
- Portable builds include the runtime

If DLL errors occur on startup, Windows Update may be required. If a framework error appears, .NET 6 should be installed manually or through Windows Update.

### BCUninstaller v1–v4

- Earliest supported OS: Windows XP
- XP support may be unreliable in later legacy releases
- Requires .NET Framework 4.5
- Some versions can run on .NET Framework 3.5 with reduced functionality

## 🧰 Typical Use Cases

BCUninstaller is useful for several Windows software maintenance tasks:

- Removing many unwanted applications after setting up or receiving a computer
- Cleaning systems that contain outdated or unused programs
- Helping IT staff process repeated uninstall tasks more efficiently
- Finding leftover entries or orphaned application records
- Managing uninstall workflows that involve different installer technologies
- Handling applications installed from Windows Store, Steam, or Windows Features

The tool is especially relevant when the goal is to reduce repetitive manual work while still keeping visibility into what is being removed.

## 🛠️ Building

Development is done with Visual Studio 2022. The solution is expected to load and build normally when the required Visual Studio features are installed.

The installer is compiled with Inno Setup v6.4. For release preparation, the original project documentation indicates that the `publish.bat` script is run first.

## 📚 Documentation and Support

The project provides online documentation through its manual:

[BCU online manual](https://htmlpreview.github.io/?https://github.com/Klocman/Bulk-Crap-Uninstaller/blob/master/doc/BCU_manual.html)

The official homepage is also available:

[BCUninstaller homepage](https://www.bcuninstaller.com/)

For contribution information, see the project contribution notes in `CONTRIBUTING.md`.

## ❓ FAQ

### What is Bulk Crap Uninstaller used for?

Bulk Crap Uninstaller is used to remove unwanted Windows applications, especially when many programs need to be removed efficiently.

### Is BCUninstaller only for IT professionals?

No. It was designed with IT professionals in mind, but it can be used by anyone who has a basic understanding of Windows application installation and uninstallation.

### Can it remove leftovers?

Yes. The original project description states that BCU can clean up leftovers after uninstalling applications.

### Does it support Windows Store Apps?

Yes. BCUninstaller is described as fully compatible with Windows Store Apps.

### Does it support Steam applications?

Yes. BCUninstaller includes compatibility with Steam applications.

### What license does the project use?

Bulk Crap Uninstaller is licensed under the Apache 2.0 open source license.

## 📄 License

Bulk Crap Uninstaller is licensed under the Apache 2.0 license. It can be used in private and commercial environments as long as the license conditions are followed.

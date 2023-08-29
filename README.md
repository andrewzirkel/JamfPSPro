# JamfPSPro
[![Minimum Supported PowerShell Version](https://img.shields.io/badge/PowerShell-5.1+-purple.svg)](https://github.com/PowerShell/PowerShell) ![Cross Platform](https://img.shields.io/badge/platform-windows%20%7C%20macos%20%7C%20linux-lightgrey) [![License][license-badge]](LICENSE) ![Build Status Windows PowerShell Main](https://github.com/TrustyTristan/JamfPSPro/workflows/ActionsTest-Windows-Build/badge.svg?branch=master)

[license-badge]: https://img.shields.io/github/license/TrustyTristan/JamfPSPro

## Warning 

This is in a very early state, almost certainly only Get-Jamf works, even that might have issues.

## Description

JamfPSPro is a PowerShell module that aims to bring cli tools for the Jamf API, can use both Classic API and Jamf Pro API

## Getting Started

### Installation

```powershell
# how to install JamfPSPro
Install-Module -Name JamfPSPro -Repository PSGallery -Scope CurrentUser
```

### Quick start

#### Example

```powershell
Get-Command -Module JamfPSPro

```
## JamfPSPro Cmdlets
[Cmdlets list](/docs/JamfPSPro.md)

## Contributing

If you'd like to contribute to JamfPSPro, please see the [contribution guidelines](.github/CONTRIBUTING.md).

## License

JamfPSPro is licensed under the [MIT license](LICENSE).

## Author

Tristan Brazier
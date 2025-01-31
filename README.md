<div align="right">
  <picture>
    <img width="100" height="40" alt="apm logo banner" src="https://github.com/abapPM/abapPM/blob/main/img/apm_banner.png?raw=true&ver=1.0.0">
  </picture>
</div>

![Version](https://img.shields.io/endpoint?url=https://shield.abappm.com/github/abapPM/abapPM-Types/src/core/zif_types.intf.abap/c_version&label=Version&color=blue)

[![License](https://img.shields.io/github/license/abapPM/abapPM-Types?label=License&color=success)](https://github.com/abapPM/abapPM-Types/blob/main/LICENSE)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg?color=success)](https://github.com/abapPM/.github/blob/main/CODE_OF_CONDUCT.md)
[![REUSE Status](https://api.reuse.software/badge/github.com/abapPM/abapPM-Types)](https://api.reuse.software/info/github.com/abapPM/abapPM-Types)

# Types and Constants for apm

Interface containing types and constants used by apm.

apm is a *package manager* 📦 for ABAP applications and modules, a *website* 🌐, and a *registry* 📑.

You can find the *website* at https://abappm.com and the *registry* at https://registry.abappm.com.

NO WARRANTIES, [MIT License](LICENSE)

## Usage

```abap
"! Schema for package.abap.json
TYPES BEGIN OF ty_package_json

"! Full manifest
TYPES BEGIN OF ty_manifest

"! Abbreviated manifest
TYPES BEGIN OF ty_manifest_abbreviated

"! Full packument (as fetched from registry)
"! Some fields are hoisted from latest version to root
TYPES BEGIN OF ty_packument

"! Supported Engines
CONSTANTS BEGIN OF c_engine

"! Most Common Licenses (https://spdx.org/licenses/)
CONSTANTS BEGIN OF c_license

"! Operating System Platforms
CONSTANTS BEGIN OF c_os

"! Hardware Platforms
CONSTANTS BEGIN OF c_cpu

"! Database Platforms
CONSTANTS BEGIN OF c_db
```

## Prerequisites

SAP Basis 7.50 or higher

## Installation

Install `@apm/types` as a global module in your system using [apm](https://abappm.com).

or

Specify the `@apm/types` module as a dependency in your project and import it to your namespace using [apm](https://abappm.com).

## Contributions

All contributions are welcome! Read our [Contribution Guidelines](https://github.com/abapPM/abapPM-Types/blob/main/CONTRIBUTING.md), fork this repo, and create a pull request.

You can install the developer version of `@apm/types` using [abapGit](https://github.com/abapGit/abapGit) by creating a new online repository for `https://github.com/abapPM/abapPM-Types`.

Recommended SAP Package: `$APM-TYPES`

## About

Made with ❤ in Canada

Copyright 2025 apm.to Inc. <https://apm.to>

Follow [@marcf.be](https://bsky.app/profile/marcf.be) on Blueksy and [@marcfbe](https://linkedin.com/in/marcfbe) or LinkedIn

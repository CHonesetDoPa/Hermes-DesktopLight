
# Hermes Desktop Light

**A lightweight Windows portable desktop client for connecting to a remote Hermes Agent.**

[![Build Light](https://github.com/CHonesetDoPa/Hermes-DesktopLight/actions/workflows/uild-desktop-light-windows.yml/badge.svg)](https://github.com/CHonesetDoPa/Hermes-DesktopLight/actions/workflows/uild-desktop-light-windows.yml)

Hermes Desktop Light is an unofficial community-built Windows x64 desktop package based on the official [NousResearch Hermes Agent](https://github.com/NousResearch/hermes-agent) project.

It is designed for users who already run Hermes Agent on a remote Linux server or VPS. The Windows computer acts as a desktop client, while the Hermes Agent and Gateway run on the remote server.

> This is an unofficial community build. It is not an official NousResearch release.

[简体中文](README.zh-CN.md)

## Features

- Windows 10 / 11 x64 desktop application.
- Based on the official Hermes Desktop source code.
- Built using the official `light` variant.
- Designed for remote-only operation.
- Connects to a remote Hermes Gateway.
- Distributed as a portable ZIP archive.
- No MSIX installation package.
- Automated builds and releases through GitHub Actions.

## Download

Visit the [Releases](../../releases) page and download:

**Hermes-DesktopLight-Windows-x64.zip**

### Installation

1. Download the Windows x64 ZIP archive.
2. Extract it to a folder of your choice.
3. Run `Hermes.exe`.
4. Configure your remote Hermes Gateway connection.
5. Connect to your remote Hermes Agent.

No MSIX installation is required.

## Requirements

### Windows client

- Windows 10 or Windows 11, 64-bit.
- Network access to your remote Hermes Gateway.
- A supported Hermes Desktop environment.

### Remote server

- Ubuntu or another supported Linux distribution.
- Hermes Agent installed and configured.
- Hermes Gateway running.
- A reachable HTTPS endpoint.
- Valid Gateway authentication credentials.

## Important notes

- This is an unofficial community-maintained build.
- It is not affiliated with or endorsed by NousResearch.
- The application is based on the official Hermes Agent source code.
- The `light` variant is intended for remote-only operation.
- The intended design is to keep Hermes Agent and its runtime on the remote server.
- A successful CI build does not by itself prove that the application never attempts to install a local runtime. First-launch behavior should be tested on a clean Windows machine.
- Compatibility depends on the selected upstream source version.

## License and upstream project

Hermes Desktop Light is built from the official Hermes Agent project.

- Upstream repository: https://github.com/NousResearch/hermes-agent
- Upstream license and notices: Refer to the upstream repository.
- This repository: Community build workflow and release packaging.

Please review the upstream license and applicable notices before redistributing modified builds.

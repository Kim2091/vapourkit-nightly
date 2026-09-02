# Vapourkit Nightly Builds

This repository hosts automated nightly builds of [Vapourkit](https://github.com/Kim2091/vapourkit).

Please consider donating to help fund development (and keep me housed)!

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/J3J3BCC3L)

## What are nightly builds?

Nightly builds are automated builds that run every night (at 11 PM UTC) if there have been commits to the main Vapourkit repository in the last 24 hours. These builds contain the latest features and fixes but may be less stable than official releases.

## Download

Check the [Releases](../../releases) page for the latest nightly build.

## Build Information

- **Platforms**: Windows x64 and Linux x64
- **Schedule**: Daily at 11 PM UTC (if there are new commits)
- **Manual Triggers**: Can also be triggered manually via GitHub Actions
- **Formats**: 
  - `.exe` - NSIS installer
  - `.7z` - Portable archive
  - `.AppImage` - Linux portable application

## How it works

This repository uses GitHub Actions to:
1. Check for commits in the main Vapourkit repository from the last 24 hours
2. Clone the `experimental-linux` branch of the main repository
3. Build Windows installers/portable versions and a Linux AppImage
4. Create a prerelease containing all build artifacts

## Stability

⚠️ **Warning**: Nightly builds are experimental and may contain bugs. For stable releases, please use the [main Vapourkit repository](https://github.com/Kim2091/vapourkit).

## Issues

If you encounter issues with nightly builds, please report them in the [main Vapourkit repository](https://github.com/Kim2091/vapourkit/issues) and mention that you're using a nightly build.

## Source Code

The source code for Vapourkit is maintained in the [main repository](https://github.com/Kim2091/vapourkit).

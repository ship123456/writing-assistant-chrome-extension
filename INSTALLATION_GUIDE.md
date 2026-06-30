# Writing Assistant Chrome Extension

## Installation Guide

**Version:** 1.0

**Last Updated:** June 2026

## Table of Contents

- [Introduction](#introduction)
- [System Requirements](#system-requirements)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Manual Installation](#manual-installation)
- [Verifying the Installation](#verifying-the-installation)
- [Getting Started](#getting-started)
- [Updating the Extension](#updating-the-extension)
- [Uninstalling the Extension](#uninstalling-the-extension)
- [Troubleshooting Installation](#troubleshooting-installation)

## Introduction

This guide explains how to install, verify, update, and remove the Writing Assistant Chrome Extension.

The extension provides grammar checking, spelling correction, writing suggestions, and readability improvements directly within supported web pages.

Manual installation is commonly used during extension development, testing, or in environments where the Chrome Web Store is unavailable.

## System Requirements

### Supported Browsers

- Google Chrome
- Microsoft Edge (Chromium)
- Brave
- Opera

### Browser Requirements

For extension users:

- Chromium-based browser that supports Chrome Extension Manifest V3 (MV3)
- Internet connection (required only for installation or updates from the Chrome Web Store)

For extension developers (optional):

- Visual Studio Code
- Node.js
- npm

## Prerequisites

Before installation, ensure that:

- A supported Chromium-based browser is installed.
- Extension installation is enabled.
- The user has permission to install browser extensions.

## Installation

1. Open Google Chrome.
2. Visit the Chrome Web Store.
3. Search for **Writing Assistant Chrome Extension**.
4. Select the extension from the search results.
5. Click **Add to Chrome**.
6. Confirm the installation.
7. Pin the extension to the browser toolbar for quick access.

## Manual Installation

If the extension is distributed as an unpacked project or ZIP package, it can be installed manually.

1. Extract the extension folder if necessary.
2. Open **chrome://extensions**.
3. Enable **Developer mode**.
4. Click **Load unpacked**.
5. Select the extension folder.
6. Verify that the extension appears in the Extensions list.
7. Pin the extension to the toolbar if desired.

## Verifying the Installation

After installation:

1. Open **chrome://extensions**.
2. Verify that **Writing Assistant Chrome Extension** is enabled.
3. Open any supported website.
4. Click the extension icon.
5. Confirm that the popup opens successfully.
6. Type inside a supported text field and verify that writing suggestions appear.

## Getting Started

After installation:

1. Pin the extension to the browser toolbar.
2. Open a supported webpage.
3. Enable writing assistance from the extension popup.
4. Start typing in an editable text field.
5. Review and apply grammar or writing suggestions.

## Updating the Extension

To update the extension:

1. Open **chrome://extensions**.
2. Enable **Developer mode** if necessary.
3. Click **Update** to check for available extension updates.
4. Restart the browser if prompted.

Extensions installed from the Chrome Web Store update automatically by default. Extensions installed using **Load unpacked** must be updated manually after changes are made.

## Uninstalling the Extension

To remove the extension:

1. Open **chrome://extensions**.
2. Locate **Writing Assistant Chrome Extension**.
3. Click **Remove**.
4. Confirm the removal when prompted.

## Troubleshooting Installation

| Issue | Solution |
|--------|----------|
| Extension not found | Verify the extension name or installation package. |
| Installation failed | Update the browser and try again. |
| Extension not visible | Refresh the Extensions page and verify it is enabled. |
| Extension disabled | Re-enable the extension from **chrome://extensions**. |
| Load unpacked unavailable | Enable **Developer mode** before attempting manual installation. |

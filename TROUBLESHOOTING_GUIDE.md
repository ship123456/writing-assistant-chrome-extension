# Writing Assistant Chrome Extension

## Troubleshooting Guide

**Version:** 1.0

**Last Updated:** June 2026

## Table of Contents

- [Introduction](#introduction)
- [Common Issues](#common-issues)
- [Installation Problems](#installation-problems)
- [Extension Activation Issues](#extension-activation-issues)
- [Writing Assistance Issues](#writing-assistance-issues)
- [Permission Issues](#permission-issues)
- [Viewing Extension Logs](#viewing-extension-logs)
- [Performance Issues](#performance-issues)
- [Frequently Asked Questions](#frequently-asked-questions)
- [Getting Support](#getting-support)

## Introduction

This guide provides solutions to common issues that users may encounter while installing or using the Writing Assistant Chrome Extension.

Follow the recommended solutions before contacting support.

## Common Issues

| Issue | Recommended Solution |
|--------|----------------------|
| Extension not installed | Verify Chrome version and install the extension again. |
| Extension icon not visible | Pin the extension from the Chrome Extensions menu. |
| Writing suggestions not appearing | Refresh the webpage and verify the extension is enabled. |
| Popup not opening | Restart Google Chrome and reopen the extension. |
| Settings not saved | Verify that the Storage permission is enabled. |

## Installation Problems

### Extension cannot be installed

Possible causes:

- Unsupported browser version
- Chrome Web Store unavailable
- Corrupted installation package

Recommended solution:

- Update Google Chrome.
- Retry the installation.
- Reinstall the extension.
- Install using a packaged extension if available.

## Extension Activation Issues

Manifest V3 service workers may become idle after periods of inactivity.

If the extension does not respond immediately, click the extension toolbar icon to reactivate the service worker, then try again.

### Extension does not activate

Possible causes:

- Extension disabled
- Browser restart required
- Unsupported webpage

Recommended solution:

1. Open **chrome://extensions**.
2. Verify the extension is enabled.
3. Restart Google Chrome.
4. Refresh the webpage.

## Writing Assistance Issues

### Grammar or spelling suggestions do not appear

Possible causes:

- Writing assistance is disabled.
- The webpage is unsupported.
- Text field is not editable.
- Required permissions are not granted.
- High-security websites may restrict extension execution through Content Security Policy (CSP).
- Rich text editors using a closed Shadow DOM may limit extension functionality.

Recommended solution:

- Enable writing assistance from the extension popup.
- Refresh the webpage.
- Verify that you are typing inside a supported editable field.
- Grant the required permissions if prompted.
- Test the extension on another supported website if suggestions do not appear.

## Permission Issues

### Required permissions are unavailable

Possible causes:

- Site access disabled
- Browser permissions restricted
- Extension permissions revoked

Recommended solution:

1. Open **chrome://extensions**.
2. Locate **Writing Assistant Chrome Extension**.
3. Open **Details**.
4. Verify that the required permissions are enabled.
5. Reload the webpage.

## Viewing Extension Logs

If the extension behaves unexpectedly, diagnostic information can be viewed using Google Chrome Developer Tools.

### Chrome Extension Errors

1. Open **chrome://extensions**.
2. Enable **Developer mode**.
3. Locate **Writing Assistant Chrome Extension**.
4. Select **Errors** to review extension error messages.

### Browser Developer Tools

1. Open the affected webpage.
2. Press **F12** (Windows/Linux) or **Option + Command + I** (macOS).
3. Open the **Console** tab.
4. Review any error messages related to the extension.

## Performance Issues

### Extension responds slowly

Possible causes:

- Large webpage
- Multiple browser extensions
- Low system memory
- Service worker temporarily inactive (Manifest V3 behavior)

Recommended solution:

- Refresh the webpage.
- Close unnecessary browser tabs.
- Disable unused browser extensions.
- Restart Google Chrome.

## Frequently Asked Questions

### Why are writing suggestions not displayed?

Verify that the extension is enabled and that the current webpage supports editable text fields.

### Does the extension work offline?

Basic writing assistance is available locally. Advanced writing suggestions may require an internet connection.

### Which browsers are supported?

Google Chrome and Chromium-based browsers such as Microsoft Edge, Brave, and Opera.

### Is my text stored?

The extension processes text locally by default and does not store user content without user interaction.

### Can I customize writing preferences?

Yes. Writing preferences can be configured through the extension settings.

### Why doesn't the extension work on some websites?

Some enterprise or security-sensitive websites use strict Content Security Policies (CSP) or closed Shadow DOM implementations that restrict extension functionality. In these cases, writing suggestions may be limited or unavailable.

## Getting Support

If the issue persists after following this guide:

- Restart Google Chrome.
- Reinstall the extension.
- Review the Installation Guide and User Guide.
- Check the Chrome Extension Errors page or Browser Developer Tools Console.
- Contact the project maintainer with details of the issue, browser version, operating system, and any relevant error messages.

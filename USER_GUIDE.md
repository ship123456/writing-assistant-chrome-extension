# Writing Assistant Chrome Extension

## User Guide

**Version:** 1.0

**Last Updated:** June 2026

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Extension Overview](#extension-overview)
- [Installation](#installation)
- [Launching the Extension](#launching-the-extension)
- [User Interface](#user-interface)
- [Using the Writing Assistant](#using-the-writing-assistant)
- [Features](#features)
- [Managing Settings](#managing-settings)
- [Tips & Best Practices](#tips--best-practices)
- [Troubleshooting](#troubleshooting)
- [Frequently Asked Questions](#frequently-asked-questions)

## Introduction

The Writing Assistant Chrome Extension helps users improve their writing directly within supported websites by providing grammar checking, spelling correction, writing suggestions, readability improvements, and vocabulary enhancement.

The extension is designed to simplify writing while maintaining a fast and intuitive user experience inside the browser.

## Getting Started

Before using the extension, ensure that:

- A supported Chromium-based browser is installed.
- The Writing Assistant Chrome Extension is installed.
- The extension is enabled.
- The website contains an editable text field.

## Extension Overview

The extension provides the following capabilities:

- Grammar checking
- Spelling correction
- Writing suggestions
- Readability improvements
- Vocabulary enhancement
- Tone suggestions
- Real-time writing assistance

## Installation

1. Install the extension from the Chrome Web Store or using the unpacked extension method.
2. Enable the extension if prompted.
3. Pin the extension to the browser toolbar.
4. Open a supported website.

## Launching the Extension

To launch the extension:

1. Click the **Writing Assistant** icon in the browser toolbar.
2. Open the extension popup.
3. Enable writing assistance if it is disabled.
4. Begin typing on a supported webpage.

## User Interface

The extension popup includes:

- Writing Assistant Status
- Enable/Disable Toggle
- Writing Suggestions
- Grammar Summary
- Settings Shortcut
- Theme Selection

![Dashboard](images/dashboard_image.png)

## Using the Writing Assistant

To improve your writing:

1. Open a supported webpage.
2. Click inside an editable text field.
3. Start typing.
4. Grammar and spelling issues are highlighted with inline indicators as you type.
5. Hover over the highlighted text to view suggested corrections or alternative wording.
6. Click a suggestion to apply the recommended change.
7. Click **Ignore** or dismiss the suggestion if you do not want to apply it.
8. Continue writing while reviewing additional suggestions in real time.

## Features

| Feature | Description |
|---------|-------------|
| Grammar Checking | Detects grammar mistakes while typing |
| Spelling Correction | Identifies spelling errors |
| Writing Suggestions | Recommends clearer sentence structure |
| Readability Improvements | Improves sentence readability |
| Vocabulary Enhancement | Suggests alternative word choices |
| Tone Suggestions | Helps maintain an appropriate writing tone |
| Real-Time Assistance | Displays suggestions as the user types |

## Managing Settings

The extension allows users to configure:

- Enable or disable writing assistance
- Light and Dark themes
- Writing preferences
- Suggestion notifications
- Language preferences (when supported)

Changes are automatically saved using Chrome's Storage API.

## Tips & Best Practices

For the best experience:

- Keep the extension updated.
- Pin the extension for quick access.
- Use supported Chromium-based browsers.
- Review suggestions before accepting them.
- Refresh the webpage if suggestions stop appearing.

## Troubleshooting

| Issue | Solution |
|--------|----------|
| Extension icon missing | Pin the extension from the Chrome Extensions menu. |
| Suggestions not appearing | Refresh the webpage and verify the extension is enabled. |
| Popup not opening | Restart the browser and reopen the extension. |
| Settings not saved | Verify Storage permission is available. |

## Frequently Asked Questions

### Does the extension work offline?

Basic writing assistance is available locally. Advanced writing suggestions may require an internet connection.

### Which browsers are supported?

Google Chrome, Microsoft Edge (Chromium), Brave, and Opera.

### Can I customize writing preferences?

Yes. Preferences can be managed through the extension settings.

### Is my writing stored?

The extension processes text locally by default and does not store user content without user interaction.

### Why are suggestions unavailable on some websites?

Some enterprise or security-sensitive websites use strict Content Security Policies (CSP) or closed Shadow DOM implementations that may restrict extension functionality.

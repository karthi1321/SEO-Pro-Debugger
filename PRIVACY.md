# Privacy Policy for SEO Pro Debugger

**Last Updated:** October 17, 2025
**Effective Date:** October 17, 2025

---

## Overview

SEO Pro Debugger ("the Extension") is committed to protecting your privacy. This privacy policy explains our data practices for the SEO Pro Debugger Chrome extension.

**TL;DR: We don't collect, store, or transmit ANY of your data. Period.**

---

## Data Collection

### What We DO NOT Collect

✅ **No Personal Information**
- We do not collect names, email addresses, or any personal identifiers
- We do not track user behavior
- We do not collect browsing history
- We do not collect passwords or credentials

✅ **No Analytics**
- We do not use Google Analytics or any analytics service
- We do not track how you use the extension
- We do not collect usage statistics
- We do not send telemetry data

✅ **No External Requests**
- The extension does not make any network requests
- No data is sent to our servers (we don't even have servers!)
- All SEO analysis happens 100% locally in your browser

✅ **No Cookies or Tracking**
- We do not set cookies
- We do not use fingerprinting
- We do not track you across websites

### What We DO Use

The extension uses Chrome's local storage API **only** to save your preferences, such as:
- Whether the "Page Summary" section is expanded or collapsed
- This data never leaves your computer

---

## Permissions Explained

The extension requires certain permissions to function. Here's exactly why:

### `activeTab`
**Why we need it:** To analyze the SEO elements of the current webpage
**What it does:** Allows the extension to read the HTML of the page you're viewing
**When it's used:** Only when you click "Run Audit"
**What we DON'T do:** We don't access tabs you're not actively analyzing

### `scripting`
**Why we need it:** To inject our analysis code into the webpage
**What it does:** Reads meta tags, headings, images, links, and other SEO elements
**When it's used:** Only when you run an audit
**What we DON'T do:** We don't modify the page or execute any malicious code

### `storage`
**Why we need it:** To save your preferences locally
**What it does:** Stores settings like collapsed/expanded sections
**When it's used:** When you change a preference
**What we DON'T do:** We don't store any webpage data or personal information

### `sidePanel`
**Why we need it:** To display the side panel interface
**What it does:** Opens the analysis panel alongside your browser
**When it's used:** When you click "Open Side Panel"
**What we DON'T do:** We don't access other extensions or browser data

### `clipboardWrite`
**Why we need it:** To copy suggested fixes to your clipboard
**What it does:** Copies HTML/JSON code when you click "Copy Fix"
**When it's used:** Only when you explicitly click a "Copy Fix" button
**What we DON'T do:** We don't read your clipboard or copy anything automatically

### `tabs`
**Why we need it:** To identify which tab you're analyzing
**What it does:** Gets the tab ID of the page you're auditing
**When it's used:** When opening the side panel or full report
**What we DON'T do:** We don't access other tabs or tab contents

### `host_permissions: <all_urls>`
**Why we need it:** To analyze any website you visit
**What it does:** Allows the extension to work on any domain
**When it's used:** Only on pages where you run an audit
**What we DON'T do:** We don't access pages you don't explicitly analyze

---

## How SEO Analysis Works

1. **You click "Run Audit"** on a webpage
2. **The extension reads** the page's HTML (meta tags, headings, images, etc.)
3. **Analysis happens locally** in your browser (no data sent anywhere)
4. **Results are displayed** in the side panel or full report
5. **Data is stored temporarily** in your browser's memory
6. **You can export** data as JSON or CSV files to your computer

**Important:** All analysis is performed **locally on your device**. Nothing is sent to external servers.

---

## Third-Party Services

**We do not use ANY third-party services, including:**
- ❌ Google Analytics
- ❌ Facebook Pixel
- ❌ Advertising networks
- ❌ Error tracking services (e.g., Sentry, Rollbar)
- ❌ Cloud storage services
- ❌ External APIs

The extension is **completely self-contained** and works entirely offline.

---

## Data Storage

### Local Storage Only
- User preferences are stored locally using Chrome's storage API
- This data includes UI settings (e.g., collapsed/expanded sections)
- This data **never leaves your computer**
- You can clear this data anytime by uninstalling the extension

### No Cloud Storage
- We do not store any data on external servers
- We do not have a database
- We do not have user accounts

---

## Data Sharing

**We do not share, sell, or rent your data to anyone.**

Why? Because we don't collect any data in the first place!

---

## Children's Privacy

This extension does not knowingly collect any information from children under 13. The extension is designed for web developers, SEO professionals, and content creators.

---

## Open Source

SEO Pro Debugger is **open source software**. You can review the source code to verify our privacy practices:

🔗 **GitHub Repository:** [github.com/[your-repo]/seo-pro-debugger](#)

We encourage security researchers and privacy advocates to audit our code.

---

## Changes to This Privacy Policy

We may update this privacy policy from time to time. Changes will be noted in the "Last Updated" date at the top of this document.

If we make significant changes, we will update the version number and notify users through:
- Extension update notes in the Chrome Web Store
- A notice in the extension's UI (if applicable)

---

## Your Rights

### You have the right to:
- ✅ **Know what data we collect** (None!)
- ✅ **Request data deletion** (There's no data to delete)
- ✅ **Opt-out of tracking** (There's no tracking)
- ✅ **Review our source code** (It's open source)

### How to Delete Extension Data
1. Go to `chrome://extensions/`
2. Find "SEO Pro Debugger"
3. Click "Remove"
4. All local preferences will be deleted

Alternatively, you can clear extension storage:
1. Right-click the extension icon
2. Go to "Manage Extension"
3. Click "Clear storage"

---

## Contact Us

If you have questions about this privacy policy or our privacy practices:

📧 **Email:** support@centilio.com
🌐 **Website:** https://centilio.com
🐛 **Issues:** [GitHub Issues](https://github.com/[your-repo]/seo-pro-debugger/issues)

---

## Legal Compliance

This privacy policy complies with:
- ✅ **GDPR** (General Data Protection Regulation - EU)
- ✅ **CCPA** (California Consumer Privacy Act - USA)
- ✅ **Chrome Web Store Policies**

---

## Summary

**In plain English:**

1. We don't collect your data
2. We don't track you
3. We don't send anything to servers
4. Everything happens locally
5. You're in complete control
6. The code is open source

**Questions?** Contact us at support@centilio.com

---

**Copyright © 2025 Centilio Software**
**Licensed under MIT License**

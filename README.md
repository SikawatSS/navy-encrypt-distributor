# Navy Encrypt Distribution

Enterprise distribution portal for Navy Encrypt iOS application (รับส่งไฟล์).

## Overview

This repository hosts a password-protected download page for the Navy Encrypt iOS enterprise application. Users can download the IPA file after entering the correct password.

**Organization:** NAVAL COMMUNICATIONS AND INFORMATION TECHNOLOGY DEPARTMENT

## Features

- 📱 OTA (Over-The-Air) Installation - Install directly from iPhone/iPad
- 🎯 No computer required - Users can install from their device
- 📝 Step-by-step installation instructions
- 🌐 Hosted on GitHub Pages (free)
- 💻 Fallback download for desktop users

## File Structure

```

navy-distributor/
├── index.html # Main download page with password protection
├── downloads/
│ ├── navy_encrypt.ipa # iOS app file (12 MB)
│ └── manifest.plist # OTA installation manifest (iOS configuration)
├── .gitignore # Git ignore rules
└── README.md # This file

```

### For iPhone/iPad Users (OTA Installation - Recommended)

1. **Open Safari** on your iPhone or iPad
2. Visit the distribution page: `https://YOUR_USERNAME.github.io/navy-distributor/`
3. Tap the **"ติดตั้ง Navy Encrypt"** (Install Navy Encrypt) button
4. iOS will show a confirmation dialog → Tap **"Install"**
5. Wait for the app to download and install (you'll see the icon on your home screen)
6. Go to **Settings → General → Device Management**
7. Select the Navy enterprise profile and tap **"Trust"**
8. Return to home screen and open Navy Encrypt

### "Unable to Install" Error

- The enterprise certificate may have expired
- The bundle identifier may not match your provisioning profile
- Check Settings → General → Device Management for any existing profiles

### App Doesn't Open After Installation

1. Go to **Settings → General → Device Management**
2. Find the Navy enterprise profile
3. Tap it and select **"Trust"**
4. Try opening the app again

## Support

For issues with the app or distribution, contact the NAVAL COMMUNICATIONS AND INFORMATION TECHNOLOGY DEPARTMENT.

## License

This is an enterprise application for authorized Navy personnel only.

```

```

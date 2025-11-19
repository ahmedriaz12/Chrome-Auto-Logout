# Chrome Auto Logout
Automatically logs users out of Chrome after a chosen period of inactivity.

<p align="left">
  <a target="_blank" href="https://chrome.google.com/webstore/detail/ngldgdloflfmfcnefhnkoodnbidemldm">
    <img src="https://github.com/ahmedriaz12/cros-info/raw/master/cws.png" alt="Install from Chrome Web Store">
  </a>
</p>

## 🚀 Quick Start
1. Install the extension from the Chrome Web Store (link above).
2. By default, the extension logs you out after **30 minutes of inactivity**.
3. To customize settings, right-click the extension icon and select **Options**.

## ⚙️ Features
- Set a custom idle timeout (15 seconds → 2 weeks).
- Choose a logout URL (default: `https://accounts.google.com/Logout`).
- Option to bring the logout tab into focus.
- Lightweight and simple—doesn’t track or store any user data.

## ⚠️ Known Limitations
- **ChromeOS is not supported.** ChromeOS admins can enforce idle lock using system policies.
- A device that is already **locked, sleeping, or showing screensaver is NOT counted as idle.**
- The logout action is **best effort** and can be bypassed with:
  - USB mouse jigglers
  - Chrome extensions that simulate activity
  - …or a very enthusiastic primate smashing the keyboard

## 🔧 Extension Options
Right-click the extension icon → **Options**:
- Idle timeout duration (15–1,209,600 seconds)
- Logout trigger URL
- Toggle: Should the logout tab take focus?

## 🛠️ Admin Deployment (Force Install)
Admins using Workspace, Cloud Identity, or GCP can push this extension to users.

1. Install the extension locally.
2. Configure your preferred options.
3. Click **Download policy** and save the generated file.
4. Follow Google’s guide to:
   - [Force-install the extension](https://support.google.com/chrome/a/answer/6306504?hl=en)
   - [Upload the custom policy](https://support.google.com/chrome/a/answer/6177447#custom)
5. Optionally enforce Chrome usage via Context-Aware Access or BeyondCorp.

---

Want me to customize the README even more—add badges, screenshots, contributing guidelines, or a license section?

# NoTTer

**A powerful timestamped note-taking extension for YouTube, available for Firefox and Chrome.**



### **👉 Press "N" (or "n") anywhere for a notepad/audio recording popup to appear on your screen, . Press "P" (or "p") to pin a particular moment of any youtube video.**


## Features


- **Timestamped Notes:** Save notes linked to specific moments in YouTube videos.
- **Rich-Text Editor:** Create detailed notes with formatted text.
- **Screenshot Previews:** Capture and preserve visual references from videos.
- **Audio Recordings:** Record and play audio associated with your notes.
- **YouTube Sidebar:** Access your notes directly while watching videos.
- **Floating Notepad:** Take notes without leaving the video.
- **Folders:** Organize notes into manageable collections.
- **Study Packs:** Organize learning materials into dedicated study collections.
- **Dedicated Dashboard:** Manage and review your saved notes in one place.
- **Cloud Synchronization:** Synchronize your notes across devices using Supabase.
- **Authentication:** Securely access your synchronized data using your Supabase account.

## Supported Browsers

| Browser         | Availability    |
| --------------- | --------------- |
| Mozilla Firefox | Source included |
| Google Chrome   | Source included |

See the browser-specific installation instructions below.

## Installation

### Mozilla Firefox

1. Download the firefox zip from the Releases section and extract it to your desired location.
2. Go to `about:config`, paste this in the search bar: `xpinstall.signatures.required`, and toggle it to "false"
3. Go to `about:addons` and click on the **gear** icon and click `Install Add-on from file`
4. Navigate to the extracted folder directory.
5. Select the extracted folder.



### Google Chrome

1. Download the chrome zip from the Releases section and extract it to your desired location.
2. Open `chrome://extensions`.
3. Enable **Developer mode**.
4. Click **Load unpacked**.
5. Select the extracted folder.

## Supabase Cloud Synchronization

The extension uses Supabase for authentication and cloud synchronization.

To configure synchronization:

1. Create a Supabase project.
2. Run the SQL setup script provided in the extension settings.
3. Configure the extension with your Supabase project URL and publishable key.
4. Sign in using your account.
5. Synchronize your notes across your supported devices.


```
Privacy and Security:-

This project uses Supabase for authentication and cloud synchronization. Users should configure their own Supabase project and ensure appropriate Row Level Security policies are enabled. Do not share private credentials, access tokens or secret keys.
```



## License

This project is licensed under the MIT License.

See the `LICENSE` file for details.

---

**Project:** NoTTer
**Maintainer:** Motachondria

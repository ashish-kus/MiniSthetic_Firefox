# Minimal Aesthetic Firefox CSS

A lightweight and minimalist CSS theme for Firefox that enhances aesthetics without compromising performance. This CSS aims to provide a sleek, distraction-free browsing experience while keeping customization options for those who enjoy personalizing their interface.

## Preview

<div align="center" width="100%"> <img src="./ASSETS/Preview/preview_2.png"> </div>

## Installation Guide

To install this custom CSS theme in Firefox, follow these steps:

1. **Enable Custom CSS in Firefox**
   - Type `about:config` in your URL bar and press Enter.
   - If prompted, click **I accept the risk**.
   - Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to **true**.

2. **Enable Sidebar/Vertical Tabs**
   - In `about:config`, search for `sidebar.verticalTab` and set it to **true**.
   - Then, search for `sidebar.revamp` and set it to **true**.

3. **Locate Your Firefox Profile Folder**
   - Linux: `$HOME/.mozilla/firefox/######.default-release/`
   - MacOS: `Users/[USERNAME]/Library/Application Support/Firefox/Profiles/######.default-release`
   - Windows: `C:\Users\[USERNAME]\AppData\Roaming\Mozilla\Firefox\Profiles\######.default-release`

4. **Copy Files to Your Profile**
   - Copy the `chrome` folder (containing `userChrome.css` and any other necessary CSS files) into your Firefox profile folder.
   - Restart Firefox to apply the CSS theme.

5. **Customize to Your Liking** *(optional)*
   - Open the CSS files in the `chrome` folder and modify the styles to suit your preferences.

---

**Looking for Contributions!**

I’m actively looking for contributions to improve this project. If you have ideas, customizations, or suggestions, please feel free to contribute!

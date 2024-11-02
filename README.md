# Minimal Aesthetic Firefox CSS

A lightweight and minimalist CSS theme for Firefox that enhances aesthetics without compromising performance. This CSS aims to provide a sleek, distraction-free browsing experience while keeping customization options for those who enjoy personalizing their interface.

## Preview

![Preview of Minimal Aesthetic Firefox CSS](preview.png)

## Installation Guide

To install this custom CSS theme in Firefox, follow these steps:

1. **Enable Custom CSS in Firefox**
   - Type `about:config` in your URL bar.
   - If prompted, click **I accept the risk**.
   - Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to **true**.

2. **Enable Sidebar/Vertical Tabs**
   - Search for `browser.tabs.drawInTitlebar` and set it to **false**. This will make room for vertical tabs by disabling tabs in the title bar.
   - Search for `browser.proton.enabled` and set it to **false** to support certain sidebar adjustments.
   - **Optional CSS Configuration:** Customize the `userChrome.css` file in the `chrome` folder for further adjustments to vertical tabs (e.g., tab size, styling).

3. **Locate Your Firefox Profile Folder**
   - Linux: `$HOME/.mozilla/firefox/######.default-release/`
   - MacOS: `Users/[USERNAME]/Library/Application Support/Firefox/Profiles/######.default-release`
   - Windows: `C:\Users\[USERNAME]\AppData\Roaming\Mozilla\Firefox\Profiles\######.default-release`

4. **Copy Files to Your Profile**
   - Copy the `chrome` folder into your Firefox profile folder.
   - Restart Firefox to apply the CSS theme.

5. **Customize to Your Liking** *(optional)*
   - Open the CSS files in the `chrome` folder and modify styles to suit your preferences.

---

**Looking for Contributions!**

I’m actively looking for contributions to improve this project. If you have ideas, customizations, or suggestions, please feel free to contribute!

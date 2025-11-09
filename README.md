# pretty-windows 🪟✨

A comprehensive guide to transform Windows 11 into a more aesthetic and visually appealing experience with blur effects, translucency, and modern customizations.

## 📋 Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installing Windhawk](#installing-windhawk)
- [Windows Blur and Translucency Setup](#windows-blur-and-translucency-setup)
- [Firefox Translucency (FlexFox)](#firefox-translucency-flexfox)
- [Additional Tips](#additional-tips)
- [Troubleshooting](#troubleshooting)
- [Resources](#resources)

## 🎯 Overview

This guide will help you achieve a beautiful, modern Windows 11 desktop with:
- **Blur effects** on windows and UI elements
- **Translucent backgrounds** for taskbar, windows, and menus
- **Customized Firefox** with translucent elements and enhanced usability
- **System-wide visual improvements** using Windhawk mods

## ✅ Prerequisites

Before starting, ensure you have:
- Windows 11 (22H2 or later recommended)
- Administrator access to your system
- Internet connection for downloads
- Basic familiarity with Windows Settings

## 🔧 Installing Windhawk

Windhawk is a powerful customization platform that allows you to modify Windows behavior and appearance using community-created mods.

### Step 1: Download Windhawk

1. Visit the official Windhawk website: [https://windhawk.net/](https://windhawk.net/)
2. Click the **Download** button to get the latest installer
3. Alternatively, download directly from GitHub: [https://github.com/ramensoftware/windhawk/releases](https://github.com/ramensoftware/windhawk/releases)

### Step 2: Install Windhawk

1. Run the downloaded installer (`windhawk_setup.exe`)
2. Follow the installation wizard:
   - Accept the license agreement
   - Choose installation location (default is recommended)
   - Click **Install**
3. Wait for the installation to complete
4. Launch Windhawk from the Start menu or desktop shortcut

### Step 3: Initial Setup

1. When Windhawk opens, you'll see the main interface
2. Allow Windhawk to run with administrator privileges when prompted
3. Windhawk will start in the system tray - look for the 🪝 icon

## 🌫️ Windows Blur and Translucency Setup

Transform your Windows interface with beautiful blur and translucency effects using Windhawk mods.

### Essential Mods for Blur and Translucency

#### 1. **Translucent Taskbar**

Makes your taskbar translucent with customizable opacity and blur.

1. Open Windhawk
2. Click on **Explore** tab
3. Search for "Translucent Taskbar" or "TranslucentTB"
4. Click **Install**
5. Configure settings:
   - **Opacity**: Adjust to your preference (20-40% recommended for good visibility)
   - **Blur**: Enable for frosted glass effect
   - **Dynamic**: Adapts transparency based on maximized windows

#### 2. **Mica For Everyone**

Applies Windows 11's Mica material effect to title bars across all applications.

1. In Windhawk, search for "Mica For Everyone"
2. Click **Install**
3. Configure:
   - **Enable Mica**: Turn on for all windows
   - **Backdrop Type**: Choose between Mica, Acrylic, or Tabbed
   - **Extend to title bar**: For seamless look

#### 3. **Acrylic Effect Everywhere**

Adds acrylic blur effect to various Windows components.

1. Search for "Acrylic" in Windhawk mods
2. Install "Acrylic Effect Everywhere" or similar mod
3. Settings to configure:
   - **Blur strength**: Medium to High
   - **Tint color**: Match your theme
   - **Apply to**: Context menus, Start menu, File Explorer

#### 4. **Windows 11 Fluent Effects**

Enhances the Fluent Design System with additional blur and transparency.

1. Search for "Fluent" or "Blur" mods
2. Install recommended fluent design mods
3. Customize:
   - **Window borders**: Add blur and glow effects
   - **Animations**: Enable smooth transitions
   - **Shadow effects**: Enhance depth perception

### Recommended Mod Settings

After installing mods, fine-tune these settings for best results:

- **Taskbar opacity**: 25-35%
- **Window blur radius**: 30-50px
- **Acrylic tint**: Light or Dark based on theme
- **Animation speed**: Fast (0.2-0.3s)

### Applying Changes

1. After installing and configuring mods, click **Apply** or **Restart Windhawk**
2. Some changes may require logging out and back in
3. For best results, restart Windows Explorer:
   - Press `Ctrl + Shift + Esc` to open Task Manager
   - Find "Windows Explorer"
   - Right-click → **Restart**

## 🦊 Firefox Translucency (FlexFox)

Make Firefox beautiful with translucent effects and enhanced usability.

### Step 1: Install Firefox

1. Download Firefox from: [https://www.mozilla.org/firefox/](https://www.mozilla.org/firefox/)
2. Install using the standard installer
3. Launch Firefox

### Step 2: Enable userChrome Customization

Firefox requires enabling custom CSS support:

1. Type `about:config` in the Firefox address bar
2. Click **Accept the Risk and Continue**
3. Search for: `toolkit.legacyUserProfileCustomizations.stylesheets`
4. Double-click to set it to **true**

### Step 3: Locate Your Firefox Profile

1. Type `about:support` in the address bar
2. Find **Profile Folder** and click **Open Folder**
3. This opens your Firefox profile directory

### Step 4: Create Chrome Folder

1. In your profile folder, create a new folder named `chrome` (lowercase)
2. Inside the `chrome` folder, create a file named `userChrome.css`

### Step 5: Add Translucency CSS

Open `userChrome.css` in a text editor and add the following code:

```css
/* Firefox Translucent Theme - FlexFox Style */

/* Make toolbar backgrounds translucent */
#navigator-toolbox {
  background-color: rgba(28, 28, 28, 0.7) !important;
  backdrop-filter: blur(20px) !important;
}

/* Translucent tab bar */
#TabsToolbar {
  background-color: transparent !important;
}

/* Active tab styling */
.tabbrowser-tab[selected="true"] .tab-background {
  background-color: rgba(60, 60, 60, 0.8) !important;
  backdrop-filter: blur(10px) !important;
}

/* Inactive tabs */
.tabbrowser-tab:not([selected="true"]) .tab-background {
  background-color: rgba(40, 40, 40, 0.5) !important;
}

/* URL bar translucency */
#urlbar {
  background-color: rgba(50, 50, 50, 0.7) !important;
  backdrop-filter: blur(15px) !important;
  border: 1px solid rgba(255, 255, 255, 0.1) !important;
}

/* Sidebar translucency */
#sidebar-box {
  background-color: rgba(28, 28, 28, 0.8) !important;
  backdrop-filter: blur(20px) !important;
}

/* Dropdown menus */
menupopup {
  background-color: rgba(40, 40, 40, 0.9) !important;
  backdrop-filter: blur(15px) !important;
}

/* Context menu */
#contentAreaContextMenu {
  background-color: rgba(40, 40, 40, 0.9) !important;
  backdrop-filter: blur(20px) !important;
}
```

### Step 6: Install Useful Firefox Extensions

Enhance Firefox functionality with these extensions:

1. **uBlock Origin**: Ad blocker
   - [https://addons.mozilla.org/firefox/addon/ublock-origin/](https://addons.mozilla.org/firefox/addon/ublock-origin/)

2. **Tree Style Tab**: Vertical tabs with better organization
   - [https://addons.mozilla.org/firefox/addon/tree-style-tab/](https://addons.mozilla.org/firefox/addon/tree-style-tab/)

3. **Dark Reader**: Universal dark mode
   - [https://addons.mozilla.org/firefox/addon/darkreader/](https://addons.mozilla.org/firefox/addon/darkreader/)

4. **Sidebery**: Advanced sidebar management
   - [https://addons.mozilla.org/firefox/addon/sidebery/](https://addons.mozilla.org/firefox/addon/sidebery/)

### Step 7: Apply Firefox Theme

1. Go to `about:addons` in Firefox
2. Click **Themes** in the left sidebar
3. Choose a dark theme or search for "translucent" themes
4. Click **Enable** on your preferred theme

### Step 8: Restart Firefox

1. Close Firefox completely
2. Reopen Firefox to see the translucent effects
3. Adjust CSS values in `userChrome.css` as needed for your preference

### Customization Tips

- **Adjust opacity**: Change the `0.7` values (0.0 = fully transparent, 1.0 = opaque)
- **Blur intensity**: Modify `blur(20px)` to increase or decrease blur
- **Color tints**: Change RGB values `rgba(28, 28, 28, ...)` for different colors
- **Light theme**: Use lighter colors like `rgba(240, 240, 240, 0.8)` for light mode

## 💡 Additional Tips

### System-Wide Enhancements

1. **Enable Windows Transparency Effects**:
   - Open Settings → Personalization → Colors
   - Turn on **Transparency effects**

2. **Use Dark Mode**:
   - Settings → Personalization → Colors
   - Choose **Dark** mode for better translucency appearance

3. **Accent Color**:
   - Choose an accent color that complements translucent effects
   - Enable **Show accent color on title bars and window borders**

4. **Wallpaper Selection**:
   - Use high-quality, medium-contrast wallpapers
   - Avoid extremely busy or bright backgrounds
   - Gradients work particularly well with blur effects

### Performance Optimization

- **Disable effects on battery**: In Windhawk settings, configure performance profiles
- **Adjust blur quality**: Lower blur radius on older hardware
- **Monitor GPU usage**: Use Task Manager to ensure effects aren't causing issues

## 🔧 Troubleshooting

### Windhawk Issues

**Problem**: Mods not applying after installation
- **Solution**: Restart Windhawk service or reboot Windows
- Check if mods are enabled in Windhawk settings
- Ensure you have administrator privileges

**Problem**: Performance issues or lag
- **Solution**: Disable some mods to identify the culprit
- Reduce blur intensity in mod settings
- Update graphics drivers

**Problem**: Windhawk doesn't start
- **Solution**: Run as administrator
- Check Windows Defender hasn't quarantined files
- Reinstall Windhawk from the official source

### Firefox Issues

**Problem**: userChrome.css not loading
- **Solution**: Verify `toolkit.legacyUserProfileCustomizations.stylesheets` is set to `true`
- Check file name is exactly `userChrome.css` (case-sensitive)
- Ensure file is in correct profile folder

**Problem**: Blur effects not visible
- **Solution**: Update Firefox to latest version (blur support varies)
- Windows 10/11 required for backdrop-filter support
- Try increasing opacity values in CSS

**Problem**: Interface elements invisible
- **Solution**: Increase opacity values (e.g., from 0.5 to 0.8)
- Adjust background colors to be less transparent
- Add borders to UI elements for better visibility

## 📚 Resources

### Official Sites
- [Windhawk Official Website](https://windhawk.net/)
- [Windhawk GitHub Repository](https://github.com/ramensoftware/windhawk)
- [Firefox UserChrome Documentation](https://www.userchrome.org/)

### Community Resources
- [r/Windhawk Subreddit](https://www.reddit.com/r/windhawk/)
- [r/FirefoxCSS Subreddit](https://www.reddit.com/r/FirefoxCSS/)
- [Windows 11 Customization Communities](https://www.reddit.com/r/windows11/)

### Inspiration
- [DeviantArt - Windows Customization](https://www.deviantart.com/tag/windowscustomization)
- [/r/unixporn for Linux](https://www.reddit.com/r/unixporn/) (inspiration for Windows themes)

## 📝 License

MIT License - See [LICENSE](LICENSE) file for details

## 🤝 Contributing

This is a personal guide, but suggestions and improvements are welcome! Feel free to:
- Fork this repository
- Submit issues for corrections or additions
- Share your own customization tips

---

**Enjoy your beautiful, translucent Windows experience!** 🎨✨

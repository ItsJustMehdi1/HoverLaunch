# Accessibility for HoverLaunch

**HoverLaunch** is a Windows 10 and Windows 11 utility designed to open desktop folder contents and previews through hover popups.

## Current Accessibility Support

- **Reduced click and window switching:** Hovering over a mapped desktop folder opens its items in a popup and lets you step into subfolders without opening many File Explorer windows.
- **Adjustable delays:** You can adjust hover, close, and media preview delays in settings (`hover_delay_ms`, `close_delay_ms`, and `media_preview_delay_ms`) to give yourself more time to move the pointer.
- **Themes and transparency options:** Six themes (`Midnight`, `Ocean`, `Forest`, `Lavender`, `Sunset`, and `Light`) and an **Acrylic blur / transparency** toggle let you switch between translucent and solid surfaces.

## Known Limitations

HoverLaunch is still being built and currently has multiple accessibility gaps:

- **Pointer-driven detection:** Desktop folder and media hover detection relies on cursor position over desktop icons and does not yet include keyboard shortcuts or keyboard-only folder activation.
- **Screen-reader and keyboard focus:** Popup items and preview windows are not yet tuned for screen readers (such as NVDA or Narrator) or full keyboard navigation.
- **Text scaling and fixed sizing:** Some interface fonts and popup/preview sizes use fixed values, which can feel tight at higher Windows display scaling or with long names.
- **Console installer (`INSTALL.bat`):** Setup runs in a Windows command prompt window with periodic screen refreshes during stages.

## Feedback and Improvements

If you use assistive technology, custom scaling, or alternative input methods on Windows 10 or Windows 11 and run into friction with HoverLaunch, please open an [Issue](https://github.com/ItsJustMehdi1/HoverLaunch/issues) with your Windows version, display scaling, and what happened.

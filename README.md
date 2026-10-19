# Here Button

English · [简体中文](README.zh-CN.md)

Pin supported buttons from your Mac apps to a floating panel. Keep frequently used actions together, move the panel wherever you need it, or dock it to the edge of your screen.

Website: [locusable.com/here-button](https://locusable.com/here-button/)

## Demo

Dock the panel to a screen edge. It tucks away when you move the pointer away and expands on hover.

https://github.com/user-attachments/assets/b9af42b4-e07f-4c94-b162-b1a26d1b9040

## Download and install

Requires macOS 14 or later. The release installer supports both Apple Silicon and Intel Macs.

Here Button has not been released yet. Purchasing is still being set up. The download links and instructions below are for the upcoming release; the direct download link will become available when the first release is published.

- [Download HereButton_latest.dmg](https://github.com/locusable-studio/HereButton-Releases/releases/latest/download/HereButton_latest.dmg)
- [Browse releases and release notes](https://github.com/locusable-studio/HereButton-Releases/releases)

1. Download and open `HereButton_latest.dmg`.
2. Drag `Here Button.app` into the `Applications` folder.
3. Open Here Button from Applications, then eject the installer disk in Finder.
4. Click **Allow Accessibility Access** in the app. Go to **System Settings → Privacy & Security → Accessibility** and enable Here Button. If it is missing from the list, click **+** and add `Here Button.app` from Applications.
5. Return to the app. Once access is enabled, you can start picking buttons. Here Button uses a floating panel and a menu bar icon rather than a separate management window.

Accessibility access lets Here Button read and trigger the controls you select. The source app must also expose those controls through macOS Accessibility; some visible buttons cannot be pinned.

## Quick start

1. Open the source app and navigate to the button you want to pin.
2. Press `Control + Option + P`, or choose **Pick a New Button…** from the menu bar.
3. Move the pointer over the button, confirm the highlight, and click to add it to the panel. Press `Esc` to cancel. Picking a button does not trigger its action.
4. Click a pin to trigger the original control. By default, Here Button brings the source app forward first. Right-click a pin to rename or remove it, or to enable background triggering.
5. Drag the panel's edges to move it. Dock it to the left or right edge of the screen to tuck it away. The menu bar has separate options for automatically hiding the panel and expanding it on hover.

In the release version, choose **Check for Updates…** from the menu bar to install updates without downloading the installer again.

## FAQ

- **Why is there no main window?** Here Button runs through its floating panel and the icon in the macOS menu bar.
- **Why can't I pick a button?** Check that Accessibility access is enabled and keep the source page open. If the source app does not expose an actionable control, that button cannot be pinned. See [Compatibility](#compatibility) for examples.
- **Why does clicking a pin switch apps?** This is the default behavior. You can enable background triggering from the pin's context menu; support depends on the source app.
- **Need help or want to report a problem?** Email [locusablestudio@gmail.com](mailto:locusablestudio@gmail.com) with your macOS version, Here Button version, source app, and steps to reproduce the issue.

## Panel and pins

Click a pin to perform its original action. Drag the panel's edges or the spaces between buttons to move the panel. Right-click a pin to rename, remove, or hide it, or to change its background-triggering setting.

Dock the panel to the left or right screen edge. **Automatically Hide When Docked** and **Automatically Expand on Hover** can be controlled separately from the menu bar. Turn off automatic hiding to keep the docked panel expanded.

Turn on **Enable Hidden Section Beta** in the menu bar to access hidden pins using the arrow at the bottom of the panel. Disabling this option does not delete your pins.

## Combination buttons (Beta)

Turn on **Enable Combination Buttons Beta** in the menu bar, then click the folder-plus button to create a combination. Give it a name and add at least two steps. You can reorder steps and set a delay before each one.

Click a combination to run its steps in order. Execution stops if a step fails. Click a running combination again to cancel the remaining steps. Right-click it to edit, remove, or change its background-triggering setting. Turning off the Beta option hides the creation button; saved combinations remain available.

## Compatibility

Here Button depends on the source app's macOS Accessibility support. Some visible buttons cannot be picked, and some controls only work when their app is in the foreground.

- WeChat for macOS 4.1.15: previous local testing did not expose usable controls for the chat interface or sidebar, so those buttons could not be pinned.
- ChatGPT for macOS: some buttons do not expose a supported press action and cannot be pinned. This does not apply to every control in the app.

These observations apply to specific app versions and controls. Behavior may change when the source app updates. If you encounter an unsupported button, contact us using the email above.

# App compatibility

English · [简体中文](COMPATIBILITY.zh-CN.md) · [Back to README](README.md)

Here Button depends on the controls an app exposes through macOS Accessibility. The list below describes specific tested versions and controls, rather than every version or feature of an app. Support may change after an app update.

## Known limitations

### WeChat

- **App name and version:** WeChat for macOS 4.1.15.
- **macOS version:** Not recorded in the earlier test report.
- **Here Button version:** Not recorded in the earlier test report.
- **Affected page or button:** Buttons in the chat interface and sidebar.
- **Steps to reproduce:** Open the WeChat chat interface, press `Control + Option + P` in Here Button, and try to pick a button in the chat interface or sidebar.
- **Expected / actual behavior:** Expected: the button can be highlighted and pinned. Actual: usable Accessibility control information was not exposed in local testing, so these buttons could not be picked or pinned.
- **Screenshot or recording:** Not attached.

## Report an incompatible app

[Open a compatibility issue](https://github.com/locusable-studio/HereButton-Releases/issues/new?template=incompatible-app.yml) to report another app or update an existing entry. Search [existing issues](https://github.com/locusable-studio/HereButton-Releases/issues) first; reports for the same app and version can be added to the existing thread.

Use this short template, or fill in the linked issue form:

```text
App name and version:
macOS version:
Here Button version:
Affected page or button:
Steps to reproduce:
Expected / actual behavior:
Screenshot or recording (optional; remove private information):
```

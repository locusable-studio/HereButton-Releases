# App compatibility

English · [简体中文](COMPATIBILITY.zh-CN.md) · [Back to README](README.md)

Here Button depends on the controls an app exposes through macOS Accessibility. The list below describes specific tested versions and controls, rather than every version or feature of an app. Support may change after an app update.

## Known limitations

- **WeChat for macOS — 4.1.15**
  - Affected controls: buttons in the chat interface and sidebar.
  - Observed behavior: usable Accessibility control information was not exposed in local testing, so these buttons could not be picked or pinned.

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

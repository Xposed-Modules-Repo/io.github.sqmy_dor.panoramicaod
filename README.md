# CosFkAod

LSPosed module for ColorOS: use **全景沉浸 (panoramic AOD)** while a third-party theme is applied, and keep it after applying a theme.

## Features
- `com.oplus.aod`: lifts the third-party theme check (`Y2.a.k`) that blocks panoramic AOD, hides it in settings, and resets it to classic on start.
- Theme Store (`com.heytap.themestore` 17.22.1 / `com.oplus.themestore` 17.11.18): if panoramic AOD was selected and applying a theme resets AOD to classic, panoramic AOD is automatically restored.

## Usage
1. Install the APK and enable **CosFkAod** in LSPosed.
2. Scope: 息屏 (`com.oplus.aod`) + 主题商店 (`com.heytap.themestore`) + 主题基础服务 (`com.oplus.themestore`).
3. Reboot your device.
4. Pick **全景沉浸** in AOD settings (not 灵感接续, which requires theme animation).

## Notes
- Hooked symbols are obfuscated and build-specific (tested on 息屏 `17.001.0021`).
- Log tag: `CosFkAod`.

## Source & Support
- Source code: https://github.com/SQMY-dor/cosfkaod
- Issues: https://github.com/SQMY-dor/cosfkaod/issues
- License: [Apache-2.0](https://github.com/SQMY-dor/cosfkaod/blob/main/LICENSE)

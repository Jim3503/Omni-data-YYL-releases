# Omni-data-YYL

Official desktop installers published by Jim3503.

Download the latest stable version from [Releases](https://github.com/Jim3503/Omni-data-YYL-releases/releases/latest):

- Windows x64: `.exe` installer
- macOS Apple Silicon: `darwin-arm64.dmg`
- macOS Intel: `darwin-x64.dmg`

The application checks this repository for published stable releases at startup and every four hours. You can also select **Omni-data-YYL → 检查更新**. Draft and prerelease versions are excluded. Installation happens only after the user confirms; downloads are verified against `SHA256SUMS.txt` before opening.

The installer contains no model credentials, user datasets, or local model weights. Configure your own model credentials in the application's configuration folder before using model features. Existing data and configuration remain in the application's user data directory during upgrades.

These initial installers are not developer-signed or notarized. Some optional processing capabilities require local dependencies: FFmpeg for video, Python and model weights for segmentation, and macOS Apple Vision for the current OCR engine.

This is an independent application built with DeepSeek Harness, not an official DeepSeek desktop distribution.

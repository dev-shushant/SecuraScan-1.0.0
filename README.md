# SecuraScan

A desktop tool for static security analysis of Android APKs and iOS IPAs, described in the release documentation as built with Kotlin and Compose for Desktop.

This public repository contains product documentation and a packaged release. Analyzer implementation source is not included in the current repository tree.

## Download

[SecuraScan v1.0.0](https://github.com/dev-shushant/SecuraScan-1.0.0/releases/tag/v1.0.0) currently provides a **macOS `.dmg` installer**. Windows and Linux installers are not attached to this release.

## Documented workflow

1. Launch the desktop app.
2. Open an APK or IPA.
3. Review the static-analysis findings.
4. Export an HTML report.

The existing product documentation describes checks for exported components, permissions, hardcoded secrets, and insecure configurations, with severity and remediation information. These capabilities have not been independently validated in this repository audit.

## Feedback

[Report an issue](https://github.com/dev-shushant/SecuraScan-1.0.0/issues) with the app version, platform, and reproduction steps. Use a sanitized sample when sharing app packages or reports.

## Project links

[GitHub profile](https://github.com/dev-shushant) · [Releases](https://github.com/dev-shushant/SecuraScan-1.0.0/releases)

No license file is present in the current repository tree; refer to any terms supplied with the installer before redistribution.

# Changelog

All notable changes, features, and architectural capabilities of this project are documented in this file.

---

## [Unreleased]

### Changed

- **Version 1.0.0 Release Preparation**: Promoted the standalone script to version 1.0.0, updated userscript metadata and notification banners to v1.0.0, and aligned documentation, version badges, and fair-play disclaimers with the GeoFS V4.0 ecosystem.

---

## [1.0.1] - Compatibility And Documentation

### Changed

- Correct the documented GeoFS version compatibility.

---

## [1.0.0] - GeoFS V4.0 Release

### Changed

- Promote the existing GeoFS V4.0 standalone script to version 1.0.0.
- Align the release documentation and userscript metadata with the V4.0 ecosystem.

### Fixed

- **Throttle Display**: Dynamically resolved active aircraft engine counts to accurately display throttle channels for multi-engine aircraft without rendering inactive channels (`information-display_standalone.user.js`).

---

## [0.1.2] - V4 Integration Update

- Shows multi-engine throttle telemetry and dynamically resolved aircraft names.
- Live GeoFS V4 validation is pending.

## [0.1.1] - Aircraft Initialization Fixes

- Wait for initialized aircraft identity before rendering flight information.

## [0.1.0] - V4 Compatibility Fixes

- Uses V4 foundation dependencies, guards aircraft transitions, and updates ground speed, AGL, glideslope deviation, and zero-valued readings.

## [4.0.0] - GeoFS 4.0 Port & Unified V3.9 Design

- Ported to GeoFS 4.0 ecosystem with dual-host support (`beta.geo-fs.com` and `www.geo-fs.com`).
- Enforced native minimalist styling matching GeoFS-V3.9 HUD conventions.
- Integrated into GeoFS-V4.0 Core Library and Design System lifecycle.

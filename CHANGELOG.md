# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-11-03

### Added

- Initial release of ScreenShotMap.
- Export of the current map canvas as a DIN A4 landscape PNG (297 × 210 mm).
- Exact preservation of the current canvas extent – no cropping or resampling.
- Automatic layout calculation so the map fits the A4 page while keeping its aspect ratio.
- Right-aligned scale bar, flush with the right edge of the map.
- Left-aligned data source list showing all visible layers, flush with the left edge of the map.
- Data sources and scale bar start on the same horizontal line.
- Runtime-generated north arrow (SVG) placed in the upper right corner of the map.
- Date stamp in the footer area.
- PNG export at 300 DPI with a file dialog to choose the save location.
- Runtime-generated camera icon for the toolbar and menu entry.
- Plugin icon for the QGIS Plugin Manager (`icon.png`).
- `LICENSE` file (GNU General Public License v3).

### Requirements

- QGIS 4.0 or later